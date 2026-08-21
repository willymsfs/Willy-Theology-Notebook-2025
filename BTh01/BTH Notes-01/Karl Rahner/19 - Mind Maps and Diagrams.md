---
title: Mind Maps and Diagrams
tags: [BTh, theology/rahner, diagrams, revision]
type: course-note
created: 2026-08-05
up: "[[Karl Rahner - Course Home]]"
---

# 19 — Mind Maps and Diagrams

> [!info] Prev: [[18 - Rahner in the Indian Context]] · Next: [[20 - Flashcards]]

## 1. The whole system on one page

```mermaid
flowchart TD
  subgraph PHIL["PHILOSOPHICAL FOUNDATION"]
    A1["Spirit in World<br/>conversio ad phantasma"]
    A2["Vorgriff auf esse<br/>horizon of Being"]
    A3["Hearer of the Word<br/>obediential potency"]
    A1 --> A2 --> A3
  end

  subgraph METH["METHOD"]
    B1["Transcendental method<br/>conditions of possibility"]
    B2["Transcendental &lt;-&gt; Categorical"]
    B1 --- B2
  end

  subgraph ONT["ONTOLOGY OF SYMBOL"]
    C1["Being expresses itself<br/>to attain itself"]
    C2["Realsymbol vs Vertretungssymbol"]
    C1 --> C2
  end

  subgraph DOG["DOGMATIC APPLICATIONS"]
    D1["Trinity: Logos = symbol of Father<br/>+ Rahner's Rule"]
    D2["Christology: humanity = symbol of Logos"]
    D3["Church: Grundsakrament"]
    D4["Sacraments: significando causant"]
    D5["Body / Heart: symbol of the person"]
  end

  subgraph GRACE["GRACE"]
    E1["Supernatural existential"]
    E2["Self-communication<br/>quasi-formal causality"]
    E3["Anonymous Christianity"]
    E1 --> E2 --> E3
  end

  subgraph LIFE["SPIRITUALITY + CHURCH"]
    F1["Mystagogy"]
    F2["Diaspora Church"]
    F3["World Church: 3 epochs"]
  end

  A3 --> B1
  B1 --> C1
  B1 --> E1
  C1 --> D1 --> D2 --> D3 --> D4
  C1 --> D5
  E2 --> D2
  E3 --> F3
  E1 --> F1
  D3 --> F2
```

## 2. The symbol chain (the single most examinable diagram)

```mermaid
flowchart LR
  F["FATHER"] -->|"eternal utterance"| W["WORD"]
  W -->|"utterance ad extra"| H["HUMANITY OF JESUS"]
  H -->|"abiding in history"| C["CHURCH"]
  C -->|"self-realisation for the individual"| S["SACRAMENT"]
  S -->|"through matter and flesh"| B["BODY / HEART"]
  B --> P["THIS PERSON"]
```

**One law all the way down:** *a being attains itself by expressing itself in another.*

## 3. Nature and grace — the three positions

```mermaid
flowchart TD
  subgraph SCH["Baroque scholasticism"]
    S1["Pure nature:<br/>complete, natural end"] -.grace added from outside.-> S2["Supernatural order"]
    S3["Gratuity: SAFE<br/>Relevance: LOST (extrinsicism)"]
  end
  subgraph LUB["De Lubac"]
    L1["One nature with intrinsic<br/>natural desire for God"] --> L2["Vision of God"]
    L3["Relevance: SAFE<br/>Gratuity: AT RISK"]
  end
  subgraph RAH["Rahner"]
    R1["Nature (Restbegriff only)"] --> R2["+ Supernatural existential:<br/>universal AND unowed"]
    R2 --> R3["Both gratuity and relevance SAFE"]
  end
```

## 4. God's one self-communication, three modalities

```mermaid
flowchart TD
  X["ONE divine self-communication"]
  X --> G["GRACE<br/>offered to all; refusable"]
  X --> I["INCARNATION<br/>given to one absolutely, irrevocably"]
  X --> V["GLORY<br/>unveiled, face to face"]
  G -->|"accepted unthematically"| AC["Anonymous Christian"]
  G -->|"accepted explicitly"| EC["Explicit believer, Church, sacraments"]
  I --> CH["Chalcedon re-read:<br/>humanity as Realsymbol"]
```

## 5. Critique map — who attacks what

```mermaid
flowchart LR
  R(("RAHNER"))
  R --- P1["Vorgriff / method"]
  R --- P2["Anonymous Christianity"]
  R --- P3["Rahner's Rule"]
  R --- P4["Symbol ontology"]
  R --- P5["Sacraments"]
  R --- P6["Transcendental subject"]

  P1 --- C1["Gilson, Fabro:<br/>not Thomism"]
  P1 --- C2["Kant: no valid<br/>inference to God"]
  P1 --- C3["Marion:<br/>onto-theology"]
  P2 --- C4["Balthasar:<br/>blunts the Ernstfall"]
  P2 --- C5["Panikkar:<br/>anonymous Hindu?"]
  P2 --- C6["Lindbeck:<br/>experiential-expressivism"]
  P3 --- C7["Moltmann:<br/>modalism"]
  P3 --- C8["Molnar, Kasper:<br/>divine freedom"]
  P4 --- C9["Hegel shadow:<br/>necessity of expression"]
  P4 --- C10["No theology of<br/>the false symbol"]
  P5 --- C11["O'Neill: manifests<br/>but does not confer"]
  P6 --- C12["Metz: abstract,<br/>unhistorical"]
  P6 --- C13["Pieris, Soares-Prabhu:<br/>no poverty, no caste"]
  P6 --- C14["Carr, Johnson:<br/>gender absent"]
```

## 6. Rahner vs the other giants — comparison table

| | **Rahner** | **Balthasar** | **Lonergan** | **Schillebeeckx** |
|---|---|---|---|---|
| Starting point | The **subject's** transcendental structure | The **form** (*Gestalt*) of revelation; glory | The **operations of consciousness**; intentionality analysis | **Experience** and its interpretation; hermeneutics |
| Key term | *Realsymbol*, supernatural existential | *Gestalt*, *Herrlichkeit*, *Ernstfall* | Transcendental precepts; conversion; method | Sacrament as encounter; "salvation from God in Jesus" |
| Method | Transcendental | Theological aesthetics / dramatics | Generalised empirical method | Historical-critical + hermeneutical |
| Non-Christians | Anonymous Christians (inclusivism) | Suspicious; stresses the scandal | Openness via conversion | Positive; stresses history and praxis |
| Christ | Unsurpassable self-communication | The form of God's glory; kenosis, Holy Saturday | Meaning and value transformed | The eschatological prophet; parable of God |
| Risk | Abstraction from history | Elitism; aestheticism | Formalism | Reduction to historical reconstruction |
| Strength | Universality of grace | Particularity, beauty, Cross | Methodological clarity | Historical and pastoral realism |

## 7. Timeline strip

```mermaid
timeline
    title Rahner's Life and Works
    1904 : Born, Freiburg
    1922 : Enters Society of Jesus
    1932 : Ordained
    1934-36 : Freiburg; Heidegger's seminars
    1936 : Geist in Welt rejected; doctorate at Innsbruck
    1938-41 : Encounters with Silence; Geist in Welt; Hörer des Wortes
    1954 : Theological Investigations begins
    1958-59 : On the Theology of Death; THE THEOLOGY OF THE SYMBOL
    1962 : Pre-censorship imposed; appointed peritus
    1962-65 : Vatican II
    1967 : The Trinity (Grundaxiom); chair at Münster
    1976 : Foundations of Christian Faith
    1979 : Vatican II as the birth of the World Church
    1984 : Defends Gutiérrez; dies 30 March, Innsbruck
```

## Self-check
- Reproduce diagram 2 from memory and explain each arrow.
- Reproduce diagram 3 and state which value each position secures and which it loses.
- For any four critics in diagram 5, state the critique and a reply.
