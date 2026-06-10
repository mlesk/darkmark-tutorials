# Bitcoin Resources

## Knowledge

- [Book: _Mastering Bitcoin, 2nd Edition_ — Andreas M. Antonopoulos (O'Reilly)](https://github.com/bitcoinbook/bitcoinbook)
  The canonical technical deep-dive. Chapters 4–7 cover keys, transactions, and the blockchain end-to-end. Use for: understanding transaction structure, script, UTXO model.
- [Developer Guide: Bitcoin.org Developer Documentation](https://developer.bitcoin.org/devguide/index.html)
  Official protocol-level reference. The [Transactions](https://developer.bitcoin.org/devguide/transactions.html), [P2P Network](https://developer.bitcoin.org/devguide/p2p_network.html), and [Mining](https://developer.bitcoin.org/devguide/mining.html) guides are directly relevant to the transaction lifecycle. Use for: authoritative protocol details, message formats, validation rules.
- [Whitepaper: "Bitcoin: A Peer-to-Peer Electronic Cash System" — Satoshi Nakamoto](https://bitcoin.org/bitcoin.pdf)
  The original 9-page paper. Use for: first principles on the chain-of-hash proof-of-work design. The timestamp server and network sections are still the clearest articulation of the core mechanism.
- [Bitcoin Wiki: Protocol Documentation](https://en.bitcoin.it/wiki/Protocol_documentation)
  Community-maintained reference for message structure, network packets, and transaction encoding. Use for: raw byte-level protocol details.
- [Bitcoin Stack Exchange](https://bitcoin.stackexchange.com/)
  High-signal Q&A for protocol mechanics and edge cases. Use for: resolving specific "how does X actually work" questions.
- [BIPs (Bitcoin Improvement Proposals)](https://github.com/bitcoin/bips)
  The canonical specification repository. BIP 141 (SegWit), BIP 145 (getblocktemplate updates), and BIP 152 (compact blocks) are specifically relevant. Use for: understanding protocol evolution.
- [Optech: Bitcoin Technical Topics](https://bitcoinops.org/en/topics/)
  Concise explainers on mempool policy, replace-by-fee, compact blocks, and other operational topics. Use for: bridging the gap between protocol specs and real-world node behaviour.
- [B10C: Mempool Observations](https://b10c.me/mempool-observations/)
  Data-driven analysis of actual mempool behaviour, transaction ordering policies, and miner selection. Use for: seeing the theory in practice.

## Wisdom (Communities)

- [Bitcoin Stack Exchange](https://bitcoin.stackexchange.com/)
  The best place for detailed technical Q&A. High moderation bar keeps signal high.
- [r/bitcoin](https://reddit.com/r/bitcoin)
  General community discussion. Moderate signal-to-noise; useful for staying current on protocol developments.
- [Bitcoin Development Mailing List](https://lists.linuxfoundation.org/mailman/listinfo/bitcoin-dev)
  Where protocol changes are proposed and discussed. For deep-dive readers only.
