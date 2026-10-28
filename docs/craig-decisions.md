# Craig decisions

Read this ledger before work in `craig-saves/rwrds-data`.

- Owner: Craig. Entries below are paraphrases of decisions dated 2026-10-28.
- Source: [CS-139](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-139), its original decision list, and its current bot/PostHog amendment recorded at 2026-10-28T07:27:49.906Z (receipt `01M60PGY4J9KFNGWV8R45KT9R1`).
- [Hub canonical ledger](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md) owns cross-section rules. The links below use its planned stable IDs. Publication and live anchors remain unverified in this PR; the Hub coordinator must validate publication before merge.
- Current decisions are binding within their scope. Product decisions below are cross-section reference, not permission to start those products in this repository. This change records decisions only. It does not prove implementation, release, or production acceptance.
- Task links use the route verified from installed BB source. Browser rendering was not verified.

## Record each new decision

1. When Craig, directly or through the CraigSaves bot, gives an instruction, preference, or decision, add an immediate receipt to the owning task.
2. Add the dated decision, affected section, source task, and any superseded decision to this ledger in the same relevant PR flow. Cross-section rules belong in Hub; link them here.
3. Preserve historical receipts. Mark a superseded instruction explicitly. State implementation results only when source evidence supports them.
4. Keep the task receipt current while the PR is pending. The coordinator arranges independent review and final-head checks, then merges without a routine permission question (standing orders 1–4 and 17).

For this documentation rollout, do not touch production data, secrets, DNS, or Coolify. Existing safety limits and correction-round history remain in force. A new head requires new verification. A PR gets at most two failed fix rounds before the order 5 stop and `needs-craig` record; a documentation entry does not reset that count.

<a id="craig-2026-10-28-01"></a>
## 01 — Merge after verification

- Date: 2026-10-28. Scope: cross-section; applies here.
- Decision: Do not ask Craig before routine merge and deployment. Complete review and relevant checks first. The section coordinator merges; children do not merge. Report the actual merged result on [CS-121](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-121).
- Preserve safety boundaries, independent review, final-head verification, and correction-round limits. This decision does not grant production actions to this documentation worker.
- Source: [CS-139](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-139). [Hub decision 01](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md#craig-2026-10-28-01).

<a id="craig-2026-10-28-02"></a>
## 02 — Run workers on Craig's laptop

- Date: 2026-10-28. Scope: cross-section; applies here.
- Decision: New workers and independent reviewers use Craig's laptop, `host_qfx8ucfcm3`, in fresh isolated worktrees. No BB workers on the VPS. One child owns one task and branch (order 12).
- The four Hub script factories remain on the server with scripts and configuration unchanged. This is not a factory migration.
- Sources: [CS-131](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-131), [CS-137](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-137), and the order 12 amendment in [CS-136](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-136), as relayed in the CS-139 brief. [Hub decision 02](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md#craig-2026-10-28-02).

<a id="craig-2026-10-28-03"></a>
## 03 — Fix the cause of data errors

- Date: 2026-10-28. Scope: cross-section; applies here when data work is assigned.
- Decision: When Craig reports a data error, fix the cause in the parser, importer, or grouping logic so the error cannot recur. A correction to one record is insufficient.
- Source: [CS-139](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-139). [Hub decision 03](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md#craig-2026-10-28-03).

<a id="craig-2026-10-28-04"></a>
## 04 — Use existing failure emails

- Date: 2026-10-28. Scope: cross-section; applies here.
- Decision: Craig does not use Slack. Remove existing Slack alert steps and secret references. Do not add Slack alerts. GitHub failure emails are sufficient. This is not permission to send test messages to real users.
- Source: [CC-123](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CC-123), receipt `01M60NCFT2PY4BSPQEJR9CJYJX`, 2026-10-28T07:07:55.587Z. [Hub decision 04](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md#craig-2026-10-28-04).

<a id="craig-2026-10-28-05"></a>
## 05 — Collect user feedback with PostHog Surveys

- Date: 2026-10-28. Scope: all site sections; cross-section product reference here.
- Decision: Build a site-wide feedback loop. Craig's latest choice is PostHog Surveys. Route and group feedback into owning section tasks; track resulting changes and report themes and shipped work on CS-121.
- History: CS-138 first requested a tool comparison. The latest CS-139 relay selects PostHog Surveys. No live survey, configuration, or feedback service is created by this documentation change.
- Sources: [CS-138](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-138) and the current amendment in [CS-139](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-139). [Hub decision 05](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md#craig-2026-10-28-05).

<a id="craig-2026-10-28-06"></a>
## 06 — Make Net worth public entry accessible

- Date: 2026-10-28. Scope: Net worth; cross-section product reference here.
- Decision: Move towards public pages without login. Make `/net-worth` a public, indexable landing page, with its own canonical URL and sign-up/sign-in actions. Keep the Hub sitemap entry. A person's own account and private data remain protected by login and authorization.
- Propose further public pages or tools on CS-121, then build them through the Net worth work flow. This repository receives no Net worth implementation or Hub proxy/navigation assignment.
- History: The current decision supersedes the earlier sitemap-exclusion recommendation. Source receipt `01M60NGXQVRYNW3H1EB9ZZF8HY`, 2026-10-28T07:10:20.923Z. That historical relay named Grok Bot; decision 11 changes the current contact.
- Source: [NW-4](https://craigsaves.getbb.app/plugins/tasks/tasks/task/NW-4). [Hub decision 06](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md#craig-2026-10-28-06).

<a id="craig-2026-10-28-07"></a>
## 07 — Complete the Places repair

- Date: 2026-10-28. Scope: Places lane of CS-98; cross-section product reference here.
- Decision: Find and fix the cause of the navigation bug and all three reported React 418 hydration errors. A diagnosis-only result is insufficient. Use a fresh approach, reproduce with production builds, and add a regression test that fails before the fix. Verify the errors stop in production before reporting repair acceptance.
- History: The 2026-10-28T06:25:35.433Z receipt `01M60JYZ6905XCJZDEJHAB4WVC` records initial PR 66 failure, failed correction round 1 in PR 67, and failed correction round 2 in PR 69. Order 5 stopped that sequence. Preserve these failures and the historical stop.
- Current authority: Craig's later receipt `01M60ND3RRGJV7PJMM71M9VDCA`, 2026-10-28T07:08:16.024Z, authorizes a fresh repair and supersedes that stop for the fresh approach. Technical acceptance remains pending. This receipt does not prove a technical PASS or erase the failed rounds.
- Separate task: [PL-4](https://craigsaves.getbb.app/plugins/tasks/tasks/task/PL-4) belongs to Places. Craig's receipt `01M60RCSQHQASC38F436RS4KA2`, 2026-10-28T08:00:31.477Z, replaces its prior STOP/photo allowance. It authorizes the Places coordinator to implement, merge, and deploy the revised robots.txt policy without further sign-off. This creates no PL-4 work in this repository.
- Source: [CS-98](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-98). [Hub decision 07](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md#craig-2026-10-28-07).

<a id="craig-2026-10-28-08"></a>
## 08 — Show full prices and group Shopping variants

- Date: 2026-10-28. Scope: Shopping; cross-section product reference here.
- Decision: Amazon cards show Full price (RRP) on the price ruler, as Coles cards do. Group flavour, colour, and scent variants into one card when product, retailer, size, and price match. The CraigSaves bot checks the pages daily and records missed groups on ST-139. This assigns no new automation to this worker.
- Sources: [ST-138](https://craigsaves.getbb.app/plugins/tasks/tasks/task/ST-138) and [ST-139](https://craigsaves.getbb.app/plugins/tasks/tasks/task/ST-139), as recorded in CS-139. The Shopping coordinator confirms daily-check ownership in receipt `01M60QRPPHGR4T25CS5TC0PFFS`, 2026-10-28T07:49:33.009Z. [Hub decision 08](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md#craig-2026-10-28-08).

<a id="craig-2026-10-28-09"></a>
## 09 — Correct Card fees, credits, and page groups

- Date: 2026-10-28. Scope: Credit cards; cross-section product reference here.
- Decision: Monthly-fee cards do not also show an annual fee. Keep sign-up bonus credits separate from ongoing credits. Remove duplicate benefits. Fail an import when credits exceed the issuer's headline amount. Group the white cards on `/credit-cards` into sections.
- Sources: [CC-126](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CC-126) and [CC-125](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CC-125), as recorded in CS-139. [Hub decision 09](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md#craig-2026-10-28-09).

<a id="craig-2026-10-28-10"></a>
## 10 — Share one prep bowl per cooking step

- Date: 2026-10-28. Scope: Cooking; cross-section product reference here.
- Decision: Ingredients added in the same step share one prep bowl.
- Source: [COO-47](https://craigsaves.getbb.app/plugins/tasks/tasks/task/COO-47), as recorded in CS-139. [Hub decision 10](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md#craig-2026-10-28-10).

<a id="craig-2026-10-28-11"></a>
## 11 — Route communication through the CraigSaves bot

- Date: 2026-10-28. Scope: cross-section; applies here.
- Decision: From this date, the CraigSaves bot replaces Grok Bot as Craig's single contact. It handles factory/coordinator communication. Reports remain on [CS-121](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-121), not retired chief threads. Do not message or notify retired chiefs.
- History: This supersedes only Grok Bot's current-contact role, including that wording in standing order 18. Preserve historical relay names and [CS-135](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-135) receipts. CS-121 is an inbox, not a chief-thread registry.
- Source: Current direct relay recorded in [CS-139](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-139). [Hub decision 11](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md#craig-2026-10-28-11).

<a id="craig-2026-10-28-12"></a>
## 12 — Record the scoped Woolworths recovery decision

- Date: 2026-10-28, 6:48pm Brisbane. Scope: Shopping recovery; cross-section reference here.
- Decision: Craig authorizes the existing Shopping recovery owner to re-check 2,344 Woolworths items now with a one-off laptop script. Read and update prices only. First run a dry-run and report counts. Send no notifications, delete nothing, and never expose dotenv values. Report the final Buyable count against about 26,500 before the outage, plus remaining missing items and reasons.
- This repository starts no script or data action. The Hub record retains the scoped recovery authority.
- Source: [CS-139](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-139), receipt `01M60W7P2SRY5A5EMCNR9BK36E`, 2026-10-28T09:07:38.201Z, and the original user turns in Shopping recovery thread `thr_wnkxny5pdr`. [Hub decision 12](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md#craig-2026-10-28-12).

<a id="craig-2026-10-28-13"></a>
## 13 — Complete approved documentation through normal review

- Date: 2026-10-28, 7:06pm Brisbane. Scope: approved documentation PRs; applies here as relayed by Hub.
- Decision: Proceed with approved AGENTS, CLAUDE, and documentation changes through pstack without another approval request. Complete normal review, tests, coordinator merge, and reporting. If legitimate edits or commits are blocked, repair the worker environment narrowly on the laptop. Use supported permission mechanisms and report the exact change.
- History: This supersedes the 6:24pm request for another approval card for these already approved documents. Preserve failed attempts and any automatic approval denial. It does not permit disabled checks or unrestricted access. Do not touch secrets, dotenv values, Coolify, DNS, or production data.
- Source: [CS-139](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-139), receipt `01M60W7P2SRY5A5EMCNR9BK36E`, 2026-10-28T09:07:38.201Z, and the original user turns in `thr_wnkxny5pdr`. Hub applies this authority to legitimate documentation preparation in this rollout. [Hub decision 13](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md#craig-2026-10-28-13).

<a id="craig-2026-10-28-14"></a>
## 14 — Record the scoped Shopping documentation approval

- Date: 2026-10-28. Scope: Shopping documentation; cross-section reference here. The earlier approval is partly superseded. The exact time of the later instruction is unresolved.
- Current decision: PR 645 contains only `docs/supermarket-catalogue.md`, with the Run locally table. Craig dropped the AGENTS import-note and CLAUDE job-description edits from that PR. The Shopping coordinator owns review and merge.
- After that merge, the original Shopping worker must discard its uncommitted documentation edits and must not open another documentation PR. This instruction assigns no action to another owner.
- History: At 6:24pm Brisbane, amended at 7:06pm, Craig approved the short AGENTS local-scripts note, the catalogue Run locally table, and corrected CLAUDE job descriptions with the catalogue link. The earlier Shopping procedures required dry-run and counts before repair or backfill. Never print, log, or copy dotenv values.
- History: The 6:24pm description called `cspecials` half-price. The 7:06pm correction says every Coles special. `cimport` is the full Coles catalogue. `wimport` is the full Woolworths catalogue, including recovery. No further `wspecials` meaning is established here.
- The separate CS-139 mandatory ledger-read, decision-capture, and coordinator-only-merge pointers in AGENTS and CLAUDE remain required. This entry grants no blanket production authority, workflow edit, or operational action here.
- Sources: The original approval is recorded in [CS-139](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-139), receipt `01M60W7P2SRY5A5EMCNR9BK36E`, 2026-10-28T09:07:38.201Z. The later direct User block in `thr_wnkxny5pdr` limits the scope to PR 645; Hub preserved it in `CS139-decision14-supersession-source.json`. [Hub decision 14](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md#craig-2026-10-28-14).

<a id="craig-2026-10-28-15"></a>
## 15 — Record the specific Shopping deployment timeout decision

- Date: 2026-10-28, 6:24pm Brisbane. Scope: one Shopping Coolify deployment timeout; cross-section reference here.
- Decision: Ignore that one-off `api.github.com` timeout unless it recurs. Create no automatic retry job, API token, or support report. If it recurs, record it on CS-121 and flag the CraigSaves bot.
- This is not a waiver for other deployment failures. This repository starts no deployment or Coolify action.
- Source: [CS-139](https://craigsaves.getbb.app/plugins/tasks/tasks/task/CS-139), receipt `01M60W7P2SRY5A5EMCNR9BK36E`, 2026-10-28T09:07:38.201Z, and the original user turns in `thr_wnkxny5pdr`. [Hub decision 15](https://github.com/craig-saves/craigsaves/blob/main/docs/craig-decisions.md#craig-2026-10-28-15).
