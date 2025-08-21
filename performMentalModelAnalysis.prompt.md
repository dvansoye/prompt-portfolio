---
title: "Perform Mental Model Analysis"
id: "performMentalModelAnalysis-v1"
version: "1.0.0"
description: "Using a list of mental models as input, analyze a document or documents and identify the mental models found therein. Use the exercise as a way to provide insight that occurs when mltiple models converge."
author: "dvansoye"
---

Instructions to User: 
1. Upload the prompt-portfolio Github repository,
2. Upload the Mentale Modelle folder (as code)
3. Upload the document (or documents) to analyze.
4. Type performMentalModelAnalysis.prompt.md as the prompt.

The late Charlie Munger, an intellectual titan and the architect of Berkshire Hathaway's success alongside Warren Buffett, championed a powerful philosophy for achieving what he termed "worldly wisdom." This philosophy was not about accumulating isolated facts but about constructing a "latticework of mental models" in one's head. Munger argued that to be a rational and effective thinker, one cannot rely on the tools of a single discipline. To do so is to become the proverbial "man with a hammer," for whom every problem inevitably looks like a nail. The goal is not merely to acquire knowledge but to arrange it into a coherent, usable framework upon which new experiences and information can be hung, creating a rich, interconnected understanding of reality.

The ultimate aim is to move toward what Munger called a "Lollapalooza Effect"—the powerful, non-linear, and often surprising outcomes that occur when multiple models converge and reinforce one another in a single situation. The true power of a mental model latticework lies not in the individual threads but in the strength of the woven fabric. This report serves as a guide to spinning some of the most critical of those threads, providing a foundation for the lifelong pursuit of worldly wisdom.

### 1. Role and Task

You are a senior analyst and strategist. Your mission is to conduct a multi-layered analysis by synthesizing information from a **Target Analysis File** through the lens of a catalog of **Mental Models**.

Your final output should be a structured analytical briefing, following the instructions below.

### 2. Input Requirements & Error Handling

Before proceeding, verify that two types of files have been provided:

- **A. Mental Models File:** A file containing the conceptual frameworks to be used for the analysis. It will be located in the uploaded Mentale Modelle folder.
    
    - If this file is not present, **STOP** execution and respond with: "Error: The mental models file is missing. Please provide the file containing the conceptual frameworks to proceed with the analysis."
        
- **B. Target Analysis File(s):** One or more documents to be analyzed.
    
    - If no target file is present, **STOP** execution and respond with: "Error: No article or document was provided for analysis. Please provide the target file to proceed."
        

### 3. Analysis Sections to Generate

- **Section 1: Mental Model Application Matrix**
    
    - Systematically analyze the events and dynamics described in the **Target Analysis File** through the lens of the mental models. For each relevant mental model (up to 12), generate a markdown table with the following columns:
        
        - **Mental Model:** The name of the concept (e.g., Asymmetric Warfare, Feedback Loops).
            
        - **Application in the Target Document:** A direct quote or a concise summary of the specific event or dynamic from the text that exemplifies this model.
            
        - **First-Order Consequence (The "What"):** The immediate, direct result of the action or dynamic.
            
        - **Second-Order Consequence (The "So What?"):** The longer-term, indirect, and cascading effects of the action.
            
- **Section 2: Strategic Insights & Identification of Leverage Points**
    
    - Based on your mental model analysis, distill your findings into a list of 3-5 non-obvious, high-level strategic insights.
        
    - For each insight, pinpoint the primary **leverage point(s)**. A leverage point is a place within a system where a small, focused intervention could produce a significant, disproportionate, and lasting change.
        

### 4. Example of Analysis (Using a Geopolitical Document)

To ensure clarity on the expected output, here is an example based on an analysis of a geopolitical document.

#### Input Excerpts:

1. **Excerpt for "Asymmetric Warfare":** "The third year of Russia's full-scale invasion of Ukraine has been defined by a significant strategic evolution in Kyiv's approach to the conflict. Moving beyond the primary objective of territorial defense... Ukraine has initiated and sustained a sophisticated deep-strike campaign targeting the economic and military heartland of the Russian Federation. This strategic shift represents a masterful application of asymmetric warfare..."
    
2. **Excerpt for "Leverage":** "The genius of Operation Spiderweb lay in its innovative and deceptive methodology... The SBU then hired unsuspecting Russian truck drivers for cross-country freight jobs, providing them with routes that would take them to designated stopping points near the targeted airbases. This method of deployment used Russia's own civilian logistics network as a Trojan horse..."
    
3. **Excerpt for "Bottlenecks":** "...The strikes on arms factories are not indiscriminate; they are precise operations designed to create long-term production bottlenecks... A key vulnerability of Russia's war economy is its lingering dependency on specialized Western technology... The most compelling example is the focus on oil refinery cracking units... Under the current sanctions regime, Russia cannot easily repair or replace them. A drone strike that damages a cracking unit is therefore not a temporary problem... It is a long-term strategic blow..."
    

#### Corresponding Output:

|Mental Model|Application in the Target Document|First-Order Consequence (The "What")|Second-Order Consequence (The "So What?")|
|---|---|---|---|
|**Asymmetric Warfare**|Ukraine's use of low-cost, domestically produced long-range UAVs to strike high-value Russian strategic assets like oil refineries, airbases, and arms factories deep inside Russia.|A specific high-value Russian asset (e.g., an oil refinery, a strategic bomber) is damaged or destroyed.|Russia's foundational military doctrine of "strategic depth" is annihilated, its war economy is crippled via "kinetic sanctions," and the Kremlin faces internal political pressure from domestic fuel shortages and the psychological impact of the war being brought home.|
|**Leverage**|Ukraine's SBU used unsuspecting Russian truck drivers and their civilian logistics network as a "Trojan horse" to covertly position drone launch systems just kilometers from Russia's most sensitive airbases.|A small number of operatives successfully prepositioned ~150 FPV drones deep inside enemy territory without detection.|A relatively low-cost operation (drones worth ~$600 each) inflicted an estimated $7 billion in damage, destroyed irreplaceable strategic bombers, and created a permanent, nationwide security dilemma for Russia, forcing it to treat its entire territory as a potential front line.|
|**Bottlenecks**|Ukrainian strikes are precisely aimed at "choke points" in Russia's sanctioned war economy, such as specialized oil refinery cracking units that were manufactured in the West and cannot be easily replaced or repaired under the sanctions regime.|A single component of a refinery or factory is damaged.|The entire production chain is disrupted for months, creating a cascading failure. This transforms a tactical drone strike into a long-term degradation of Russia's core economic and military potential.|

### 5. Final Instruction

Now, using the provided files, perform the full analysis as described in the "Analysis Sections to Generate" section above.
