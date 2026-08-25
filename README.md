# breakfast-fixtures

> [!WARNING]
> Frozen fixtures for the [breakfast](https://github.com/mrsixw/breakfast)
> end-to-end test suite. **Do not modify anything in this repository** — not the
> pull requests, their titles, their labels, or their states.
>
> Changing anything here breaks CI on `mrsixw/breakfast`. See
> `docs/design/testing.md` in that repository for the inventory the tests assert
> against and how to rebuild this repo from scratch.

The pull requests below are asserted by exact count in
`tests/e2e/features/pr_listing.feature`.

| # | Title | State | Draft | Labels |
| --- | --- | --- | --- | --- |
| 1 | Open PR with no labels | open | no | — |
| 2 | Open PR labelled bug | open | no | `bug` |
| 3 | Open PR labelled enhancement | open | no | `enhancement` |
| 4 | Open PR with two labels | open | no | `bug`, `wip` |
| 5 | Draft PR awaiting work | open | yes | — |
| 6 | Second draft PR | open | yes | `enhancement` |
| 7 | Closed without merging | closed | no | — |
| 8 | Merged fixture PR | merged | no | — |
