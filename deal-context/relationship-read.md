---
type: concept
title: Relationship read — partner or vendor?
tags: [relationship, account-strategy, commercial, positioning, deal-context]
sources:
  - ./stakeholder-map.md
  - ./group-structure.md
  - ./go-no-go-flags.md
  - ./open-questions.md
  - ./competitive-positioning.md
  - ../technical-architecture/system-overview.md
last_updated: 2026-05-29
status: active
---

# Relationship read — does SocialRemit see VL as a strategic partner or a technical vendor?

**Short answer: the signals are mixed, and that ambiguity is itself the central commercial
risk of the deal.** This is not yet a settled fact — it is something the deal will *decide*,
and VL has leverage over which way it resolves. Treat "they see us as a strategic partner" as
a hopeful hypothesis until the commercial terms are tested.

## Signals pointing to "strategic long-term partner"

This is what Joseph *says* and how he behaves *relationally*:

- **He bypassed sales and went straight to the architect.** Joseph re-engaged Boris Vida directly in May 2026, not the BD contact. His sentiment is read as wanting "architecture and delivery credibility, not a sales pitch" ([stakeholder-map.md](./stakeholder-map.md)).
- **He framed it as "not just a one-off project."** Joseph laid out the full Affecta flywheel (Transpara, E-money Score, E-money Finance) and positioned the MVP as step one of a multi-product journey ([group-structure.md](./group-structure.md)). VL's own read of the pitch is "be the technology partner for the journey" ([competitive-positioning.md](../product-management/competitive-positioning.md)).
- **The BFF is positioned as a shared crown jewel.** The middleware is described as the primary intellectual asset VL is creating and the enabler of the Fincode→Transpara exit — tied to SocialRemit's investor story ([system-overview.md](../technical-architecture/system-overview.md)).
- **The equity / deferred-payment ask is, on its face, a partnership posture** — share the risk and the upside.

## Signals pointing to "cheap technical vendor"

This is how Joseph *buys*:

- **He is actively shopping freelancers at £5k–£10k** and "speaking to so many different people giving me proposals" ([competitive-positioning.md](../product-management/competitive-positioning.md), [open-questions.md](./open-questions.md) item 14) — commodity sourcing behaviour.
- **No budget figure, and a 10–20× perception gap** against VL's prior £118–169k ([go-no-go-flags.md](./go-no-go-flags.md)).
- **The equity/deferred-payment ask reads less charitably** as "I can't or won't pay VL's rate upfront." VL's go/no-go treats it as the single red flag, not as evidence of partnership ([go-no-go-flags.md](./go-no-go-flags.md)).

## The read

The most likely synthesis: **Joseph wants a strategic partner but is trying to procure one
at vendor (or below-vendor) prices, using equity as the bridge.** He genuinely values VL's
technical credibility — that is why he returned to Boris — but he is also a cash-constrained,
finance-trained founder (FCCA) optimising hard on price and risk transfer. Both are true and
they are in tension.

Note the pattern: the "partner" framing is strongest where Joseph is *talking*; the "vendor"
framing where he is *buying*.

## Why it matters / how it resolves

The answer is not fixed — the commercial decision will set it:

- **If VL accepts deferred-payment + equity**, it *becomes* a partner, with partner-level risk and upside.
- **If VL holds standard terms**, the relationship likely collapses back to "vendor" — and a cheaper option probably wins.

This is exactly why everything hinges on Andy Birch's (CRO) commercial answer ahead of the
2026-06-01 internal alignment. Until then, do not let the flattering "partner" narrative
justify over-investing presale effort — the same caution the go/no-go page makes.

**Revisit this page** when the commercial terms are decided and again at proposal/negotiation;
the partner-vs-vendor question will recur.

## What we're actually selling — and the discovery gap

The partner-vs-vendor tension shows up concretely in *what the client thinks they are buying*.

**SocialRemit considers discovery done and wants delivery.** From Joseph's side, product
definition is *his* job and it is finished: a full Figma prototype and a November 2025
screen-by-screen spec exist; the platform/vendor decisions are made (Fincode, Sumsub, Trust
Payments, Volume); corridors are fixed (Ghana + Nigeria); a governance/architecture model is
formalised; and the business rails are in place (EMI licence, $900M liquidity, AML board).
The 19 May go-live scope was *"Flutter frontend + BFF + Fincode — the full stack,"* live in
6–8 weeks ([open-questions.md](./open-questions.md) item 16, [client-overview.md](./client-overview.md),
[product-vision.md](../product-management/product-vision.md), [governance-principles.md](../technical-architecture/governance-principles.md)).

**What VL is selling is a build engagement** — the Flutter/RN app + the BFF/middleware layer
+ integration of Fincode, Sumsub, Trust Payments and Volume, with the BFF designed as the
Fincode→Transpara exit ramp ([system-overview.md](../technical-architecture/system-overview.md)).
Note the scope *grew*: the December 2025 proposal was a frontend-only "FE build" (Joseph
wanted an asset he could keep if the backend relationship soured —
[proposal-dec-2025.md](./proposal-dec-2025.md), [stakeholder-map.md](./stakeholder-map.md)); the
May re-engagement is now full-stack.

**The gap:** the client believes discovery is finished; VL's own analysis says critical
pieces are unvalidated. What SocialRemit completed is *design / product-definition* discovery
(screens, flows, vendors). What is missing is *strategic* discovery and *scope/technical*
confirmation:

- No personas or validated user research — the "built by migrants" claim is unproven ([migrant-user-research-brief.md](../product-management/research/migrant-user-research-brief.md)).
- No competitor / white-space analysis ([competitor-research-brief.md](../product-management/research/competitor-research-brief.md)).
- No GTM / first-10k plan; the transaction-target-vs-customer math does not reconcile.
- Scope itself is not VL-confirmed, and the Fincode API is unverified (sandbox creds pending), so BFF build scope is still an estimate ([pre-meeting-brief.md](./pre-meeting-brief.md), [fincode-gap-analysis.md](../technical-architecture/fincode-gap-analysis.md)).

**Framing implication.** VL's discovery work is not re-doing Joseph's homework — it is
de-risking *his* delivery and *our* fixed-timeline commitment. But a founder who believes
discovery is done can read VL discovery questions either as reassuring rigour or as an agency
padding the bill. It must be presented as the former. This ties directly to the partner-vs-
vendor question above: a pure delivery *vendor* just builds the Figma; a strategic *partner*
is expected to challenge the strategy. Which one VL is determines how much discovery the
client will actually pay for or tolerate.
