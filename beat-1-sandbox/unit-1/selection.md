# Unit 1 — Issue Selection

Path: `beat-1-sandbox/unit-1/selection.md`

Record of the issue carried into Unit 2, and of the evaluation runs that produced
`eval-run.txt`. This file is graded at the path above; a copy kept anywhere else in
the repository is not read.

Complete every labelled field below. Each is graded on its own; content placed under the
wrong label is not graded.

---

## Selected issue

**Issue link**
https://github.com/codepath/pathreview-ai301-fa26-s1/issues/63

**Verdict output**

[Your skill's live-mode output for this issue, pasted verbatim and ending with the
fenced JSON verdict block. A summary does not satisfy this field.]

**The verdict must record `accept` for this issue.** Choose an issue your own skill
accepts. If your skill rejects every candidate you try, that is a signal about your
rubric rather than about the issues: revise it and re-run — retries are unlimited and a
partial re-run costs about $0.20 — or run the skill on different candidates. Output
recording `reject` for the issue you chose earns no credit for this field.

```
  {
    "item": "https://github.com/codepath/pathreview-ai301-fa26-s1/issues/63",
    "checks": [
      {"name": "no-policy-ban", "grade": "pass", "evidence": "docs/CONTRIBUTING.md covers branches, commits, CI, style, tests and is entirely silent on AI use — no ban."},
      {"name": "Community alive", "grade": "pass", "evidence": "Newest main commit 'chore: track five more manifest entries against the tracker' dated Sep 16, 2026 — 6 days before today (2026-09-22)."},
      {"name": "Repo in use", "grade": "pass", "evidence": "No releases published, but last push Sep 16, 2026 is well within 6 months."},
      {"name": "Scope fits you", "grade": "pass", "evidence": "Issue body has no 'Operating system' field (fields are Relevant Files, Estimated Effort, repro command)."},
      {"name": "Issue is unclaimed", "grade": "pass", "evidence": "Assignees: None; Development box: 'No branches or pull requests'."}
    ],
    "verdict": "accept"
  },
```

---

## Eval iterations

Quote source text directly in each field below. Paraphrase does not satisfy them.

**Run history**

[The agreement score of each run you did, in order. A single run is a complete answer if
only one run occurred. **The last score in your list must match the agreement line in the
`eval-run.txt` you committed** — that file is the record of your final run.]

Run 1: 9/20
Run 2: 18/20

**Issue analysis**

[One scored issue, identified by id (`issue-01` through `issue-20`; the `calib-`
issues are not scored). State your rubric's decision, the gold label, and the
reasoning that produced your rubric's result.]

issue-04:  Gold accept  verdict: accept  

**Check rationale**

[One check from the `rubric.md` uploaded to `tools/issue-select/`, quoted as it is
currently written, with the reasoning behind its current form.]

**Trade-offs**

[What the quoted check gives up. Any one of these is a complete answer: an issue whose
result it changes, a canary you re-ran with `--only`, a case you accept it will miss, or a
stated reason nothing changed elsewhere. "Nothing changed, and here is how I know" earns
the point in full when the reason follows.]

---

## Selection rationale

Graded on whether all three are answered, in your own words. Not on how good the
reasoning is, and not on length — a short honest answer to each earns the full marks.
This is also the basis for the claim comment you write in Unit 2.

**Selection rationale**

[Answer all three:

1. The issue's fit to your interests and to the time available.
2. What the verdict identified correctly, and what you weighed that the rubric could
   not.
3. The anticipated difficulty in claiming it.]

---

Related paths: `eval-run.txt` in this directory; your skill's files in
`tools/issue-select/`.
