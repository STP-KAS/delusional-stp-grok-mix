# Who in core — seek help, don’t spam

“Core” is not a legal title. Yonatan’s rough list (30 Apr 2025): michaelsutton, hashdag, coderofstuff_, someone235, freshair08, biryukovmaxim, reshmem, aspect, tiram88, elichai, tmrlvi, D-Stacks. Inspect kaspanet + research.kas.pa.

This desk **never DMs you** as a brand promise on the master file. If you ask, ask **one hole**, in public if you can (issue / Kas-Smiths / R&D observer), with a txid or a failing test.

---

## Ask these people for these holes

| Hole | Who | Channel | Bring |
| --- | --- | --- | --- |
| kaspa-x402 Windows CRLF / 0600 / fsync | **Luke / @elldeeone** | GitHub issue on kaspa-x402 (paste grok-heavy-test docs/02) | hashes, OS, Node 24 |
| Binding questions, CAIP #193, batch claim/refund race | **Luke** | issue or Kas-Smiths x402 thread | don’t ask him to bless Ishum |
| `#243` compute budget, `#250` split tuples, `#234` foreign state, `pragma ^0.1.0` vs v1.0.0 | **Ori Newman / someone235** | silverscript issues (already open) | don’t open a new “please ship my dapp” |
| TN10 vs TN12, Toccata tooling, “don’t use TN12” | **IzioDev** | already on record 6 Jun 2026 — **cite, don’t re-ask** | new evidence only |
| KCC-0012 wallet provider | **saefstroem** + Izio reviewing | kccs#24 | a public implementation, not a wish |
| Partitioned / parallel state (not a dollar) | **Michael Sutton** | only a precise question; his 11 Sep post is a hypothesis, essay **not written** | one UTXO design, not “please design our DEX” |
| Receipt unit, status lanes, CLAIMS.yml | **Parker / parker2017code** | his repo | cite; overlay; don’t fork the site |
| KaChat pay prefix, handshake | **KaspaSilver** | their desktop repo | one STP fork, changelog vs upstream |
| Channel lock primitive | **Kali123411** | k402 / kccs#4 | credit; not x402 v2 |
| DK e2e / confirmation policy | **FreshAir08** / rusty #1127 | only if you have a failing test | not a product pitch |
| KIP-21 lanes | **biryukovmaxim** | if you actually use subnetwork_id | grams are mass, not a token |
| Node / archival | rusty-kaspa issues, kaspa.stream | Xai.Kaspa.node is a prompt, not core | |

---

## Do not ask

| Person | Don’t |
| --- | --- |
| **hashdag** | 100 BPS as a spec, Kaspa-dollar, GDP of empty blocks as a raise |
| **Sutton** | “is our till DeFi?” — no. Productize Argent before a tag — no |
| **Ori** | merge a random STP `.sil` as language law |
| **Luke** | USDC on his binding, mainnet `allowMainnet`, “please add kUSD” |
| **Whole core Telegram** | dump 30 GitHub links and ask “thoughts?” |
| **Kaspa global / unchained** | they are not a spec |

---

## How to ask (practice)

1. One issue, one repo, one failing command or one txid.
2. Label testnet vs mainnet vs draft.
3. Link grok-heavy-test or master-file pin so they don’t re-explain HTTP 402 vs x402.
4. If the hole is already an open issue (`#243`, `#250`, kccs#4, namespaces#193), **comment evidence**, don’t clone the issue.
5. Observer-first in t.me/kasparnd. Recaps: kaspa.news.

---

## This desk’s side of the bargain

If we ping Luke, we file the Windows repro instead of only DMing a novel.

If we ping Ori, we are on v1.0.0 and we are not using split tuples.

If we ping Parker, we cite his pack and we have started *our* journal.

If we ping Silver, we have one fork, not three.
