# What to improve

Clustered. Quality over new repos.

## 1. Receipts / PegLab / stillpay

**Reality:** Parker has 26 accepted TN10 txs. We have ENGINE_SPEC + a cited pack. Timeout `.sil` that doesn’t lock output value is a trap; don’t copy fee-from-principal on the successor (Luke’s claim path is the pattern to copy).

**Improve:**

- Fill peglab-poc journal: create, pay, timeout, refuse-fake-dollar — **our** txids.
- Fold stillpay-tn10 evidence into that journal. One README table.
- stillpay-mainnet stays gated until that table is green.
- Keep peglab-stp as classroom. Never list tPEG on a till.

**Pushback:** another HTML “Darwin” tab (gramlanepeglab, mixer-concept) does not substitute for an explorer link.

## 2. 402 / Luke / grok heavy

**Reality:** envelope exists. We reviewed it. We have not charged a call.

**Improve:**

- File the Windows issue (grok-heavy-test docs/02) on elldeeone/kaspa-x402.
- One local dApp: `curl` unpaid → 402 with `PAYMENT-REQUIRED` → pay TN10 exact → 200 + txid.
- Do not wrap Ishum in x402 headers “for the catalog.” Different job.
- Point all 402 writeups at grok-heavy-test.

**Pushback:** four report repos in one morning is the same sprawl we criticize in kaspahttp402.

## 3. Ishum / tills

**Reality:** three POS stories (Ishum, kaspa-till, xai-reasoning-3). Only Ishum is the live shape.

**Improve:**

- Default `EnableKUSD` / `EnableUSDT` **off**.
- Mandatory payload match or HD address. Kill claim-any-payment-to-this-address.
- Confirmations: selected-chain depth, not blue-score subtraction.
- README: 10 BPS, not “10 conf ≈ 10 seconds.”
- Archive kaspa-till. Keep xai-reasoning-3 as EUR dual-rail notes only.

**Pushback:** a reserved kUSD rail on the keypad is how a classroom becomes a lie without a depeg button.

## 4. Gramlane / master-file / project-delusional

**Reality:** one principle, three homes.

**Improve:**

- master-file = pins + THINK-BIG orders.
- Archive or README-redirect gramlane and project-delusional to master-file.
- Grams stay mass + WorkCredit. No GRAM token.

## 5. kaspaexplained / Parker overlay

**Reality:** Parker is the referee. STP overlay exists.

**Improve:**

- Don’t duplicate CLAIMS.yml.
- Overlay may add PoW ethos / Kasware-Kastle. Must not silently change status lanes.
- Cite Parker’s TN10 pack; don’t paste his site into mixer-concept as if we ran it.

## 6. KaChat

**Reality:** Silver pushed 14 Sep. STP has three repos, last STP push 11 Sep.

**Improve:**

- `stp-kachat` tracks Silver or says how it differs (one paragraph).
- Archive `kaachat-desktop`. Keep `kachat-test-with-silver` as a test fork, labeled.
- Settlement: native KAS, prefix `kchat:1:pay`. Don’t invent a third covenant family for chat.

**Pushback:** encrypted messaging is not this desk’s 10-year product. Don’t let it eat the timeout journal.

## 7. Names / kns

**Reality:** spec-heavy overlay, indexer FCFS uniqueness, HTTP 402 *shape* on `kns`.

**Improve:**

- One name, one local dApp, one **real** x402 charge (Luke’s envelope).
- Don’t advertise kns 402 as x402 v2.
- Conformance tests in kns-spec that fail if `ipfs`/`peer` keys are missing.

## 8. Node / Windows

**Reality:** guides exist. Good.

**Improve:** keep them ops. Don’t mix node-prompt repos with protocol claims.

## 9. Argent / DK / vProgs

**Reality:** preview / research.

**Improve:** do nothing as product. Revisit only on tag / merge / product testnet as THINK-BIG step 7.
