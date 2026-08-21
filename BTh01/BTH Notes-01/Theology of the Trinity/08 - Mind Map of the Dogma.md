---
title: Mind Map of the Dogma (Mermaid)
tags: [BTh, theology/trinity, mind-map, diagram]
type: course-note
source: "The Oxford Handbook of the Trinity (NotebookLM)"
created: 2026-07-25
up: "[[Theology of the Trinity - Course Home]]"
---

# 08 — Mind Map of the Dogma

> [!info] Home: [[Theology of the Trinity - Course Home]] · reads with [[03 - Systematic Concepts and Terminology]]
> Mermaid renders live in Obsidian reading/live-preview mode.

## 1. The structure of the dogma
```mermaid
flowchart TD
    God["ONE GOD<br/>one divine essence — ousia"]:::core
    God --> F["FATHER<br/>unbegotten / source"]:::person
    God --> S["SON<br/>begotten"]:::person
    God --> H["HOLY SPIRIT<br/>proceeding"]:::person

    F -- "generation (intellect → Word)" --> S
    F -- "spiration (will → Love)" --> H
    S -. "Filioque — West only" .-> H

    F -. "perichoresis" .- S
    S -. "perichoresis" .- H
    H -. "perichoresis" .- F

    F --> R["Distinguished ONLY by<br/>relations of origin"]:::note
    S --> R
    H --> R

    classDef core fill:#4c1d95,stroke:#ddd,color:#fff;
    classDef person fill:#1e3a8a,stroke:#ddd,color:#fff;
    classDef note fill:#374151,stroke:#ddd,color:#fff;
```

## 2. Topic overview (mindmap)
```mermaid
mindmap
  root((TRINITY))
    Biblical
      Shema Deut 6:4
      Prov 8 Wisdom
      Matt 28:19
      John 1:1
    Councils
      Nicaea 325 homoousios
      Constantinople 381 Spirit
    Concepts
      ousia / hypostasis
      processions
      relations of origin
      perichoresis
      appropriation
      Filioque
    Heresies
      Arianism
      Modalism
      Subordinationism
      Tritheism
    Modern
      Barth revelation
      Rahner Rule
      Social Trinity
      Trinity as social program
```

## 3. Councils & heresies map
```mermaid
flowchart LR
    A["Arius: Son a creature"] -->|condemned| N["NICAEA 325<br/>homoousios"]
    N --> Ath["Athanasius defends"]
    Ath --> Capp["Cappadocians<br/>ousia vs hypostasis"]
    P["Pneumatomachi:<br/>Spirit not God"] -->|condemned| C381["CONSTANTINOPLE 381<br/>Spirit is Lord & Giver of life"]
    Capp --> C381
    M["Modalism"]:::her -.rejected.-> N
    T["Tritheism"]:::her -.rejected.-> Capp
    classDef her fill:#7f1d1d,stroke:#ddd,color:#fff;
```

> [!tip] Study use
> Diagram 1 = **what the dogma says**. Diagram 2 = **whole-topic recall net**. Diagram 3 = **how history got there**. Reproduce Diagram 1 from memory before an exam.
