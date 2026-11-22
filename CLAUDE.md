# Working on Spark

## Start here
At the start of every session: read this file and the shared agent rules (Agent Rules for Richard's Sites, https://claude.ai/artifact/VrxiekE5tGeewsZjWCcGR6), run git status and git log -15, and list this site's open jobs on Site Jobs (ArtifactData query on https://claude.ai/artifact/9cukbteXbK5sJbHyxGHPri, collection tasks, where site == "all" and done == false). Then say in two lines where things stand.

- **What it is:** one page, `Tap Tempo BPM Tool.html` ("Free Tap Tempo BPM Tool"): tap a button and it shows the beats per minute. Plain HTML and JavaScript, styled with the Tailwind CDN script. Uploaded on 25 June 2025; no changes since.
- **Status:** Richard believes it is in use. [TODO: where is it published (which site and address), and does a change here reach it automatically?]
- **Build and test:** none. Open the file in a browser to check it.
- **Branches:** default branch `main`. Work on the session's `claude/...` branch. [TODO: Richard's rule for merging to `main`.]

## Rules
- Site Jobs: when you finish work that leaves something for Richard to do, or completes a job, update the Site Jobs page (https://claude.ai/artifact/9cukbteXbK5sJbHyxGHPri) with ArtifactData in the `tasks` collection (site `all`, siteName `All sites`): add new jobs with urgency and importance (1–5) and score = urgency × importance, tick done ones, and never delete or untick.
