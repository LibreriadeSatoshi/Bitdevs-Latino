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



### Estadísticas de la Red
- [mempool.space](https://mempool.space/)
- [clarkmoody.com](https://bitcoin.clarkmoody.com/dashboard/)
- [utxo.live](https://utxo.live/)
- [bitcointreasuries.net](https://bitcointreasuries.net/)
- [stratum.work](https://stratum.work/)
- [non standard txs dataset](https://bitcoin-data.github.io/non-standard-transactions/)
- [mining centralization index](https://mainnet.observer/charts/mining-pools-centralization-index-with-proxy-pools/?c)



# Temas Next bitdevs Fecha semana del 23 Dic - Bitdevs Latino #4 - 

➡️✍️👩‍💻📖 
Poner el nombre + link de la Lectura que vas a exponer o bien estás listo para hablar de ella. 



News & Announcements
--------------------

- 
Discussion
----------

### Tweets, Blogs & Podcasts

- 

### [bitcoin-dev](https://groups.google.com/g/bitcoindev)

- 

### [Delving Bitcoin](https://delvingbitcoin.org/)

- 
CVEs and Research
-----------------

### Research

- 

### InfoSec

- 


BIPs
----

- 

Noteworthy PRs
--------------

### [Bitcoin Core](https://github.com/bitcoin/bitcoin)

- 









End





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
- [A Lightning Network of multi-party mechanisms](https://delvingbitcoin.org/t/a-lightning-network-of-multi-party-mechanisms/1163)

---
# Temas Martes 20 de Enero - Bitdevs Latino #5
*Reading list compiled for Bitcoin development discussion and technical analysis*


## Libsecp256k1

- [ecmult_multi: reduce strauss memory usage by 30%](https://github.com/bitcoin-core/secp256k1/pull/1761)

## Bitcoin Dev Mailing List

- [BIP idea: Timelock-Recovery storage format](https://groups.google.com/g/bitcoindev/c/K1NpJp9_BYk)
- [Reducing RAM requirements with dynamic dust](https://groups.google.com/g/bitcoindev/c/PMtM_I3qwqg)

## Delving Bitcoin

- [Miniscript Studio - a fulll IDE based on Rust Miniscript](https://delvingbitcoin.org/t/miniscript-studio-a-fulll-ide-based-on-rust-miniscript/2086)
- [Comparing the performance of ECDSA signature validation in OpenSSL vs. libsecp256k1 over the last decade](https://delvingbitcoin.org/t/comparing-the-performance-of-ecdsa-signature-validation-in-openssl-vs-libsecp256k1-over-the-last-decade/2087)
- [A Game-Theoretic Approach to Bitcoin’s Valuation in Equilibrium](https://delvingbitcoin.org/t/a-game-theoretic-approach-to-bitcoin-s-valuation-in-equilibrium/1547)
- [Using Ark as a channel factory](https://delvingbitcoin.org/t/ark-as-a-channel-factory-compressed-liquidity-management-for-improved-payment-feasibility/2179)
- [What is the importance of running a node?](https://delvingbitcoin.org/t/what-is-the-importance-of-running-a-node/2079)
- [GitLab Backups for Bitcoin Core repository](https://delvingbitcoin.org/t/gitlab-backups-for-bitcoin-core-repository/624/1)
## LND

- [graph: fix graph-cache issue](https://github.com/lightningnetwork/lnd/pull/10378)
- [Implement Onion Messaging (BOLT4) and Support Downstream BOLT12 Features](https://github.com/lightningnetwork/lnd/issues/10220)

## Security

- [Bitcoin Core wallet migration bug](https://bitcoincore.org/en/2026/01/05/wallet-migration-bug/)
- [Blockstream Jade Security Disclosure](https://blog.blockstream.com/jade-security-disclosure/)
- [LND: Infinite Inbox DoS](https://morehouse.github.io/lightning/lnd-infinite-inbox-dos/)
- [An Independent Security Audit of Bitcoin Core](https://brink.dev/blog/2025/11/19/bitcoin-core-security-audit/)

## Otros

- [Quantum Doomsday Clock](https://quantumdoomclock.com/)
- [Cloudflare outage on November 18, 2025](https://blog.cloudflare.com/18-november-2025-outage/)
- [BitMEX research: 64 byte transactions](https://www.bitmex.com/blog/64-Byte-Transactions)

## Releases

- [LND v0.20.0-beta](https://github.com/lightningnetwork/lnd/releases/tag/v0.20.0-beta)
- [LDK v0.2](https://github.com/lightningdevkit/rust-lightning/releases/tag/v0.2)
- [CLN v25.12](https://github.com/ElementsProject/lightning/releases/tag/v25.12)
- [Bitcoin Core v30.1](https://github.com/bitcoin/bitcoin/blob/master/doc/release-notes/release-notes-30.1.md)
- [BTCPay Server 2.3.0](https://github.com/btcpayserver/btcpayserver/releases/tag/v2.3.0)