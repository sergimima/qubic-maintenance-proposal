# Proposal: QBridge Operation — 12‑month Continuation Agreement

## Proposal
Approve a 12-month continuation agreement between Vottun (“Operator”) and the Qubic Incubation Program (“Client”) to operate and maintain the non-custodial cross-chain Qubic ↔ Ethereum bridge (“QBridge”), including validator services, APIs, and middleware. Terms summarized below.

Send 30,000 USDT +5% if paid in QUBIC to Identity `BQARESULJVFAYAFSLATVPCYKDGTCEEQSAZHWLXCOQFRAHFSZWTWJUJLDCSNJ` to fund the 12‑month maintenance of QBridge (≈ 12.56B QUBIC at MEXC; ≈ 13.19B incl. +5%).

Additionally, request the Incubation Program or its market maker to seed an initial Uniswap wQubic/ETH pool by bridging approximately $25,000 in QUBIC paired with ETH via QBridge (≈ 10.47B QUBIC at MEXC). Liquidity remains under Incubation/MM ownership (they capture fees and may withdraw at any time). This is separate from the 30,000 USDT maintenance fee.

> Option 0: no  
> Option 1: yes, approve the continuation agreement as outlined


## How We Used Past Funding

- This is a continuation agreement to operate and maintain QBridge following its initial development and integration work.
- Prior work included: bridge architecture and implementation, validator/middleware setup, deployment/testing, and integration with the target liquidity venue (Uniswap) for wQubic/ETH.

## Overview
QBridge connects Qubic and Ethereum, enabling secure, non-custodial bridging of QUBIC and wQubic with a user experience aligned with leading bridges. The goal is to unlock interoperability, liquidity access, and DeFi participation for Qubic.

This proposal combines:
- Stable operations funding via a 12‑month maintenance fee.
- An initial liquidity request to seed a wQubic/ETH pool on Uniswap (owned and controlled by Incubation/MM).
- Clear SLAs, governance, and a structured review at term end.

## Provided Services / What QCT does
- Operate, monitor, and maintain bridge infrastructure: validator services, APIs, middleware.  
- Support secure and reliable operations; apply patches, updates, and security improvements during the term.  
- Business-hours monitoring with on-call escalation for critical incidents (see SLA).

Notes:
- Operation is performed on behalf of the shareholder that owns the Qubic smart contract after CCF is processed.
- Future protocol-level upgrades beyond standard maintenance are out of scope (see “Future Upgrades”).

## Maintained Products/Software
- QBridge validator services and monitoring
- QBridge middleware and APIs
- Operational dashboards and alerting
- Deployment/configuration assets for Ethereum and Qubic endpoints

## Fees and Economics
- Maintenance Fee (12 months): 30,000 USDT equivalent. Payable in USDT/USDC, or in QUBIC (+5% volatility adjustment if paid in QUBIC).
- Bridge Fee Split: 50% to Vottun (Operator), 50% to the winner of the smart contract CFF bidding.
- Liquidity Support Suggestion: 40% of bridge fees to be locked in the Uniswap LP to strengthen liquidity.  
  Clarification to be finalized with Client: whether the 40% applies to gross bridge fees or to a party’s share, and custody/timing.

## Initial Liquidity Request (Uniswap wQubic/ETH)
- Request: Incubation Program or its Market Maker (MM) bridges ~$25,000 worth of QUBIC and pairs it with an equivalent amount of ETH to create the initial wQubic/ETH pool on Uniswap.
- Ownership and Control: The liquidity remains fully owned and managed by Incubation/MM, who captures fees and may withdraw at any time.
- Rationale: Ensures successful launch, improves accessibility, increases trading activity, and signals commitment to the market, encouraging community LP participation.

## Service Level Agreement (SLA)
Business hours: Monday–Friday, 09:00–18:00 CET (UTC+1), excluding Spanish national holidays.  
Outside business hours: on-call engineers are auto-escalated for S1 and will strive to meet S1 targets.

| Severity | Definition                                           | Initial Response | Workaround Target         | Full Resolution Target                  |
|---------:|------------------------------------------------------|------------------|---------------------------|-----------------------------------------|
| S1 — Critical | Bridge fully down, funds at risk, or security incident | ≤ 30 minutes     | ≤ 4 business hours        | ≤ 24 hours                              |
| S2 — High     | Degraded performance or partial outage, no fund risk   | ≤ 2 business hrs | ≤ 1 business day          | ≤ 1 business day                        |
| S3 — Normal   | Minor issue, cosmetic defect, non-blocking request     | —                | ≤ 3 business days         | Next scheduled maintenance release      |

Additional targets:
- Uptime: ≥ 99.5% monthly for core bridge functions (excluding announced maintenance).
- Scheduled maintenance: announced ≥ 24 hours in advance and, when feasible, performed outside business hours.

## Term and Review
- Initial Term: 12 months from the Effective Date.
- Review: ≥ 30 days before term end, Parties review total bridge fees vs. Maintenance Fee.
  - If Vottun’s 50% fee share exceeds the Maintenance Fee by ≥ 30% for the period, Parties acknowledge the bridge is self-sustaining; the Agreement expires at term end unless mutually renewed/modified.
  - If fees are below the Maintenance Fee, Parties may renew for an additional 12 months with agreed scope adjustments.

## Future Upgrades (Out of Scope)
Changes to the Qubic protocol, SDKs, consensus, or core infra beyond standard maintenance are excluded. Any adaptation requires separate scope, timeline, and commercial agreement.

## Termination
- Either party may terminate with 60 days’ written notice.  
- For breach: 15 days’ notice to cure; if not remedied, the non-breaching party may terminate.

## Dispute Resolution and Governing Law
- Governing Law: British Virgin Islands (BVI).  
- Dispute Resolution: ICC binding arbitration, seat in Barcelona, Spain. Arbitrator’s decision is final and binding.

## Governance
- Liquidity and fee ownership/custody remain with Incubation/MM as specified.
- Transparency: Vottun will provide reasonable operational reporting aligned with the SLA and term review requirements.

## Success Indicators
- Stable operations with uptime ≥ 99.5%.  
- Incidents handled within SLA targets.  
- Liquidity pool established and maintained; community LP participation increases.  
- Bridge volumes and fees trending toward self-sustainability.

## Cost Break Down
- Infrastructure and operational monitoring/resources for bridge components.
- Personnel for operations, on-call, and maintenance activities aligned with SLA.
- Security patches, updates, and routine maintenance tasks.

## Definitions
- CCF: Community Contribution Fund (context: Qubic).  
- CFF: Smart contract bidding winner referenced in fee split (as per source text).  
- IPO: Referenced in source text; confirm intended usage/meaning in this context.

## References
- https://uniswap.org/
- https://qubic.org/

## Effective Date and Signatures
- Effective Date: [DD MMM YYYY]  
- Operator: Vottun — [Name, Title, Contact]  
- Client: Qubic Incubation Program — [Name, Title, Contact]