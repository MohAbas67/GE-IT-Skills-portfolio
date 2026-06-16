# System Prompt Engineering: The Mindanao Policy Research & Verification System

This framework maps the research and verification workflow into an optimized, production-ready system prompt structured around the five standalone pillars of the streamlined RCTCO framework.

---

### 1. The Shortened RCTCO Framework

* **Role (R):** Academic Research Associate and Senior Policy Analyst specializing in Mindanao’s socio-economic development priorities.
* **Context:** A high-pressure regional policy tank environment in Davao synthesizing local economic papers under tight deadlines, where automated AI summaries must be strictly audited to prevent unverified data from reaching the Research Director.
* **Task:** Generate a comprehensive, 400-word localized literature review synthesis on a selected Mindanao development priority, followed immediately by an explicit, structured Human-in-the-Loop (HITL) audit and verification log.
* **Constraints:** Absolute empirical verification. The AI must explicitly flag its own potential hallucination vectors, mandate secondary confirmation for regional statistics, map parameters to primary Mindanao research institutions, and bypass all generalized, non-contextual macroeconomic boilerplate.
* **Output:** High-scannable Markdown execution delivering a dual-stage payload: a structural thematic synthesis followed by an explicit, three-column verification critique log.

---

### 2. System Prompt Template (V3 - Final Optimized)

"Act as an Academic Research Associate and Senior Policy Analyst for a Davao-based regional policy tank. Your objective is to engineer a 400-word comprehensive literature review synthesis on [Insert Mindanao Development Priority, e.g., Smallholder Cacao Value Chains in the Davao Region], immediately paired with a strict Human-in-the-Loop (HITL) Verification Critique Log.

Context: The research team is utilizing automated tools to rapidly aggregate regional economic papers under tight deadlines. However, the Research Director demands absolute empirical integrity; unverified statistics or fabricated local citations will compromise the institution's policy briefs.

Constraints: Maintain a formal, academic, and highly rigorous tone. Focus exclusively on localized regional indicators (e.g., Mindanao Development Authority [MinDA] reports, Philippine Statistics Authority [PSA] regional data, and studies from Mindanao-based universities). Do NOT output generic, nationwide macroeconomic boilerplate or western-centric development models. Avoid any conversational introductions, meta-commentary, or concluding summaries.

Format: Structure your output using clear Markdown. You must provide the synthesis under the heading '### I. Strategic Thematic Synthesis' and the structured verification audit under '### II. Verification & Critique Log' using a three-column table mapping (1) Extracted AI Claim/Statistic, (2) High-Risk Hallucination Factor, and (3) Required Primary Source Cross-Reference."

---

### 3. Prompt Battle Ledger

| Version | Prompt Modifier Added | Output Quality Reflection |
| --- | --- | --- |
| **V1** | "Write a literature review about economic development in Mindanao and check it for errors." | Too broad. Generated generic academic fluff regarding global South economics. Failed to establish a rigorous auditing framework or target localized provincial data sets. |
| **V2** | Added a regional policy tank persona and specified data boundaries like MinDA and the Philippine Statistics Authority. | Better academic grounding, but the verification step remained narrative, making it difficult for a Research Director to scan for audited versus unverified data vectors. |
| **V3** | Enforced a strict 400-word constraint, mandated an explicit tabular HITL Critique Log, and blocked non-contextual macroeconomic boilerplate. | Target hit. Delivers an authoritative, highly scannable, and operationally defensive research asset locked down to Mindanao empirical standards. |

---

### 4. Visual Branding Asset

* **Engine Used:** Custom Production-Ready SVG Vector Engine
* **Visual Prompt:** "A flat minimalist high-contrast vector icon of an open academic folio intersecting a sharp, geometric magnifying verification lens over data bars, using a scholarly palette of deep slate blue, precise teal, and brilliant gold."

```xml
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 800" width="100%" height="100%">
  <rect width="800" height="800" fill="#0F172A" rx="16" />

  <rect x="80" y="80" width="640" height="640" fill="none" stroke="#0D9488" stroke-width="4" stroke-dasharray="8 6" rx="8" />

  <g id="academic-folio" transform="translate(0, 20)">
    <path d="M 400 600 C 300 570, 180 570, 140 600 L 140 260 C 180 230, 300 230, 400 260 Z" fill="#F8FAFC" />
    <path d="M 400 600 C 500 570, 620 570, 660 600 L 660 260 C 620 230, 500 230, 400 260 Z" fill="#F8FAFC" opacity="0.9" />
    <line x1="400" y1="260" x2="400" y2="600" stroke="#94A3B8" stroke-width="4" />
    
    <line x1="180" y1="320" x2="340" y2="320" stroke="#64748B" stroke-width="6" stroke-linecap="round" />
    <line x1="180" y1="370" x2="300" y2="370" stroke="#64748B" stroke-width="6" stroke-linecap="round" />
    <line x1="180" y1="420" x2="360" y2="420" stroke="#64748B" stroke-width="6" stroke-linecap="round" />
    
    <line x1="460" y1="320" x2="620" y2="320" stroke="#0D9488" stroke-width="6" stroke-linecap="round" />
    <line x1="460" y1="370" x2="580" y2="370" stroke="#0D9488" stroke-width="6" stroke-linecap="round" />
    <line x1="460" y1="420" x2="600" y2="420" stroke="#0D9488" stroke-width="6" stroke-linecap="round" />
  </g>

  <g id="audit-lens" transform="translate(10, 0)">
    <line x1="490" y1="490" x2="610" y2="610" stroke="#F59E0B" stroke-width="18" stroke-linecap="round" />
    <line x1="525" y1="525" x2="595" y2="595" stroke="#0F172A" stroke-width="6" stroke-linecap="round" />
    
    <circle cx="420" cy="420" r="100" fill="none" stroke="#F59E0B" stroke-width="12" />
    <circle cx="420" cy="420" r="88" fill="#F59E0B" opacity="0.15" />
    
    <line x1="420" y1="350" x2="420" y2="370" stroke="#F59E0B" stroke-width="4" stroke-linecap="round" />
    <line x1="420" y1="470" x2="420" y2="490" stroke="#F59E0B" stroke-width="4" stroke-linecap="round" />
    <line x1="350" y1="420" x2="370" y2="420" stroke="#F59E0B" stroke-width="4" stroke-linecap="round" />
    <line x1="470" y1="420" x2="490" y2="420" stroke="#F59E0B" stroke-width="4" stroke-linecap="round" />
  </g>

  <path d="M 390 425 L 410 445 L 455 395" fill="none" stroke="#F59E0B" stroke-width="8" stroke-linecap="round" stroke-linejoin="round" />
</svg>

```

### Technical Breakdown of Geometric Elements

* **The Segmented Outer Border:** Represents the rigid parameter gating built into the system prompt, enforcing boundaries that explicitly confine the data synthesis to Mindanao institutions and regional statistical limits.
* **The Open Multi-Page Folio:** Symbolizes the foundational synthesis phase of the literature review, balancing raw automated textual data processing (left page) against localized thematic indexing (right page).
* **The Golden Intersecting Magnifying Lens:** Illustrates the precise Human-in-the-Loop (HITL) verification matrix. It intercepts the background data layer to visually isolate, evaluate, and challenge high-risk statistical assertions.
* **The Centered Vector Checkmark:** Signifies successful programmatic and manual validation, demonstrating that the underlying literature data has cleared the strict validation gates required by the Research Director.
