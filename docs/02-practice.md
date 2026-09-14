# Best practice

Desk law. Kill-if means stop the line.

## Do

1. **Read the pin before you clone.** silverc v1.0.0 `3ed9733`, rusty-kaspa v2.0.1, TN10, kaspa-x402 v1.0.0-rc.1, kaspaexplained.com/status.
2. **Prove on explorer.** A README without our txids is ENGINE_SPEC. Allowed as a spec. Forbidden as a victory lap.
3. **Bind Luke’s envelope** for anything that charges a call. Exact `standard-native` first. Batch is capital lock + signed ceiling T. Don’t pre-sign T beyond delivered work.
4. **Lock value in script.** `validateOutputState` does not lock amount. `require(tx.outputs[i].value == expected)` on every continuation. Luke’s claim path does this. Copy that, not `pragma ^0.1.0`.
5. **Own UTXO only.** Foreign `readInputState` is the 42-byte class. `#234` closed unmerged.
6. **Skip split-tuple syntax** until `#250` merges. `.0` / `.1` if you must.
7. **Measure compute budget** by TN10 rejection (`#243`). Don’t invent one.
8. **Wallets:** QR, `kaspa:` URI, paste txid. In-page inject = Kasware or Kastle. Never ask for a seed.
9. **Names:** official KNS inscriptions for uniqueness-as-indexer. `kns://` overlay locates; Kaspa settles; the machine runs. Uniqueness is still FCFS — say so.
10. **Chat:** Silver is upstream. One STP fork. Pay prefix `kchat:1:pay` (not `payunit`).
11. **Reports:** grok-heavy-test is the 402 pass. Don’t spawn a new writeup repo per thought.
12. **Monday tripwire:** fail if compiler tag, x402 tag, reward step, or `/status` moved and the freeze didn’t.

## Do not

- Call HTTP 402 “x402”
- Call k402 / KCC-0402 “Kaspa’s x402”
- Invent a fourth envelope
- List tPEG or kUSD as money
- Mint GRAM as KCC-20 (grams are mass)
- Use TN12 for new Toccata work
- Enable `allowMainnet` on kaspa-x402
- Ship Argent ICC before a tag + the two missing rules compile
- Treat `accepted` as irreversible
- Treat 10 BPS as 100 BPS
- Treat DAGKnight as consensus
- Fork kaspaexplained.com
- Default-on USDT on a Kaspa till
- Paste a seed into a website
- Wait for vProgs / KCC-20 Final / a Kaspa dollar before filling the timeout journal

## Naming

| Say | Don’t say |
| --- | --- |
| x402 v2 binding (Luke, RC.1, TN10) | “Kaspa has x402” |
| HTTP 402 | x402 (unless the headers are there) |
| till / POS | payment protocol |
| classroom that depegs | stablecoin |
| 1 sompi receipt | USD |
| overlay `kns://` | official KNS / new chain |
| STP KaChat fork | the chat network |

## Git hygiene

- One job per repo. If two READMEs say the same essay, archive one.
- README first sentence = honest label (testnet / draft / classroom / not money).
- No `127.0.0.1` as if it were a public dApp without the disclaimer.
- `.sil` files: `pragma` matching v1.0.0, or a comment that the fixture compiler commit is the pin.
- Don’t open a new STP-KAS repo to store a prompt.
