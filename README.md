# PostQuantum Cash Improvement Proposals (PQIPs)

Public design documents for changes to PostQuantum Cash (PQCH): consensus rules, the peer-to-peer
protocol, node and wallet behaviour, and how the project works. How a PQIP is written, discussed and
activated is in [PQIP 1](pqip-0001.md).

| Number | Title | Type | Status |
| --- | --- | --- | --- |
| [1](pqip-0001.md) | PQIP purpose and process | Process | Proposed |
| [2](pqip-0002.md) | Pay-to-Merkle-Root outputs and post-quantum signatures | Consensus | Proposed |
| [3](pqip-0003.md) | Merged mining with Monero (AuxPoW) and the Monero key rule | Consensus | Proposed |
| [4](pqip-0004.md) | ML-DSA emergency soft fork | Consensus | Proposed |

## Proposing a PQIP

1. Discuss the idea first on the PQCH forum or in the Matrix room (both linked from
   [pqch.org](https://pqch.org)), to see whether it is new and wanted.
2. Open a pull request with `pqip-draft-<short-name>.md`, following the format in PQIP 1. The editors
   check the form and assign a number.
3. A vulnerability is never proposed here: report it privately (see `SECURITY.md` in
   [pqch-core/pqch](https://github.com/pqch-core/pqch)).

All PQIPs are dedicated to the public domain under [CC0-1.0](LICENSE).
