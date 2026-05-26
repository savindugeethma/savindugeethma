<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=111827&height=220&section=header&text=SAVINDU%20GEETHMA&fontSize=42&fontColor=ffffff&fontAlignY=45&animation=twinkling" width="100%" />
  
  <p align="center">
    <strong>Full Stack Engineer • AI Automation Architect • Founder & Tech Entrepreneur</strong>
  </p>

  <p align="center">
    <img src="https://img.shields.io/github/followers/savindugeethma?label=Followers&style=fast&color=22c55e&labelColor=1f2937" alt="Followers">
    <img src="https://img.shields.io/github/stars/savindugeethma?style=fast&color=eab308&labelColor=1f2937" alt="Stars">
  </p>
</div>

---

### 🔮 Executive Overview

A forward-thinking Software Engineering undergraduate blending deep technical capability with brand strategy and enterprise automation. Specializing in architecting continuous integration loops, production-grade AI agent frameworks, and self-sustaining automated digital business ecosystems.

```python
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
