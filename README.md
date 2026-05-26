from dataclasses import dataclass, field
from typing import List, Dict

@dataclass(frozen=True)
class EnterpriseEcosystem:
    ventures: Dict[str, str] = field(default_factory=lambda: {
        "Dropti": "Founder & Owner — Autonomous Startup Ecosystem",
        "Zeylona": "Brand Orchestrator — AI-Driven Luxury Spices & Tea",
        "Dropti Ceylon Plantations": "Director — Premium Agro-Export Infrastructure"
    })

class TechEntrepreneur:
    """
    Synthesizing Academic Rigor, Advanced Automation, and Luxury Brand Execution.
    """
    def __init__(self) -> None:
        self.identity: str = "Savindu Geethma"
        self.academic: str = "BSc (Hons) Software Engineering (L2) — University of Birmingham City (UK)"
        self.ecosystem: EnterpriseEcosystem = EnterpriseEcosystem()
        
    @property
    def technology_matrix(self) -> Dict[str, List[str]]:
        return {
            "Languages":     ["TypeScript", "JavaScript (ES6+)", "Python", "Java", "PHP"],
            "Frontend_UI":   ["Next.js (App Router)", "React", "Tailwind CSS", "Bootstrap", "HTML5/CSS3"],
            "Backend_EE":    ["Node.js", "Hibernate ORM", "RESTful Service Layers"],
            "Cloud_Data":    ["PostgreSQL (Supabase Relational Engines)", "MySQL Cluster"],
            "AI_Automation": ["n8n Workflow Orchestration", "Ollama (Device-Native LLMs)", "VPS Architecture Tuning"]
        }

    @property
    def core_philosophy(self) -> str:
        return "Compounding enterprise scale by offloading infrastructure maintenance to intelligent autonomous agents."

# Activating Profile Ecosystem
savindu = TechEntrepreneur()
