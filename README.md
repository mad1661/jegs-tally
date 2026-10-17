# jegs-tally
Unofficial live JEGS Allstars team points (Texas FallNationals). Public read-only data; totals.json pushed by publish.sh on the box.

`pi_runs-dt1.json`: sanitized NHRA timing-Pi pairs for this event (results only: names, car numbers, class, dial, timing slip;
no member numbers, no credentials). Read by the Dark Mawson Announcer PC/Mac app to backfill the pro lows strip / bump and
OLD RUNS from first launch. Regenerated from the box Pi log by `/workspace/shared/bin/announcer-event-runs.py` in the same loop.
