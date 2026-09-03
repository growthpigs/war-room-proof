# War Room · proof of work

Daily snapshot of the private repository behind [app.thewarroom.ai](https://app.thewarroom.ai), a political intelligence platform designed, built and operated by one person, [Roderic Andrews](https://rodericandrews.com).

The repository is private because it is a client's product. This one is public so the numbers can be checked: every commit here is timestamped by GitHub, and `history/` keeps one file per day.

| As of 2026-09-03 | |
|---|---|
| Merged pull requests since 2025-10-12 | **7485** |
| Merged in the last 30 days | **2352** |
| Test files on `main` | **2083** |
| Database migrations | **237** |

How it is produced: [`proof-snapshot.mjs`](https://github.com/growthpigs/personal-brand/blob/main/site/scripts/proof-snapshot.mjs) runs `gh api search/issues` against the repository and `git ls-tree` on its `main` branch, then writes `proof.json`. The query strings ship inside the JSON. Nothing is typed by hand.

Read it rendered at [rodericandrews.com/proof](https://rodericandrews.com/proof).
