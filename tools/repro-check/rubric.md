# Rubric: is this reproduction package ready to post?

<!--
THIS IS THE PART YOU WRITE. The skill in SKILL.md executes whatever
checks you define here. It ships empty on purpose: the judgment is your
work.

A filled rubric must contain:

1. At least one row in the checks table. Each row needs all four
   columns:
   - Check: a short name (used in the output JSON).
   - Evidence: exactly what to look at, and where in the package. Name
     the part (the claim comment, the repro report's environment
     record, the artifacts read against the issue's description, the
     repo-facts block) or a location from your
     references/evidence-guide.md. "The report" is not a source; "the
     output excerpt read against the error the issue describes" is.
   - Pass condition: a decision rule about the OUTCOME that someone
     else could apply and get your answer. Judge the thing itself (does
     the artifact show the issue's behavior?), never the write-up's
     shape (how many steps it has, how long it is, whether it uses a
     template's headings). Structure-shaped checks are what make
     graders disagree with themselves.
   - Weight: `required` (a fail here holds the package) or `preferred`
     (never changes the verdict).

2. A verdict rule below the table: how the check grades combine into
   accept (ready) or reject (hold), including how `unclear` is
   treated. The verdict space is binary. If you write no rule for
   `unclear`, the skill treats it as fail.

Cover what actually gets bad packages posted. The lecture named the
proof families: the environment is recorded, the steps are complete
and followable, the behavior shown matches the issue (not an adjacent
one), the outcome is stated honestly (an evidenced cannot-reproduce is
a pass, a confident wrong-target is not), and the words respect the
repo's conventions. A rubric that ignores a family will fail eval
packages designed around that family.
-->

## Checks

| Check | Evidence | Pass condition | Weight |
|---|---|---|---|
|  |  |  |  |

| Run environment is stated | The repro report's environment record, read against the repo-facts block / README | The tool and its version are ones the README supports; the OS is one the README lists or doesn't exclude; the toolchain matches the README's; | required |
| Steps are runnable | The run steps in the repro report, read against the environment record | Someone with the same environment could execute the steps as written. Every command is given, and every file or input the steps depend on is pasted or described specifically enough to recreate (name, location, behavior-relevant contents). Steps that state honestly which part of the issue's scenario they did and did not reach still pass. Fails only if the grader can name a specific missing command, file, input, or unstated version that the run depends on. | required |
| Expected and actual behavior | The report's expected and actual output description, read against the issue text | Expected behavior is clearly stated, and the actual behavior described matches what the issue reports, not an adjacent behavior | required |
| Artifact supports the stated outcome | The output excerpt, crash message, or exit code in the repro report, read against the report's stated conclusion and the issue text | The artifact is real output from the stated run and matches what the report says happened. If the report says it reproduced, the artifact shows the specific behavior the issue describes. If the report says it could not reproduce, the artifact matches the report's account of the run, and the report states which of the issue's preconditions or steps it did and did not reach. A could-not-reproduce that openly admits it may not have reached the trigger passes. Fails if the conclusion contradicts the artifact, if the artifact shows an adjacent behavior presented as the issue's, or if a could-not-reproduce claims to have exercised the issue's step when the artifact shows it did not. | required |
| Claim comment is specific and promises only investigation | The claim comment, read against the issue | The claim names the issue it is about (by number, link, or its specific symptom) and says what the author will do next. It promises no fix and no date. Fails only if it is generic, names no issue specifics, or promises a fix or timeline. | required |

| Comments follow the repo's stated policies | The claim and repro comments, read against the repo-facts block / README / CONTRIBUTING and the scope.md house rules | Any comment template or AI-disclosure policy the repo states is followed, including disclosure where required. The repro comment gives its own evidence and does not piggyback ("same as above", "can confirm"). If the repo states no template or disclosure policy, those parts pass. Fails only when a stated policy or house rule is violated, and the grader can name which one. | required |
## Verdict rule

<!-- State how the grades above combine into accept or reject, and how
unclear is treated. Example shape (write your own): "accept if every
required check passes; preferred checks never change the verdict;
unclear counts as fail." -->

Accept if all required checks pass. Reject if any required checks fails. unclear counts as fail.
