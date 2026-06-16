# System Prompt Engineering: The Mindanao Regional Data Cleansing & Visualization Pipeline

This framework converts the raw data aggregation and visualization workflow into an optimized, production-ready system prompt structured around the five standalone pillars of the streamlined RCTCO framework.

---

### 1. The Shortened RCTCO Framework

* **Role (R):** Senior Data Analyst and Regional Development Council (RDC) Environmental Systems Architect.
* **Context:** An emergency provincial legislative session requiring immediate budgetary allocations based on a chaotic, uncleaned regional CSV dataset (e.g., municipal solid waste generation trends across varying *puroks* or critical crop yield disruptions).
* **Task:** Execute a comprehensive data-cleansing sequence on an unorganized regional development dataset, generate exactly two high-contrast visual trend charts, and author a highly localized socio-environmental interpretive caption.
* **Constraints:** Absolute structural precision. The system must explicitly document structural corrections (e.g., handling null values in local reporting, adjusting skewed municipal metrics), enforce high-contrast styling tailored for immediate policy decisions, and bar all generic, non-contextual data-science boilerplate.
* **Output:** Highly scannable Markdown execution delivering an Automated Visual Data Report featuring: a structural adjustment summary log, two SVG-based high-contrast visual charts, and a localized explanatory narrative.

---

### 2. System Prompt Template (V3 - Final Optimized)

"Act as a Senior Data Analyst and RDC Environmental Systems Architect. Your objective is to ingest, structurally sanitize, and visualize an unorganized development dataset into a 300-word Automated Visual Data Report for an emergency LGU budgetary session.

Context: Your department has received a corrupted, unorganized CSV file tracking [Insert Specific Mindanao Development Dataset, e.g., Municipal Solid Waste Generation and Collection Deficits across Davao Region Localities]. You must clean the database and produce visual policy assets within a strict deadline to guide localized infrastructure funding.

Constraints: Maintain an authoritative, precise, and governance-oriented data tone. Focus exclusively on localized regional constraints (e.g., data gaps from low-bandwidth barangay reporting, missing infrastructure fields, seasonal agricultural or weather anomalies unique to Mindanao). Do NOT output generic data-science introductory pleasantries, placeholders, or broad macroeconomic boilerplate.

Format: Structure your response in clean Markdown using these exact headings:
## Execution
# AUTOMATED VISUAL DATA REPORT: [Insert Project Title Here]

## I. DATABASE STRUCTURAL ADJUSTMENT SUMMARY

[Provide a 3-column markdown table mapping: (1) Data Corruption Identified, (2) Structural Adjustment / Cleaning Vector, and (3) Policy Implication]

## II. HIGH-CONTRAST POLICY VISUALIZATIONS

[Generate exactly two production-ready, clean SVG code blocks representing the target data trends, utilizing an institutional color palette of deep charcoal, vivid gold, and electric teal]

## III. SOCIO-ENVIRONMENTAL POLICY NARRATIVE

[Provide a concise human-authored analytical caption linking the visual data directly to localized infrastructure realities, using terms like Purok, Barangay, and MDRRMO]"

---

### 3. Prompt Battle Ledger

| Version | Prompt Modifier Added | Output Quality Reflection |
| --- | --- | --- |
| **V1** | "Clean up a messy CSV data file about Mindanao and draw a couple of charts showing the main trends." | Too broad. Generated generic Python snippet scripts and boilerplate charts without mapping specific structural anomalies or anchoring data to LGU governance needs. |
| **V2** | Added an RDC Systems Architect persona and requested a table detailing the structural adjustments. | Improved data auditing, but the resulting visualizations were described narratively rather than rendered as concrete, production-ready, high-contrast visual code blocks. |
| **V3** | Mandated exactly two high-contrast SVG code blocks, forced local administrative variables, and stripped out all conversational data-science fluff. | Target hit. Delivers a highly defensive, production-ready automation framework that transforms messy data into structured policy-ready visualizations instantly. |

---

### 4. Visual Branding Asset

* **Engine Used:** Custom Production-Ready SVG Vector Engine
* **Visual Prompt:** "A flat minimalist high-contrast vector icon of an ascending data-trend bar chart intersecting a sharp, geometric data cleaning broom line under an analytical policy grid, using an institutional palette of deep slate, vibrant gold, and crisp governance white."

```xml
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 800" width="100%" height="100%">
  <!-- Background Canvas -->
  <rect width="800" height="800" fill="#0F172A" rx="16" />

  <!-- Technical Analytical Grid Lines (Policy Layer) -->
  <line x1="150" y1="200" x2="650" y2="200" stroke="#334155" stroke-width="2" stroke-dasharray="4 4" />
  <line x1="150" y1="350" x2="650" y2="350" stroke="#334155" stroke-width="2" stroke-dasharray="4 4" />
  <line x1="150" y1="500" x2="650" y2="500" stroke="#334155" stroke-width="2" stroke-dasharray="4 4" />

  <!-- Clean Database Foundations (X and Y Axis) -->
  <line x1="150" y1="150" x2="150" y2="600" stroke="#F8FAFC" stroke-width="6" stroke-linecap="round" />
  <line x1="150" y1="600" x2="650" y2="600" stroke="#F8FAFC" stroke-width="6" stroke-linecap="round" />

  <!-- High-Contrast Visual Trend Charts (The Trend Bars) -->
  <g id="data-bars">
    <!-- Baseline Trend Bar (e.g., Initial Unvetted/Corrupted Flow) -->
    <rect x="200" y="420" width="60" height="180" fill="#0D9488" opacity="0.4" rx="4" />
    <!-- Medium Growth Trend Bar -->
    <rect x="320" y="300" width="60" height="300" fill="#0D9488" rx="4" />
    <!-- Peak Budget Allocation Target Bar -->
    <rect x="440" y="180" width="60" height="420" fill="#0D9488" rx="4" />
  </g>

  <!-- The Ascending Core Trend Line -->
  <path d="M 230 420 L 350 300 L 470 180" fill="none" stroke="#F59E0B" stroke-width="8" stroke-linecap="round" stroke-linejoin="round" />
  <circle cx="470" cy="180" r="12" fill="#F8FAFC" stroke="#F59E0B" stroke-width="4" />

  <!-- Data Cleansing & Extraction Vector (The Clean Sweep Line) -->
  <g id="cleansing-vector">
    <!-- Diagonal Processing Angle -->
    <line x1="120" y1="550" x2="580" y2="200" stroke="#F59E0B" stroke-width="4" stroke-dasharray="16 10" stroke-linecap="round" />
    <!-- Dynamic Clean Nodes -->
    <circle cx="280" cy="425" r="8" fill="#F8FAFC" />
    <circle cx="420" cy="320" r="6" fill="#F8FAFC" />
  </g>

  <!-- Data Validation Anchor Nodes -->
  <rect x="142" y="585" width="16" height="30" fill="#F59E0B" rx="2" />
  <rect x="142" y="435" width="16" height="30" fill="#F59E0B" rx="2" />
  <rect x="142" y="285" width="16" height="30" fill="#F59E0B" rx="2" />
</svg>

```
### Technical Breakdown of Geometric Elements

* **The Muted Background Grid Lines:** Symbolize the legislative planning criteria and budgetary limits within which the regional dataset must be forced to align.
* **The Solid Axis Lines and Vertical Trend Bars:** Represent the stabilized, structurally sound data database after purging corrupted inputs, allowing decision-makers to assess values instantly.
* **The Golden Ascending Trend Line:** Illustrates the optimized policy insight extracted from the raw data, peaking at a clear target vector to prompt rapid budgetary resource mobilization.
* **The Intersecting Diagonal Clean Sweep Line:** Represents the programmatic and manual AI data cleaning filter, sweeping across raw data planes to remove null data gaps and isolate reliable metrics.

# AUTOMATED VISUAL DATA REPORT: Davao Region Municipal Solid Waste (MSW) Logistics & Volume Deviations

## I. DATABASE STRUCTURAL ADJUSTMENT SUMMARY

The raw, unorganized CSV dataset submitted to the Regional Development Council contained multiple structural corruptions, non-standard unit entries, and missing administrative identifiers stemming from low-bandwidth reporting across isolated *puroks*. The database was processed and sanitized using the following structural adjustment sequence:

| Data Corruption Identified | Structural Adjustment / Cleaning Vector | Policy Implication |
| --- | --- | --- |
| **Mismatched Volumetric Metrics:** Waste weights randomly logged in kilograms, metric tons, and localized "dump truck loads." | Standardized all collection values to metric tons ($MT$) using a programmatic conversion vector. | Prevents severe resource allocation errors based on inflated or deflated volume calculations. |
| **Missing Administrative Fields:** 23% of entries lacked explicit *Barangay* or *Purok* designations, showing only coordinate strings. | Geocoded missing entries against the official LGU geographic reference frame to re-assign exact political boundaries. | Restores granular jurisdictional accountability for localized waste collection strategies. |
| **Null Temporal Points:** Corrupted date/time strings during peak rainy seasons due to intermittent terminal power drops. | Imputed chronological sequences using the nearest active log from corresponding Municipal Disaster Risk Reduction and Management Office (MDRRMO) logs. | Enables accurate cross-referencing between seasonal weather anomalies and public utility performance dips. |

---

## II. HIGH-CONTRAST POLICY VISUALIZATIONS

The two SVG-based visualizations below represent the cleaned data trends. They utilize a high-contrast, professional palette designed for immediate clarity during emergency legislative budgeting sessions.

### Chart 1: Daily Waste Generation vs. Collection Deficits by District

```xml
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 450" width="100%" height="100%">
  <rect width="800" height="450" fill="#1E293B" rx="8" />
  
  <line x1="100" y1="350" x2="720" y2="350" stroke="#475569" stroke-width="2" />
  <line x1="100" y1="260" x2="720" y2="260" stroke="#334155" stroke-width="1" stroke-dasharray="4 4" />
  <line x1="100" y1="170" x2="720" y2="170" stroke="#334155" stroke-width="1" stroke-dasharray="4 4" />
  <line x1="100" y1="80" x2="720" y2="80" stroke="#334155" stroke-width="1" stroke-dasharray="4 4" />

  <text x="50" y="85" fill="#94A3B8" font-family="sans-serif" font-size="12" font-weight="bold">150 MT</text>
  <text x="50" y="175" fill="#94A3B8" font-family="sans-serif" font-size="12" font-weight="bold">100 MT</text>
  <text x="50" y="265" fill="#94A3B8" font-family="sans-serif" font-size="12" font-weight="bold">50 MT</text>
  <text x="50" y="355" fill="#94A3B8" font-family="sans-serif" font-size="12" font-weight="bold">0 MT</text>

  <text x="180" y="380" fill="#F8FAFC" font-family="sans-serif" font-size="14" font-weight="bold" text-anchor="middle">District 01</text>
  <text x="400" y="380" fill="#F8FAFC" font-family="sans-serif" font-size="14" font-weight="bold" text-anchor="middle">District 02</text>
  <text x="620" y="380" fill="#F8FAFC" font-family="sans-serif" font-size="14" font-weight="bold" text-anchor="middle">District 03</text>

  <rect x="120" y="140" width="50" height="210" fill="#0D9488" rx="4" />
  <rect x="175" y="180" width="50" height="170" fill="#F59E0B" rx="4" />

  <rect x="340" y="90" width="50" height="260" fill="#0D9488" rx="4" />
  <rect x="395" y="210" width="50" height="140" fill="#F59E0B" rx="4" />

  <rect x="560" y="190" width="50" height="160" fill="#0D9488" rx="4" />
  <rect x="615" y="210" width="50" height="140" fill="#F59E0B" rx="4" />

  <rect x="250" y="25" width="20" height="12" fill="#0D9488" rx="2" />
  <text x="280" y="36" fill="#F8FAFC" font-family="sans-serif" font-size="12">Total Generated Volume</text>
  
  <rect x="460" y="25" width="20" height="12" fill="#F59E0B" rx="2" />
  <text x="490" y="36" fill="#F8FAFC" font-family="sans-serif" font-size="12">Volume Successfully Collected</text>
</svg>

```

### Chart 2: Seasonal Waste Log Deviations (Amihan vs. Inter-Monsoon Peak)

```xml
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 450" width="100%" height="100%">
  <rect width="800" height="450" fill="#1E293B" rx="8" />

  <line x1="100" y1="350" x2="720" y2="350" stroke="#475569" stroke-width="2" />
  <line x1="100" y1="80" x2="100" y2="350" stroke="#475569" stroke-width="2" />
  
  <line x1="100" y1="215" x2="720" y2="215" stroke="#334155" stroke-width="1" stroke-dasharray="4 4" />
  <line x1="100" y1="80" x2="720" y2="80" stroke="#334155" stroke-width="1" stroke-dasharray="4 4" />

  <text x="150" y="380" fill="#94A3B8" font-family="sans-serif" font-size="12" text-anchor="middle">Jan</text>
  <text x="260" y="380" fill="#94A3B8" font-family="sans-serif" font-size="12" text-anchor="middle">Mar</text>
  <text x="370" y="380" fill="#94A3B8" font-family="sans-serif" font-size="12" text-anchor="middle">May</text>
  <text x="480" y="380" fill="#94A3B8" font-family="sans-serif" font-size="12" text-anchor="middle">Jul</text>
  <text x="590" y="380" fill="#94A3B8" font-family="sans-serif" font-size="12" text-anchor="middle">Sep</text>
  <text x="700" y="380" fill="#94A3B8" font-family="sans-serif" font-size="12" text-anchor="middle">Nov</text>

  <path d="M 150 280 Q 205 290 260 210 T 370 120 T 480 310 T 590 190 T 700 140" fill="none" stroke="#F59E0B" stroke-width="6" stroke-linecap="round" stroke-linejoin="round" />

  <circle cx="370" cy="120" r="10" fill="#F8FAFC" stroke="#0D9488" stroke-width="4" />
  <circle cx="480" cy="310" r="10" fill="#F8FAFC" stroke="#EF4444" stroke-width="4" />
  <circle cx="700" cy="140" r="10" fill="#F8FAFC" stroke="#0D9488" stroke-width="4" />

  <rect x="495" y="295" width="180" height="30" fill="#EF4444" fill-opacity="0.2" rx="4" />
  <text x="505" y="315" fill="#EF4444" font-family="sans-serif" font-size="11" font-weight="bold">Log Drop: Weather Disruption</text>
</svg>

```

---

## III. SOCIO-ENVIRONMENTAL POLICY NARRATIVE

The visual data models reveal a critical operational structural breakdown within District 02. While waste generation scales lineally during peak municipal trade cycles, the actual capacity for collection drops sharply, creating a compounding uncollected residue curve.

This specific 46% service delivery deficit is directly linked to localized logistical friction parameters: the central transit corridors connecting peripheral *puroks* to the primary sanitary landfill pass directly through river basins vulnerable to flash floods. When heavy rainfall anomalies occur, flooding cuts off physical access to collection vehicles.

Consequently, uncollected household solid waste accumulates within drainage infrastructures at the *barangay* level, multiplying municipal public health vectors and paralyzing localized secondary water channels.

To break this loop, the Regional Development Council must immediately divert emergency capital infrastructure allocations away from general urban maintenance and explicitly lock those funds into constructing elevated municipal transition stations and reinforced bypass networks. This strategic pivot ensures continuous operational access for collection vehicles, successfully protecting both community health assets and vital regional environments.
