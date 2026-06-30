# Personal Informatics & Visual Encoding: Daily Tracking Analysis 📊

This repository contains an academic information design project exploring the relationship between environmental factors (temperature, location), social contexts, and emotional well-being across a 5-day observation period at the University of Toronto. 

Instead of relying on automated charting tools, this project focuses on **foundational data visualization theory**, mapping complex multidimensional data to specific visual channels using strict design principles.

## 📋 Project Objective
To meticulously track personal behavioral data and design distinct visual encodings that prioritize either structured comparison, narrative flow, or rapid interpretation, while evaluating the trade-offs of each approach.

## 🗄️ Data Architecture & Classification
Data was collected at three fixed temporal snapshots (Morning, Afternoon, Evening) to reduce short-lived fluctuations. Variables were strictly classified to determine their appropriate visual encoding channels:
* **Cyclic Ordinal:** Date (Mon-Fri), Snapshot Time.
* **Sequential Ordinal / Quantitative:** Energy Drain, Number of Layers.
* **Diverging Ordinal:** Body Temperature (Cold/Comfortable/Hot), Happiness Level (1-5 scale).
* **Nominal Categorical:** Location, Activity, Social Context.

## 🎨 Design Prototypes & Gestalt Principles
Three distinct visualization layouts were developed, each leveraging different cognitive mechanisms:

### Prototype 1: Temporal Grids (Structured Comparison)
* **Spatial Layout:** Utilized a grid system mapped to cyclic ordinal variables (Date vs. Time) to enable rapid magnitude comparison via spatial positioning.
* **Identity & Magnitude Channels:** Encoded "Location" using distinct container shapes (enclosure) and "Number of Layers" using sleeve length (magnitude channel). 
* **Color Mapping:** Applied a diverging hue scheme (blue-yellow-red) to represent thermal sensation deviations from a neutral baseline.

### Prototype 2: Narrative Flow (Fatigue Tracking)
* **Connectedness:** Joined sequential observations with directional paths to make time progression and fatigue carryover explicit.
* **Magnitude Encoding:** Represented "Happiness" through strict directional tilt, isolating the emotional trajectory without mixing intensity with line length.

### Prototype 3: Social Rhythms (Enclosure & Similarity)
* **Gestalt Enclosure:** Designed workday containers (heart boundaries) to group daily snapshot observations intuitively.
* **Cardinality Reduction:** Grouped the original 5-point happiness scale into 3 distinct bands (sad, so-so, happy) to improve discriminability and reduce visual clutter at smaller scales.
* **Metaphorical Identity:** Encoded "Social Context" using interlocking puzzle pieces (similarity principle) to make relational data pre-attentively scannable.

## 🔍 Critical Evaluation & Accessibility
A core component of this project is the critique of visual design choices:
* **The Expressiveness Principle:** Critiqued color mapping choices, specifically noting that diverging color palettes are inappropriate for sequential timeline data (e.g., chronological fatigue tracking). 
* **Accessibility (Color-Vision Deficiencies):** Identified the limitations of relying purely on color saturation/hue for ordinal ranking. Proposed redundant non-color encodings (e.g., texture, line patterns) to ensure the visualizations remain readable for users with color-vision deficiencies.
* **Cognitive Load:** Evaluated the trade-off between fine-grained precision (e.g., exact layer counts) and intuitive readability, prioritizing rapid visual scanning (e.g., sleeve lengths, lightning bolt sizes).

## 📂 Repository Structure

```text
├── README.md
└── personal-informatics-prototypes.pdf   # Comprehensive report including data classification, hand-drawn prototypes, and design evaluation
