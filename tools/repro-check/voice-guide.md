# Voice guide: how I talk upstream

## Who I am in threads

I'm a recent CS graduate (Fall 2025) with C, C++, JavaScript, Java, Python, Bash, and SQL experience, picking up my first upstream issues in Path Review. I break problems into small steps and report what I actually observed, so readers can expect a claim first, then a repro report with my environment and output.

## Rules I write by

### Rule: Promise the investigation, never a fix or a date

A claim says what I'll look into next, not that I'll fix it or by when.

- Wrong: "Hi!! I'll fix this by tomorrow, promise! Please assign me!"
- Right: "I'd like to take this one. Next I'll try to reproduce it and post a repro report here."

### Rule: Name the version, promise the check, don't assert the result

Before I've run anything, I name the version and behavior the issue reports and say I'll test it. I don't claim it's confirmed.

- Wrong: "Confirmed, string output is ignored on v3.10.0, exactly as described."
- Right: "The issue reports string output being ignored on v3.10.0. I'll try to reproduce that and post my environment and output."

### Rule: Plain sentences, no hype

One or two direct sentences. No filler praise, no stacked exclamation points.

- Wrong: "Amazing project!! Super excited to dive into this!!"
- Right: "I'm taking this issue and will post a repro report."

### Rule: Own proof, own words

Never piggyback on someone else's repro.

- Wrong: "Same as above, can confirm."
- Right: "I'll run this myself and post my own environment and output."

## Things I never post

- A promised fix, timeline, or "by tomorrow"
- "Same as above" or "can confirm" without my own evidence
- A result I haven't actually run
- Exclamation-stacked or gushing openers
- Anything that hides AI assistance if the repo's policy requires disclosing it