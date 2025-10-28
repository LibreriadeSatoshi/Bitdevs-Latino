#Bitdevs Latino

[BitDevs Madrid](https://bitdevsmadrid.org/socratic-seminar-0/)
[BitDevs Barcelona](https://bitdevsbarcelona.org/socratic-seminar-5/)
[CDMX BitDevs](https://www.cdmxbitdevs.org/2025-06-19-socratic-seminar-6.html)
[BitDevs Córdoba](https://bitdevscordoba.org/socratic-seminar-9/)
[Santiago BitDevs](https://santiagobitdevs.com/2025-08-26-socratic-seminar-09-nostr)
[BitDevs GDL (BTC GDL)](https://bitdevs.btcgdl.com/2025-08-12-socratic-seminar-14)
[BitDevs El Salvador](https://bitdevelsalvador.com/2025-08-20-socratic-seminar-16)
[BitDevs BA](https://www.bitdevsba.org/socratic-seminar-6/)


### Recordatorios

- No se permiten fotografías, vídeos o grabaciones de audio
- Nos adherimos a "[the Chatham House Rule](https://www.chathamhouse.org/about-us/chatham-house-rule)"
- Mantener el enfoque en Bitcoin y tecnologías afines; no se permite la promoción de otras criptomonedas.
- Mutear tu mic si no estás hablando. 
- Respetar los tiempos de intervención, tratar de ser concis@
- Sugiere temas para el siguiente Seminario Socrático! [¿Donde encontrar temas para futuros seminarios?](/about/find-topics)


### Oportunidades educativas o laborales
[Bitcoiner Jobs](https://bitcoinerjobs.com/) 

Grants y entrenamiento: [B4OS](B4os.dev)

### Conferencias
https://labitconf.com/


### Estadísticas de la Red
- [mempool.space](https://mempool.space/)
- [clarkmoody.com](https://bitcoin.clarkmoody.com/dashboard/)
- [utxo.live](https://utxo.live/)
- [bitcointreasuries.net](https://bitcointreasuries.net/)
- [stratum.work](https://stratum.work/)
- [non standard txs dataset](https://bitcoin-data.github.io/non-standard-transactions/)
- [mining centralization index](https://mainnet.observer/charts/mining-pools-centralization-index-with-proxy-pools/?c)


## Temas Miercoles 28 de Oct - Bitdevs Latino #3

# Bitcoin Development Reading List

## Bitcoin Core Development

### Protocol Improvements
- [fuzz: replace hardcoded numbers for bech32 limits](https://github.com/bitcoin/bitcoin/pull/30596) - PR improving bech32 fuzz testing by removing hardcoded limits
- [p2p: improve TxOrphanage denial of service bounds](https://github.com/bitcoin/bitcoin/pull/31829) - Enhanced DoS protection for transaction orphanage handling

### Package Relay & Mempool
- [Changing the minimum relay feerate](https://delvingbitcoin.org/t/changing-the-minimum-relay-feerate/1886) - Discussion on Delving Bitcoin about lowering the minimum feerate
- [Package Relay Project Tracking](https://github.com/bitcoin/bitcoin/issues/27463) - Comprehensive tracking issue for package relay implementation
- [Pay to Anchor and Ephemeral Dust](https://bitcoin.stackexchange.com/questions/123456/pay-to-anchor-and-ephemeral-dust) - Discussion on P2A and ephemeral dust handling

### Multiprocess Architecture  
- [Multiprocess tracking issue](https://github.com/bitcoin/bitcoin/issues/28722) - Core issue tracking multiprocess Bitcoin implementation
- [Add bitcoin-{node,gui} to release binaries for IPC](https://github.com/bitcoin/bitcoin/pull/31802) - PR adding IPC binaries to releases
- [Multiprocess: Add basic spawn and IPC support](https://bitcoincore.reviews) - PR Review Club discussion
- [Bitcoin Core Multiprocess Design](https://github.com/ryanofsky/bitcoin/blob/ipc/pr/doc/design/multiprocess.md) - Technical design documentation
- [Cap'n Proto: Introduction](https://capnproto.org/index.html) - IPC serialization protocol used in multiprocess implementation

## Research & Innovation

### Sync Optimization
- [SwiftSync -- Speeding up IBD with pre-generated hints (PoC)](https://delvingbitcoin.org) - Novel approach to accelerate Initial Block Download
- [SwiftSync Implementation](https://github.com/2140-dev/swiftsync) - Reference implementation and underlying crates
- [Bitcoin Kernel: Examples](https://github.com/bitcoin/bitcoin/tree/master/src/kernel) - Modular kernel examples for alternative implementations

### Network Analysis
- [Stats on compact block reconstructions](https://delvingbitcoin.org) - Analysis of compact block performance and optimization opportunities  
- [Bitcoin Network Monitor - DSN Research Group](https://dsn.kastel.kit.edu/bitcoin/) - Real-time Bitcoin network monitoring and analysis
- [0xB10C Bitcoin Research](https://github.com/0xB10C) - Network analysis tools and research
- [peer-observer DHD Prague 2025](https://docs.google.com/presentation/d/peer-observer-dhd-prague-2025) - Presentation on Bitcoin peer observation techniques

## Lightning Network

### Protocol Extensions
- [A Lightning Network of multi-party mechanisms]([https://delvingbitcoin.org](https://delvingbitcoin.org/t/a-lightning-network-of-multi-party-mechanisms/1163)) - Research on extending LN beyond two-party channels


---
BITDEVS LATINO #2 
*Reading list compiled for Bitcoin development discussion and technical analysis*


### X & NOSTR
[Samourai Wallet Developers Plead Guilty to Conspiring to Operate an Unlicensed Money Transmitting Business]
(https://bitcoinmagazine.com/news/samourai-wallet-developers-plead-guilty)


#### Post-Quantum
- [A Post Quantum Migration Proposal](https://groups.google.com/g/bitcoindev/c/uEaf4bj07rE)
- [Video: Quantum Bitcoin Summit Day 1](https://www.youtube.com/watch?v=GeUdu4hrBPI)
- [Video: Quantum Bitcoin Summit Day 2](https://www.youtube.com/watch?v=feMWrdJnLak)
- [Lopp Post in Google Groups](https://groups.google.com/g/bitcoindev/c/uEaf4bj07rE?pli=1)
- [Post-Quantum HD-Wallets, Silent Payments, Key Aggregation, and Threshold Signatures](https://delvingbitcoin.org/t/post-quantum-hd-wallets-silent-payments-key-aggregation-and-threshold-signatures/1854)


#### Minimum Relay Feerate
- [Changing the minimum relay feerate](https://delvingbitcoin.org/t/changing-the-minimum-relay-feerate/1886)
- [#33106 - policy: lower the default blockmintxfee, incrementalrelayfee, minrelaytxfee](https://github.com/bitcoin/bitcoin/pull/33106)
- [Bitcoin Core development and transaction relay policy](https://bitcoincore.org/en/2025/06/06/relay-statement/)
- [Sub 1 sat/vB stale block analysis](https://x.com/mononautical/status/1956073741454336191)


#### Security
- [Not in The Prophecies: Practical Attacks on Nostr](https://eprint.iacr.org/2025/1459)
- [Qubic reorgs Monero Blockchain](https://qubic.org/pr/qubic-overtakes-monero-s-hash-rate-in-live-51-takeover-demo)


#### Otros

- [Augur: Block’s Open Source Bitcoin Fee Estimation Library](https://delvingbitcoin.org/t/augur-block-s-open-source-bitcoin-fee-estimation-library/1848)
- [Spiral. Nerd of the Month #5: A Castle of Glass](https://spiralbtc.substack.com/p/nerd-of-the-month-5-a-castle-of-glass-1f4)
- [utreexo](https://github.com/utreexo/utreexo) - [bitcoinops.or/utreexo](https://bitcoinops.org/en/topics/utreexo)- Utreexo
