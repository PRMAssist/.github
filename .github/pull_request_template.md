<!-- See https://github.com/PRMAssist/prmassist-infrastructure/blob/master/docs/contributing.md. Don't request a review until every box below is ticked. -->

## What and why
<!-- What changes, and the problem it solves. -->

## How I tested it
<!-- The commands you ran and their output. "Should work" is not a test plan. -->

<!--
FRONT END (web, app, admin or portal UI): also required. Delete this block if the PR changes no UI.
See https://github.com/PRMAssist/prmassist-infrastructure/blob/master/docs/contributing.md#front-end-evidence. Test data only, never real people.
-->
**Screenshots** (before / after for changed UI; empty, loading and error states):

**Screen recording** of the main flow (drag the file in):

**Ran on:** <!-- browser + viewport, or device/emulator + OS version -->

## Related PRs and merge order
<!-- Other repos in this feature, and which merges first. "None" if standalone. -->

## Breaking / contract changes
<!-- API request/response shapes, env vars, schema refs. "None" if none. Mark the title with `!` if breaking. -->

## AI review
<!--
Run an AI code review (default: Claude Code `/code-review <this PR>`) AFTER your last code change.
List EVERY finding. Rejected needs a specific reason; deferred needs a tracking issue/PR.
See https://github.com/PRMAssist/prmassist-infrastructure/blob/master/docs/contributing.md#ai-code-review.
-->

**Tool:** <!-- e.g. Claude Code /code-review -->  **Ran on commit:** <!-- sha -->

| # | Finding | Disposition | Commit / reason / tracking |
|---|---|---|---|
| 1 |  | Fixed / Rejected / Deferred |  |

## What I'm unsure about
<!-- Anything you want the reviewer to look at closely. -->

---

- [ ] **Light route**: docs only, or 20 lines or fewer of comments, copy or config values with no logic. Tick it to skip the AI review and front-end evidence ([rules](https://github.com/PRMAssist/prmassist-infrastructure/blob/master/docs/contributing.md#light-route)).

- [ ] I have run this and pasted the output above
- [ ] Front end only: screenshots and a screen recording are above, using test data
- [ ] CI is green, and this PR targets `master` with no conflicts
- [ ] I have read my own diff, every line, and can explain each change
- [ ] An AI code review ran on the final commit, and every finding above has a disposition
- [ ] The description matches the code
- [ ] No personal data in code, fixtures, logs or this description
