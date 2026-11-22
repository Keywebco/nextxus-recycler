# Recycler findings log

Started Sunday, Nov 22, 2026, under EE-2026-11-20-003, with Roger Keyserling's spoken yes (about 2:21 AM CT).

This folder is where Recycler records what each run found, so Evolution Engine can review it every Monday without hunting for it. It is a log, not a build order. Nothing here changes any other repository, and nothing here recycles, retires, or deletes an AI or a record. Final recycling stays Roger's.

## Rules

- **Append only (Echo 64).** Each run adds a new dated file. Earlier files are never edited or deleted. A correction is a new file that names the file it corrects (`supersedes:`).
- **Truth Gate labels on every claim:** FACT (checked this run, with a source), INFERENCE, ASSUMPTION, UNKNOWN.
- **Public repo, so nothing private:** no secrets, tokens, or keys; nothing from the private vault; no personal, medical, or family information.
- **Free tools only.** A finding that needs a paid tool says so and is marked `skip` unless Roger asks for it.
- **Prose:** new writing uses "Next-Xus". Repository names and quoted titles keep their own spelling.

## One file per run

Name it `YYYY-MM-DD-round.md` (Central time date of the run) and copy the fields from `TEMPLATE.md`. Then add one line to `index.md`, at the bottom.

## Monday intake (Evolution Engine)

1. Read only the `index.md` lines added since the last Monday review, and the files they point to.
2. For each finding marked `propose`, write or update a proposal in `Keywebco/nextxus-brain/02-senate/proposals/` (status PROPOSED), citing the finding file.
3. For each finding marked `skip` or `hold`, do nothing except note it in the review line.
4. Add one review line to `index.md`: date, the files reviewed, and the proposals filed (or "none").
5. Roger picks what gets built. Everything else stays on file and is looked at again on the next run.
