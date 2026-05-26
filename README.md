from typing import List, Dict, Union

class TechEntrepreneur:
    """
    Synthesizing Academic Rigor, Advanced Automation, and Luxury Brand Execution.
    """
    def __init__(self) -> None:
        self.identity: str = "Savindu Geethma"
        self.academic: str = "BSc (Hons) Software Engineering (L2) — University of Birmingham City (UK)"
        
        self.ventures: Dict[str, str] = {
            "Dropti": "Founder & Owner — Autonomous Startup Ecosystem",
            "Zeylona": "Brand Handler — AI-Driven Luxury Tea & Botanical Spices",
            "Dropti Ceylon Plantations": "Director — Premium Agro-Export Business"
        }

    def get_technology_matrix(self) -> Dict[str, List[str]]:
        return {
            "Languages":   ["TypeScript", "JavaScript (ES6+)", "Python", "Java", "PHP"],
            "Frontend":    ["Next.js (App Router)", "React", "Tailwind CSS", "Bootstrap", "HTML5/CSS3"],
            "Backend_EE":  ["Node.js", "Hibernate ORM", "RESTful APIs"],
            "Databases":   ["PostgreSQL (Supabase Engine)", "MySQL Cluster"],
            "Automation":  ["n8n Workflow Orchestration", "Ollama (Device-Native LLMs)", "VPS Architecture Tuning"]
        }

    @property
    def core_philosophy(self) -> str:
        return "Compounding enterprise scale by offloading maintenance to intelligent autonomous machines."
