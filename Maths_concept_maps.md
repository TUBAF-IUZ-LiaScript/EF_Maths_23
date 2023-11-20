<!--
author:   Dr. Mark Jacob
email: mark.jacob@iuz.tu-freiberg.de
version:  0.0.1
language: en
narrator: UK English Female
comment: Content of week 3 WS 2023/2024
icon: https://upload.wikimedia.org/wikipedia/commons/thumb/e/e8/TUBAF_Logo.svg/800px-TUBAF_Logo.svg.png
script:   https://cdn.jsdelivr.net/npm/mermaid@10.5.0/dist/mermaid.min.js
import: https://raw.githubusercontent.com/liaScript/mermaid_template/master/README.md
-->

[![LiaScript](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?https://github.com/TUBAF-IUZ-LiaScript/EF_Maths_23/blob/main/Maths_concept_maps.md)

# Concept maps

## sample map

```mermaid @mermaid
flowchart TB
    classDef someclass fill:#f96;
    A[Concrete] --> B
    A:::someclass --> C
    C[Language] --> V[Words]
    C --> W[Interaction]
    V --> I[Etymology]
    I --> AD[com lat. = together]
    AD:::someclass --> AK
    I --> AE(cretus lat. = grown)
    AE:::someclass --> AK[grown together]
    AK:::someclass
    
    V --> J[Collocations]
    J --> I
    J --> reinforced:::someclass 
    P --> R[Processes]
    R --> AK
    R --> AP[Inputs & Outputs]
    W --> P[Describing]
    J --> P
    W --> Q[Discussing]
    Q --> AG[Argumentation]
    AG --> AP
    AP --> S[Presentations]
    AP --> AQ[Texts]
    AQ <--> AR[Concept maps]
    S --> AI
    S <--> AR
    
    B[Subject] --> D[Composition]
    D --> N[Aggregate]:::someclass 
    D --> O[Cement]:::someclass 
    B --> E[Production]
    E --> L[Mixing]:::someclass 
    E --> M[Curing]:::someclass 
    B --> F[Structure]
    F --> AA[Homogeneity]:::someclass 
    F --> AB[Porosity]:::someclass 
    B --> G[Properties]
    G --> X[high compressive strength]:::someclass 
    G --> Y[Water resistant]:::someclass 
    B --> H[Applications]
    H --> Z[Dams]:::someclass 
    H --> AC[Furnaces]:::someclass 
    D --> E
    E --> F
    F --> G
    G --> H
    B --> AH
    H --> AH[Impacts]
    AH --> AJ[Economic]:::someclass    
    AH --> AI[Environmental]:::someclass 
    X --> Z
    Y --> Z
```

## Concept map MW

```mermaid @mermaid
flowchart LR
    A{AI} -->|How does it work?| B(example: ChatGPT)
    B --> |type of AI|C(LLM, transformer)
    B --> D(statistical model) --> E(tries to predict next word in a sentence)
    D --> F(filtered and controlled by human rated 'usefulness')
    D --> |but| G(prone to 'halluncination') --> |i.e.| H(stating falsehoods as facts) --> I(no factchecking)
    A --> J(helpfulness in everyday situations) --> K(boring or repetitive tasks can be automated) --> |such as|L(writing e-mails)
    K --> |or|M(generating sounds)
    K --> |or|N(generating pictures)
    K --> |or|O(summarising texts/videos)
    A --> |already happens!|P(dangers) --> Q(people could build unhealthy attachments) --> R(would trust hallucinating AIs)
    P --> S(AI training and server maintaining is extremely energy-consuming) --> T(bad for the environment in general)
    P --> U(misinformation can be spread more easily)
    A --> V{CONSCIOUSNESS?} --> W(maybe, maybe not. Depends on your definition.)
    J --> |but also in science!|X(scientific breakthroughs, e.g.) --> Y(protein folding)
    X --> Z(better ways to produce energy / consume less)
    X --> |at least in theory, that is|AA(nuclear fusion)
```

## Concept map FK

```mermaid @mermaid
flowchart TD
    A[Mathematics] -->|need proof| B(theorems)
    B -->|hard to find a proof| C{unsing computers as 'proof checker'}
    C -->|60.000 lines of code for one proof|D[needs a lot of code for a proof]
    C -->|unsing AI like chat gpt| E[can write proofs but they are nonsense]
    C -->F[crucel for a better understanding of math]
    E --> |researchers|G[let AI generate formalised proof]
```
## Concept map YB

```mermaid @mermaid
flowchart TD
    A[giant lacewing]--> B(is an insect)
    
    A --> I(from the jurassic-era)
   A --> C( thought to be extinct across north america in 1800s) -->D(but were found in walmat)
    D --> F( finding it in a suburban area) -->G(demonstrates)
--> H[adaptability of the species]
I --> J(lived through)
J --> K(extinction of dinosaurs)
J --> L(industrial revolution)
L --> H
K --> H
  J --> M(and more)
  D --> N(for the first time in 50 years)
```