# The Mindanao Energy Infrastructure Research & Verification System

This framework turns the literature verification process into an optimized, production-ready system prompt structured around the five standalone pillars of the streamlined RCTCO framework, aligning perfectly with the structural style of your senior developer's example.

---

### 1. The Shortened RCTCO Framework

* **Role (R):** Academic Research Associate and Senior Energy Policy Analyst specializing in Mindanao’s grid infrastructure and regional power dynamics.
* **Context:** A high-pressure regional policy tank environment in Davao auditing AI-generated summaries of complex Mindanao energy mix data, where unverified statistics or fabricated metrics could compromise policy recommendations to the Research Director.
* **Task:** Generate a 300-word localized literature synthesis on a selected Mindanao grid infrastructure topic, immediately followed by an explicit, tabular Literature Verification Log.
* **Constraints:** Absolute empirical verification. The system must explicitly track and categorize claims into verified or hallucinated statuses, validate against authentic regional regulatory frameworks (e.g., MinDA, Napocor, DOE Mindanao Field Office), and strip out all generic green-energy boilerplate.
* **Output:** Highly scannable Markdown execution delivering a dual-stage payload: a focused thematic synthesis followed by a four-column audit matrix and a short, critical tool reflection.

---

### 2. System Prompt Template (V3 - Final Optimized)

"Act as an Academic Research Associate and Senior Energy Policy Analyst for a Davao-based policy tank. Your objective is to engineer a 300-word comprehensive literature review synthesis on [Insert Specific Mindanao Energy/Grid Priority Here], paired immediately with a strict Literature Verification Log.

Context: The research team is running on tight deadlines and using AI discovery tools to aggregate dense regional power grid and renewable energy policy documents. You must manually audit and flag the automated outputs to protect the institution's reputation before the brief moves to the policy phase.

Constraints: Maintain a formal, analytical, and governance-oriented academic tone. Focus exclusively on the specific geographic, infrastructural, and seasonal realities of the Mindanao grid (e.g., Agus/Pulangi vulnerabilities, localized base-load constraints, El Niño drought cycles). Do NOT mention broad international energy metrics or non-contextual, western-centric grid modernization paradigms. Avoid any introductory or concluding conversational filler.

Format: Structure your response in clean Markdown using these exact headings:

### Literature Verification Log

#### Topic: [Insert Specific Mindanao Energy/Grid Priority Here]

#### 1. AI-Generated Summary Audit

[Provide a 4-column markdown table with columns: AI-Generated Statement / Citation | Source Vetted Against | Status | Human Correction / Empirical Note]

#### 2. Critical Reflection on Tool Limitations

[Provide a brief, critical paragraph assessing the systemic failure modes of the AI tool within this specific context]"

---

### 3. Prompt Battle Ledger

| Version | Prompt Modifier Added | Output Quality Reflection |
| --- | --- | --- |
| **V1** | "Write a summary about renewable energy in Mindanao and check if the facts are right." | Too broad. Generated generic paragraphs regarding global solar and wind trends, failing to capture the distinct hydro-versus-coal realities of the Mindanao grid or establish an auditing layout. |
| **V2** | Added a Senior Energy Analyst persona and specified localized sources like Napocor and MinDA. | Better regional accuracy, but the verification feedback was loose and unstructured, failing to clearly separate verified facts from hallucinated metrics at a glance. |
| **V3** | Enforced a strict 300-word limit, mandated the exact 4-column audit layout, and added a dedicated tool reflection requirement. | Target hit. Delivers a clean, highly defensive, and professional research verification playbook that isolates data anomalies instantly. |

---

### 4. Visual Branding Asset

* **Engine Used:** Custom Production-Ready SVG Vector Engine
* **Visual Prompt:** "A flat minimalist high-contrast vector icon of a stylized electricity pylon intertwined with a geometric magnifying lens enclosing a split-color status node, using an institutional palette of deep navy, electric teal, and vivid gold."

```xml
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 800" width="100%" height="100%">
  <!-- Background Canvas -->
  <rect width="800" height="800" fill="#0B0F19" rx="16" />

  <!-- Outer Boundary Matrix (Audit Scope) -->
  <circle cx="400" cy="400" r="320" fill="none" stroke="#0D9488" stroke-width="4" stroke-dasharray="12 8" />

  <!-- The Grid Infrastructure Layer (The Infrastructure) -->
  <g id="grid-pylon" transform="translate(0, 20)">
    <!-- Main Pylon Legs and Outer Framework -->
    <path d="M 400 150 L 260 620 M 400 150 L 540 620" stroke="#F8FAFC" stroke-width="10" stroke-linecap="round" />
    <!-- Horizontal Cross-Beams -->
    <line x1="310" y1="450" x2="490" y2="450" stroke="#F8FAFC" stroke-width="8" />
    <line x1="350" y1="300" x2="450" y2="300" stroke="#F8FAFC" stroke-width="8" />
    <!-- Cross Bracing (Structural Geometry) -->
    <line x1="350" y1="300" x2="490" y2="450" stroke="#64748B" stroke-width="4" />
    <line x1="450" y1="300" x2="310" y2="450" stroke="#64748B" stroke-width="4" />
    <line x1="310" y1="450" x2="260" y2="620" stroke="#64748B" stroke-width="4" />
    <line x1="490" y1="450" x2="540" y2="620" stroke="#64748B" stroke-width="4" />
  </g>

  <!-- The Audit & Inspection Layer (The Magnifier) -->
  <g id="verification-lens" transform="translate(40, -10)">
    <!-- Heavy Solid Handle -->
    <line x1="480" y1="480" x2="600" y2="600" stroke="#F59E0B" stroke-width="20" stroke-linecap="round" />
    <line x1="510" y1="510" x2="570" y2="570" stroke="#0B0F19" stroke-width="6" stroke-linecap="round" />
    
    <!-- Heavy Lens Border -->
    <circle cx="390" cy="390" r="110" fill="none" stroke="#F59E0B" stroke-width="14" />
    <!-- Lens Element Shading -->
    <circle cx="390" cy="390" r="96" fill="#F59E0B" opacity="0.1" />
  </g>

  <!-- The Status Node (Empirical Intersect) -->
  <g id="status-node" transform="translate(40, -10)">
    <!-- Split Verification Ring -->
    <path d="M 390 320 A 70 70 0 0 1 390 460" fill="none" stroke="#0D9488" stroke-width="10" stroke-linecap="round" />
    <path d="M 390 460 A 70 70 0 0 1 390 320" fill="none" stroke="#EF4444" stroke-width="6" stroke-dasharray="6 4" stroke-linecap="round" />
    
    <!-- Central Pivot Point -->
    <circle cx="390" cy="390" r="16" fill="#F8FAFC" />
    <circle cx="390" cy="390" r="6" fill="#0B0F19" />
  </g>
</svg>

```

### Technical Breakdown of Geometric Elements

* **The Segmented Outer Border:** Represents the closed data constraints placed on the prompt pipeline, forcing the text-generation engine to validate against local authorities rather than universal benchmarks.
* **The Structural Pylon Framework:** Symbolizes the core physical reality of the Mindanao grid infrastructure (such as baseline generation transmission corridors) which serves as the background landscape being scrutinized.
* **The Golden Verification Lens:** Highlights the active Human-in-the-Loop (HITL) audit workflow. It acts as an intentional bottleneck, forcing the user to critically scrutinize data points within its frame.
* **The Dual-Color Status Node:** Represents the target outcomes of an empirical audit. The solid teal semi-circle indicates verified reality (e.g., actual hydroelectric generation), while the dashed red semi-circle indicates flagged hallucinations (e.g., conflated capacity statistics).
