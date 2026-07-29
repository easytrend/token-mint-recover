# Claim-LostSol

> Recover the excess SOL locked in your Solana token mint — non-custodially, in a single on-chain transaction.

**Claim-LostSol** is a browser-based tool powered by [SIMD-0266](https://github.com/solana-foundation/solana-improvement-documents/pull/266) (`withdraw_excess_lamports`) that lets Solana token mint creators reclaim surplus SOL that was previously stuck above the rent-exempt minimum.

---

## Features

- 🔒 **Non-custodial** — Your keys never leave your device
- ⚡ **Single atomic transaction** — Withdrawal + fee in one verifiable on-chain tx
- 🔍 **Live on-chain scan** — See exact recoverable amount before signing
- 🪙 **Token Program & Token-2022** — Supports both standards
- 📁 **Renounced mints** — Recover using original keypair (read locally, never uploaded)
- 🌐 **Works on mainnet** — Proven with real SOL on real mints

---

## How It Works

| Step | Description |
|------|-------------|
| 1️⃣ Scan | Paste a mint address or connect your wallet |
| 2️⃣ View | See exact recoverable SOL (net of fees) |
| 3️⃣ Verify | Confirm recovery path — active authority or original mint keypair |
| 4️⃣ Sign | Approve one transaction in your wallet |

---

## Security

- We will **never** ask for your seed phrase
- Keypair files are read **locally in-browser** and never uploaded
- Every transaction is verifiable on any Solana explorer

---

## Tech Stack

- Vanilla HTML / CSS / JavaScript (no framework)
- SIMD-0266 `withdraw_excess_lamports` instruction
- Solana RPC for on-chain data

---

## License

MIT
