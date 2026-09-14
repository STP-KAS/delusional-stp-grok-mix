# Delusional STP Grok mix

**Now with Luke’s repo and grok heavy.** Not Kaspa core. Not a KIP. Not a dollar. Not an audit.

This is the desk operating system after the 14 Sep 2026 pass:

| Piece | What |
| --- | --- |
| Project delusional / STP | [kaspa-master-file](https://github.com/STP-KAS/kaspa-master-file) — pins, kill-ifs, two tracks |
| Luke | [elldeeone/kaspa-x402](https://github.com/elldeeone/kaspa-x402) `v1.0.0-rc.1` — the x402 **v2** envelope |
| Grok heavy | [STP-KAS/grok-heavy-test](https://github.com/STP-KAS/grok-heavy-test) — send Luke [docs/00-for-luke.md](https://github.com/STP-KAS/grok-heavy-test/blob/main/docs/00-for-luke.md) |
| This mix | Best practice, advice, steps, who in core, capital, pushback — over **every** STP-KAS repo + Parker + PegLab + Gramlane + KaChat + kaspaexplained |

Date: **2026-09-14**. Full authority: pick a path, kill the rest, say when money is missing, do not flatter the catalog.

---

## How to read

| Want | Open |
| --- | --- |
| **Send Luke** | [grok-heavy-test / docs/00-for-luke.md](https://github.com/STP-KAS/grok-heavy-test/blob/main/docs/00-for-luke.md) |
| One screen of orders (this desk) | this README, [Verdict](#verdict) then [Steps](#steps) |
| Every GitHub, honest label | [docs/01-portfolio.md](docs/01-portfolio.md) |
| Best practice (do / do not) | [docs/02-practice.md](docs/02-practice.md) |
| What to improve, repo by cluster | [docs/03-improve.md](docs/03-improve.md) |
| Who in core to ask (and not) | [docs/04-core.md](docs/04-core.md) |
| Capital: when yes, when no | [docs/05-capital.md](docs/05-capital.md) |

---

## Verdict

The map is honest. The catalog is **too big**. The empty box is still the same:

**No STP TN10 timeout txids. No local endpoint that returns x402, takes KAS, and comes back 200 + txid.**

Thirty public repos will not fill that box. Parker already journaled receipts on TN10. Luke already has an RC binding. PegLab already teaches depeg. This desk’s job is **one covenant that cannot lie about value**, **one 402 that charges**, **one till that does not pretend to be a dollar**. Everything else is a side tab or a report.

Luke’s repo is the envelope. Grok heavy is the proof we actually ran it. Master file is the pin list. **This mix is the orders.**

---

## The mix in three sentences

1. **Luke / kaspa-x402** — real x402 v2 binding for native KAS. Bind it. TN10 only. Not v1. Not mainnet. Windows `npm test` fails until `.gitattributes`. Full: [grok-heavy-test](https://github.com/STP-KAS/grok-heavy-test).
2. **Parker / kaspaexplained** — 1 receipt = 1 locked sompi. Status lanes. Cite; do not fork the site into a second truth. Overlay [kaspaexplained-delusional-stp](https://github.com/STP-KAS/kaspaexplained-delusional-stp) stays an overlay.
3. **PegLab / Gramlane / Ishum / KaChat** — classroom that **will depeg**; grams are mass not a token; Ishum is a **till not x402**; KaChat is Silver’s product, STP has too many copies.

---

## Portfolio, compressed

Honest status of the public GitHub. Detail in [docs/01-portfolio.md](docs/01-portfolio.md).

### Keep (Track 0 — public goods)

| Repo | Job | Honest |
| --- | --- | --- |
| [kaspa-master-file](https://github.com/STP-KAS/kaspa-master-file) | Pin list | **Law of the desk.** Freeze table must not lag tags. |
| [grok-heavy-test](https://github.com/STP-KAS/grok-heavy-test) | Agent pass of Luke | **Send this to Luke.** |
| [kns-spec](https://github.com/STP-KAS/kns-spec) | Overlay + conformance | Spec-heavy. One name must actually publish. |
| [windows-p2p-node-guide](https://github.com/STP-KAS/windows-p2p-node-guide) / [Xai.Kaspa.node](https://github.com/STP-KAS/Xai.Kaspa.node) | Run a node | Useful. Not a product. |

### Keep (Track 1 — software that takes KAS)

| Repo | Job | Honest |
| --- | --- | --- |
| [peglab-poc](https://github.com/STP-KAS/peglab-poc) | Receipt PoC | **ENGINE_SPEC until our TN10 txids.** Next empty box. |
| [peglab-stp](https://github.com/STP-KAS/peglab-stp) | Depeg classroom | **WILL DEPEG.** Not money. Keep. |
| [ishum](https://github.com/STP-KAS/ishum) | POS till | Live rail = KAS. kUSD/USDT seats are a trap. Not x402. |
| [stillpay-tn10](https://github.com/STP-KAS/stillpay-tn10) | Timeout escrow TN10 | Merge into peglab-poc or journal txids. Two stillpays is drift. |

### Cite, do not become

| Repo | Job | Honest |
| --- | --- | --- |
| [elldeeone/kaspa-x402](https://github.com/elldeeone/kaspa-x402) | x402 v2 binding | **Bind. Do not fork.** RC.1. |
| [parker2017code/kaspa-explained](https://github.com/parker2017code/kaspa-explained) | kaspaexplained.com | **Referee + receipt unit.** Do not clone the site. |
| [KaspaSilver/KaChat-Desktop](https://github.com/KaspaSilver/KaChat-Desktop) | Chat | **Upstream.** STP has three copies. Pick one. |

### Freeze or archive (side tabs)

`gramlane` (ideas already in master-file) · `gramlanepeglab` (8 KB HTML battletest) · `mixer-concept` · `project-delusional` · `kaspa-till` (Ishum replaced it) · `xai-reasoning-3` (EUR till; keep notes, don’t run a second POS) · `kaachat-desktop` + `kachat-test-with-silver` (collapse into `stp-kachat` vs Silver) · `dagknight-test-grok` (not consensus; don’t productize) · `argent-xai` (no Argent tag) · `ok` · `sixpack.wtf` (personal) · today’s short 402 twins (`x402-vs-grok`, `x402-ishum`, `402-is-not-x402`) — **point at grok-heavy-test**, don’t grow a fourth writeup.

**Kill-if you ship them as product:** tPEG as money · GRAM as KCC-20 · fourth 402 envelope · TN12 · seed-paste UX · `allowMainnet` on kaspa-x402 · kUSD with no capital.

---

## Best practice (desk law)

1. **One map.** `kaspa-master-file` is the pin. Do not invent a fifth freeze copy.
2. **One envelope.** `elldeeone/kaspa-x402` `v1.0.0-rc.1`. Steal k402’s *lock*. Never call k402 “x402.” Never “adopted KCC-0402.”
3. **One unit.** 1 receipt = 1 sompi. Parker won. Do not re-litigate.
4. **One classroom.** PegLab **will depeg**. That is the lesson. Not a peg.
5. **One till.** Ishum (or stillpay), not four POS repos. Quote fiat if you must. Settle **KAS**. Default kUSD/USDT **off**.
6. **One chat fork.** Silver is upstream. `stp-kachat` is the STP build. Delete or archive the extras.
7. **Compiler pin.** SilverScript **v1.0.0** `3ed9733`. `pragma ^0.1.0` is a footgun. `#234` `#243` `#249` still holes. `require(tx.outputs[i].value == …)` on every continuation.
8. **TN10 only.** IzioDev, 6 Jun 2026: do not use TN12 for Toccata product work.
9. **Explorer or it didn’t happen.** ENGINE_SPEC without our txids is fanfic. Cite Parker; fill *our* journal.
10. **No seed in the page.** QR / `kaspa:` URI / paste txid. Inject = Kasware or Kastle until KCC-0012 has a public implementation.
11. **HTTP 402 ≠ x402.** Say the status code when you mean the status code.
12. **Monday job fails closed** if compiler tag, kaspa-x402 tag, reward step, or `/status` disagree with the freeze.

Full: [docs/02-practice.md](docs/02-practice.md)

---

## Steps

Do in order. Skip only if the **done check** is already green. Kill-if → stop.

| # | Do | Done when |
| --- | --- | --- |
| 0 | Pin: silverc v1.0.0, rusty **v2.0.1**, TN10, kaspa-x402 **RC.1**, referee kaspaexplained.com/status | Every STP `.sil` names v1.0.0. No TN12. |
| 1 | One own-UTXO covenant. `validateOutputState` + **`require(value)`**. No foreign `readInputState`. No split tuples. | TN10 txid spends and recreates with value invariant. |
| 2 | Timeout journal in peglab-poc: create, pay, timeout, refuse-fake-dollar | README lists **our** explorer links. Dollars 0–0. |
| 3 | Bind kaspa-x402. One local URL → 402 → pay TN10 → 200 + txid | `curl` proves it. No USDC. |
| 4 | Ishum: KAS only on the keypad. kUSD/USDT default off. Fix 1 BPS leftover. Selected-chain conf, not blue-score delta. | A second machine hosts it. Desk holds 0. |
| 5 | One KNS name that opens a local paid dApp. No seed. | Stranger with Kasware/Kastle pays, gets a receipt. |
| 6 | Collapse GitHub: archive duplicates. Point 402 writeups at grok-heavy-test. | Catalog ≤ the keep tables above. |
| 7 | Only then: Argent if tagged; KCC-20 if not Draft; vProgs if product testnet. | Not this week. |

---

## Who in core (short)

Do not DM the whole “rough core” list with a product pitch. Ask the person who owns the hole.

| Ask | Who | Do not ask them |
| --- | --- | --- |
| x402 envelope, Windows repro, CAIP | **@elldeeone** / Luke | To bless a till or a dollar |
| Compiler `#243` `#250` `#234`, pragma vs v1.0.0 | **Ori / someone235** | To review your dapp marketing |
| TN10 vs TN12, wallet provider KCC-0012 | **IzioDev**, **saefstroem** | For a “please merge our POS” |
| Partitioned state, not a dollar | **Sutton** — only with a precise question | To productize Argent before a tag |
| Receipts, status lanes, “wTestUSD cannot buy crops” | **Parker** | To become kaspaexplained |
| KaChat handshake / prefix | **KaspaSilver** | To maintain three STP forks |
| k402 lock (credit them) | **Kali123411** | To call it x402 v2 |
| DK tests only | FreshAir / dagknight PRs | To ship DK as this desk’s product |
| Founder research | hashdag | 100 BPS, GDP, “Kaspa dollar” |

Yonatan’s rough core list is **not a support desk**. Full: [docs/04-core.md](docs/04-core.md)

---

## Capital — honest

| Thing | Capital? |
| --- | --- |
| Track 0 map, grok reports, kns-spec | **No.** Time and a GitHub. |
| Track 1 till (Ishum, stillpay) | **No VC.** Hardware signer + a shop that wants KAS. Desk keeps 0. |
| TN10 journals | **Faucet tKAS.** Not money. |
| Binding kaspa-x402 on TN10 | **No.** Clone, pay toy coins. |
| Mainnet kaspa-x402 | **Not yet.** Luke’s gates are open. Don’t put production KAS in it. |
| kUSD / “Kaspa dollar” | **Yes, and don’t.** Reserves, issuer, law (MiCA/GENIUS). This desk is not Circle. Dollars stay 0–0. |
| USDT guest rail | **No capital, worse.** You import a freeze king onto the keypad. Skip for dapps. |
| Public rusty-kaspa node | **Yes, modest.** Disk, inbound 16111, electricity. Not a token raise. |
| KaChat as a company | **If you want a company.** Otherwise stay a test fork of Silver. Don’t pretend three repos are a network. |

Fill is not a business. The jar is not Nakamoto. If you need a raise to pretend a peg, you are on the wrong track.

Full: [docs/05-capital.md](docs/05-capital.md)

---

## Pushback (real)

- **Publishing is not shipping.** Thirty repos, 0 stars, empty timeout journal.
- **ENGINE_SPEC is fanfic** until *our* TN10 txids exist. Citing Parker is allowed. Wearing Parker is not.
- **RC.1 is not v1.** Grok heavy already said it. Don’t tell Discord “Kaspa has x402.”
- **Ishum + kUSD on the keypad** fights the master-file principle you wrote yourself.
- **Three KaChats** is not encryption research. It is git sprawl.
- **gramlane vs master-file vs project-delusional** is the same essay three times.
- **Sutton asked a DeFi question.** That is not a license to mint a dollar or a DEX.
- **Luke asked agents to break kaspa-x402.** We did (Windows). File the issue. Then go fill the timeout journal. That is the mix: his envelope, our empty box.

---

## Links to send

| Send | URL |
| --- | --- |
| This mix | https://github.com/STP-KAS/delusional-stp-grok-mix |
| Grok heavy (send Luke this page) | https://github.com/STP-KAS/grok-heavy-test/blob/main/docs/00-for-luke.md |
| Grok heavy (repo) | https://github.com/STP-KAS/grok-heavy-test |
| Luke | https://github.com/elldeeone/kaspa-x402 |
| Pins | https://github.com/STP-KAS/kaspa-master-file |
| Parker | https://github.com/parker2017code/kaspa-explained |
| PegLab classroom | https://github.com/STP-KAS/peglab-stp |
| Receipt PoC | https://github.com/STP-KAS/peglab-poc |
| Ishum till | https://github.com/STP-KAS/ishum |
| KaChat upstream | https://github.com/KaspaSilver/KaChat-Desktop |
