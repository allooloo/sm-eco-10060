# SM-ECO-10060

**SM-ECO-10060 defines the jurisdiction binding of a signed capital-product record and the market chapter from which that binding is published. Each chapter preserves the market's duties, authorities, sources, dates, conditions and exact section versions, with the producing node's signature. The jurisdiction namespace maps explicitly to the market value carried in the receipt. Member pages, node pages and specialised readouts derive from the same immutable chapter; ACM rule revisions point to the chapter evidence that produced them. SM-ECO makes the market context recoverable across the family while keeping separate the responsibilities of sourced content, clearance, orderability, venue reference and proof of the read.**

Reference site: **https://sm-eco-10060.org/** — canonical text v1.0 (30 October 2026).

## The contract

SM-ECO-10060 defines the jurisdiction binding of a signed record. It owns the market field carried in the receipt, the jurisdiction namespace, and the relationship between a record, its market's duty and the responsible regulator. Its central object is the market chapter: the sourced, dated and versioned body of information an artificial-intelligence (AI) agent needs to understand the obligations and constraints relevant to its specified activity in that market.

The Book of Markets holds these chapters as structured records. A chapter brings together the market's authorities, applicable duties, disclosure infrastructure, product and client constraints, venue reference information and sustainability-disclosure regime. Each field preserves the evidence behind its value. Each section has a defined schema and an immutable version. A member page is a readout of its chapter.

The chapter begins with the activity and the duty. An agent must identify the product and subject, the actor and client category, the applicable jurisdiction, the governing revision, the information it must read, the restrictions it must test and the evidence it must retain. The chapter supplies the market context for those questions. Product-specific facts and client-specific assessments remain referenced records, never invented market-wide answers.

Every published chapter preserves subject and market scope, provenance, source observation time, applicability dates, revision identity and producing-node attribution. A field can be present, not found, unavailable, not applicable or conflicting without those states being collapsed. Sourceable information relevant to the duty stays in the chapter even when it has no place on the current page.

## What the standard does not do

A chapter is a structured representation of sourced information. It does not certify a product, establish the truth of a source, give an individual legal opinion, or guarantee that every applicable obligation has been captured. Its declared scope and evidence gaps determine what it can support.

Finding a regulator, venue, filing or endpoint does not authorise an action. Missing evidence does not establish a prohibition. A failed source request does not establish that a rule is absent. A chapter supports a clearance evaluation only when its evidence, scope and rule references satisfy the evaluating profile.

Jurisdiction binding does not by itself prove data residency, regulatory recognition or an actor's entitlement. Hosting location, listing market, issuer domicile, client location and applicable regime are distinct attributes; cross-border applicability is represented through explicit references and conditions.

Artificial intelligence makes mistakes. Every field links the page it was read on. Read the regulator.

## Who signs

The producing market node signs its chapter and its specialised section records under the record key, following the ECO-10060 content contract. Attribution names the producing node inside the signed payload. Shared regime material is referenced from its separately signed authoritative record; a market node never presents a shared revision as its own original publication.

A national rule revision is produced by the market's node; a shared rule-family revision is produced by the apex. Both use the record key. Market chapters reference the exact shared revision and record national applicability, additions or exceptions with their own evidence.

RCO-10060 separately governs the receipt, signed by the receipt door under the receipt key. The receipt carries the deployed market value and the applied rule_version; its answer_hash binds it to the exact signed answer supplied. The record key signs content; the receipt key signs the read. Neither signs the other's object.

## The arrow

listed security  →  record (ECO-10060, the node)  →  market and duty (SM-ECO-10060, the chapter)  →  rule (ACM-68000)  →  whether (AIO)  →  where (AMP)  →  receipt (RCO-10060, under every door)

A dependency model, not a ladder. ECO supplies attributable content; SM-ECO supplies jurisdiction and duty context; ACM-68000 supplies rule revisions and the clearance vocabulary; AI Orderability (AIO) supplies the structured product, market and client-class outcome; the Agentic Market Protocol (AMP) supplies venue reference information and, only under a separately evidenced clearance profile, route resolution; CPG-68000 is the umbrella.

AIO may require venue restrictions before it can conclude. Venue discovery can precede clearance, while an actionable route requires the relevant clearance and orderability results. Sustainability disclosure (ESG) is a specialised ECO record and a rule family in ACM, not a tier; it supplies evidence for a defined sustainability condition and never a generic sustainable outcome.

## The thing SM-ECO owns

The jurisdiction namespace identifies the member and its scope. The receipt's market field keeps the deployed representation. Namespace and receipt value are explicitly mapped in the fleet registry; a richer namespace never silently replaces a deployed receipt value. Country, jurisdiction and venue identifiers are never used interchangeably.

The chapter is the durable source for the member page, the product node page and the per-market sections of the other standards. Protocol membership and live product service are separate layers with independent lifecycle states. Their addresses come from the fleet registry and are never constructed from a country code.

A chapter version is an immutable manifest naming exact section versions. Every section is immutable once written. A change produces a new version with a supersedes relationship and never overwrites the earlier one. An unchanged section may be referenced unchanged by a successor chapter. Historical versions remain recoverable for the records and receipts that refer to them.

A chapter version is the evidence event an ACM rule revision points at. The rule reference names the exact chapter version, section and evidence from which the rule was produced. A changed observation or calendar field creates a new chapter version but not, by itself, a new duty revision; a substantive rule or binding change creates a new immutable rule revision linked to its source chapter event.

Chapter content is committed first; rule revisions then reference that immutable content; a later chapter manifest may reference those revisions. A revision never depends on its own digest through a chapter that embeds the same revision. The implementation publishes the exact reference and hashing profile.

## Publication discipline

One approved schema and one sourced record feed every readout. Readers populate the Book on a declared cadence, with additional passes for detected changes. The publication rail reads accepted chapter versions; pages conduct no searches of their own and introduce no unsupported values.

Each reading run records the source set, observation time, success or failure, changed fields, unresolved gaps and conflicts. A failed run never erases the last valid chapter or presents its observations as fresh; readers keep the last accepted record with visible age and failure status until a successor is validated.

The rail publishes a consistent chapter selection across related surfaces and makes each surface's source version inspectable. Validation rejects mismatched markets, broken references, missing provenance and invalid signatures. A partial publication is reported as drift, never concealed by updating displayed dates.

No coverage total, member ordinal or inventory total appears in authored prose; generated displays read the record. Acronyms are expanded on first use; definitions stay stable; reading guides index authoritative resources and add no doctrine. Publication supports discovery and grounded interpretation; it guarantees neither model training inclusion nor regulatory recognition.

The sequence is mission, schema, source reading, field population, validation, publication. A semantic amendment names its compatibility and affected schemas. Standard version, chapter version, section version, rule revision and deployment version stay distinct.

## Machine files

- registry.json — the members in registry order (written by the nightly eco-ops agent)
- https://sm-eco-10060.org/nodes.json · /protocol.json · /llms.txt
- the Book of Markets chapters: one chapter manifest per market (C:\ALLOOLOO\BOOK, mirrored to the ops store)

---

Standard held by Allooloo Technologies Corp. · Open standard, MIT licence.
