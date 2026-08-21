---
title: Knowledge Graph of the Unit
tags: [BTh, theology/rahner, graph, revision]
type: course-note
created: 2026-08-05
updated: 2026-08-06
up: "[[Karl Rahner - Course Home]]"
---

# 23 — Knowledge Graph of the Unit

> [!info] Back to [[Karl Rahner - Course Home]]
> **Rebuilt 2026-08-06** after [[24 - The Theology of the False Symbol]] and its Chauvet verification (§10a). Now **176 concepts · 289 relations · 9 communities** (build history: 137 · 198 · 9 → 163 · 257 · 10 → 176 · 289 · 9).

## Files

| File | What it is | How to open |
|---|---|---|
| `graphify-out/graph.html` | **Interactive graph** — drag, zoom, search, colour-coded by community | Double-click; opens in any browser, no server needed |
| `graph.canvas` | Obsidian **Canvas** with communities as groups | Click it inside Obsidian |
| `graphify-out/GRAPH_REPORT.md` | Audit report — god nodes, surprising connections, ambiguous edges, gaps | Open in Obsidian |
| `graphify-out/graph.json` | Raw graph data (GraphRAG-ready) | For querying / re-use |

**Honesty tags on every edge:** 89% `EXTRACTED` (explicitly stated in these notes), 10% `INFERRED` (a real conceptual dependency the notes imply, avg confidence 0.75), 1% `AMBIGUOUS` (genuinely contested in the literature — flagged, not hidden).

## The nine communities

| # | Community | Cohesion | Centre of gravity |
|---|---|---|---|
| 3 | **The False Symbol, the Idol and the Mystery** | 0.16 | The constructive doctrine, Chauvet, Marion, the idol, Judas's kiss, absolute mystery |
| 6 | **The Abstraction Critique and the Criteria of Discernment** | 0.15 | Metz, Fabro, Balthasar, the feminists — and the five criteria that answer them |
| 7 | **Freedom, Death and the Cross** | 0.15 | *Grundentscheidung*, the lie as self-mutilation, kenosis, Augustine |
| 8 | **Trinity, Rahner's Rule and the Necessity Objection** | 0.15 | *Grundaxiom*, Moltmann, Molnar, Hegel, Fields |
| 5 | **The Thomist Root and the Productionist Critique** | 0.14 | Aquinas, *conversio*, Kant, Maréchal — **and Chauvet's productionist critique** |
| 2 | **Spirituality, Mission and the World Church** | 0.13 | Ignatius, mystagogy, diaspora, inculturation, Jerusalem precedent |
| 4 | **Theology of Religions and Eschatological Speech** | 0.12 | Four theses, Lindbeck, *Dominus Iesus*, eschatological hermeneutics |
| 0 | **Real Symbol and Counter-Symbol: Church, Sacrament, Body** | 0.11 | Five applications, O'Neill, anti-sacrament, competing symbols, caste |
| 1 | **Grace, Self-Communication and Christology** | 0.09 | Existential, quasi-formal causality, evolutionary Christology |

> [!note] Reading the cohesion numbers
> Low cohesion is not a defect. Communities 0 and 1 are **broad**: sacramental theology and grace touch nearly everything else in Rahner, so their members have many edges pointing *out*.

> [!important] What the Chauvet nodes did to the graph — a structural confirmation
> Two results, neither of them intended:
>
> **1. Chauvet's productionist critique clustered with Aquinas, not with Rahner.** `The productionist scheme` and `grace as non-object` landed in **C5, the Thomist community**, alongside Aquinas and *conversio ad phantasma*. That is precisely the correction §10a had to make by hand: Chauvet's target is scholastic causality, not Rahner's *Realsymbol*. The clustering algorithm found it independently.
>
> **2. Chauvet's three temptations clustered with the false symbol, not with the sacraments.** They sit in **C3** beside the idol, the lying symbol, Marion and absolute mystery — confirming that his typology of corruption belongs to the *falsity* discussion and not to sacramental mechanics. And the community that formed around them is now the **most cohesive in the graph (0.16)**, which is a way of saying that the doctrine of symbolic failure has become a genuine centre of the unit rather than an appendix to it.

## God nodes — the ten most connected concepts

| Rank | Concept | Edges | Note |
|---|---|---|---|
| 1 | **The false symbol** | **15** | [[24 - The Theology of the False Symbol]] |
| 2 | Karl Rahner | 13 | (Trivially — the author node) |
| 3= | **Ontology of the symbol** | 12 | [[07 - The Theology of the Symbol - The Core Essay]] |
| 3= | ***Realsymbol*** | 12 | [[07 - The Theology of the Symbol - The Core Essay]] |
| 5= | **Transcendental method** | 11 | [[04 - The Transcendental Method in Theology]] |
| 5= | **Supernatural existential** | 11 | [[05 - The Supernatural Existential - Nature and Grace]] |
| 5= | **Anonymous Christian** | 11 | [[11 - Anonymous Christians and the Non-Christian Religions]] |
| 8= | Symbolic causality | 10 | [[12 - Ecclesiology and Sacramental Theology]] |
| 8= | **Counter-symbol / anti-sacrament** | 10 | [[24 - The Theology of the False Symbol]] §7 |
| 10 | Church as *Grundsakrament* | 9 | [[12 - Ecclesiology and Sacramental Theology]] |

> [!important] The finding worth an essay
> **The false symbol is now the most connected concept in the unit — ahead of the symbol ontology itself, and ahead of Rahner.**
>
> It entered at 12 edges and rose to 15 once Chauvet was checked in. That is a structural result, not a compliment to note 24. A doctrine that connects to fifteen existing concepts was never an optional extra: the graph was **load-bearing around a hole**. Ecclesiology, sacramental theology, the caste argument, the Cross, Balthasar's critique and Chauvet's whole project were all reaching for a doctrine that was not there.
>
> Rahner's system therefore has **four** pillars, not three: method, symbol ontology, grace — and, implicitly, an account of how symbolisation fails, which he never wrote down.
>
> **Caveat worth keeping honest:** part of this centrality is an artefact of where the recent writing went. Two of the last three edits were about falsity, so falsity accumulated edges. The claim survives anyway — but state it as "the unit now turns on this" rather than "Rahner's corpus does."

## The bridges (highest betweenness — the concepts that hold the system together)

1. **Ontology of the symbol** — links the symbol essay to the theology of religions, sacramental theology, the Trinity, and the critics. Cut it and the system falls into unrelated pieces.
2. **Transcendental method** — links epistemology to grace, to the symbol ontology, and to religions.
3. **The false symbol** — now links ecclesiology, sacramental theology, the Cross, the Indian material and Balthasar's critique into one argument.
4. **Anonymous Christian** — links the theology of religions to the *Vorgriff*, to grace, and to Balthasar's counter-position.

## Surprising connections the graph surfaced

- **`Quasi-formal causality` ≈ `Realsymbol`.** Two doctrines from different notes doing structurally identical work: God present *in* another as an inner constitutive principle without composition. Rahner's grace theory and his symbol ontology are the same move in two registers, and he never says so.
- **`Darshana / prasada` ≈ `Realsymbol`.** The Indian sensibility that the sacred is present rather than represented sits closer to Rahner's *Realsymbol* than to the modern Western "merely symbolic." → [[18 - Rahner in the Indian Context]]
- **`Lawful religion thesis` ≈ `Cultural-linguistic model`.** Rahner's argument that grace must take *social, ritual and historical* form partly **anticipates** the model Lindbeck deploys against him. → [[16 - Critical Reflection I - Philosophical]]
- **`Soares-Prabhu` ≈ `Metz`.** Independent critiques from Pune and Münster converge: the transcendental subject arrives too late at suffering. Note 24's **victim criterion** is where that convergence gets absorbed into the ontology rather than left as an objection.
- **`Ontology of the symbol` → `Mission redefined`.** Rahner's account of mission (making grace explicit rather than importing it) is a consequence of the **symbol ontology**, not of his theology of religions. Missiologists usually miss this.
- **`Marion's idol` → inside Rahner, not against him.** The idol/icon distinction, invented as an anti-Rahnerian weapon, clusters with *Vorgriff* and absolute mystery once the false-symbol typology exists — it turns out to name a mode of symbolic failure Rahner's own ontology needed.

## Ambiguous edges — flagged for your own judgement

Four now, up from two — the Chauvet check added the two that touch this unit's own construction.

| Edge | Why it is ambiguous |
|---|---|
| `Kant` → **undercuts** → `Vorgriff auf esse` | Whether Kant's *Transcendental Dialectic* actually defeats Rahner's retorsion argument is unresolved → [[16 - Critical Reflection I - Philosophical]] |
| `The disputed 'vice versa'` → **endangers** → `Divine freedom` | The central live dispute over Rahner's Rule; Rahner's texts do not settle it → [[09 - Rahner's Rule - The Grundaxiom of the Trinity]] |
| `Realsymbol` → **tensions_with** → `Presence of the absence` | Rahner: the symbol is maximal presence. Chauvet: the symbol is the site of an absence not to be filled. Unreconciled → [[24 - The Theology of the False Symbol]] §10a |
| `A lie is not an arbitrary sign` → **destabilises** → `Presence of the absence` | §2's load-bearing claim assumes symbols carry presence. On a Chauvetian reading falsity would instead be *refused absence*. **This one is a flag against my own argument, kept deliberately** |

> [!tip] Use these four edges as essay topics
> An "ambiguous" tag marks exactly where the literature has not settled — which is exactly where a BTh essay can say something. The last two mark where **this unit** has not settled, which is better still: you can finish an argument the notes leave open.

## Rebuilding after you edit the notes

The graph is authored, not scraped: the concept nodes and their relations were written by hand, so `graphify update` will re-read changed **files** but will not invent new **concepts**. To add concepts, extend the extraction script and re-run the pipeline.

```bash
graphify update "D:/Obsidian Notes willy 2025/Willy Dec 2025/BTh01/BTH Notes-01/Karl Rahner"
```
