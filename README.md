# solvency-proofs

### New updates:
- Dec 1st, 2022: audit report for Binance's Proof of Reserve's solution has been uploaded. TL;DR 4 vulnerabilities and 3 other privacy, trust and optimization issues have been reported. See the full report [here](/audits/audit_reports/Binance_PoR_by_MystenLabs_Nov_28_2022.pdf).
  - Binance is already working with their auditor and cryptography experts to address feedback and try to improve in the subsequent versions of their PoR system.

## Goal
This repository aims at tracking and enlisting:
- cryptographic schemes for proofs of solvency applied to centralized exchanges, wrapped coins, custodians etc. These schemes typically include: 
  - **proofs of liabilities**: proving the total value the prover owes to all of its customers or creditors.
  - **proofs of assets** (also known as proof of reserves) and is divided into 2 main categories:
      - blockchain account ownership for various assets:
        - fungible: cryptocurrency, stable coins etc.
        - non-fungible (NFTs)
      - non-blockchain asset ownership (cash, bonds, stocks, real estate etc.), usually divided into:
        - liquid assets
        - semi-liquid assets (can be converted to cash within a reasonable amount of time, usually within one year)
        - illiquid assets
  - **proofs of solvency**: the combined outcome of the above two, including absolute, fractional or with a surplus solvency expectations. 
- useful cryptographic primitives:
  - Zero-Knowledge Proof systems and related gadgets
  - Merkle trees (including sparse trees)
  - Random sampling algorithms
  - Private Information Retrieval (to avoid tracking who verifies proofs)
- repository links with implementations for any of the above algorithms / solutions
- official audit reports
- links to official solvency reports from various exchanges 
- list of Exchanges, Oracles and Auditors and Organizations that work on (provide) solvency proofs solutions.
- interesting news-posts or social network threads and posts (Reddit, Twitter, LinkedIn etc)
- other educational material, including podcasts and blogposts
- list of known attacks or insolvent cases
