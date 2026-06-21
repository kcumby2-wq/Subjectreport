# Evaluation Processing — Transcript → Family-Facing Summary

This skill defines how a raw Prospect Edge evaluation transcript becomes the family-facing summary delivered to the customer.

## Trigger

A new transcript appears in `data/transcripts/`.

## Process

1. Read the raw transcript/evaluation data in full.
2. Translate technical grading language into the family-facing summary using the `srvoice` skill tone rules.
3. Apply any standing feedback-log instructions affecting this skill (e.g. plain-language lines under technical grades) before drafting.
4. Save the finished summary to `output/reports/` with the date and athlete name in the filename.
5. Check the overall grade:
   - 4.0+ → flag the athlete as an Active Profile candidate (confirm a consent form is on file before creating a profile; if missing, flag as blocked).
6. Note in the session log that the transcript was processed and where the output was saved.

## Notes

- This skill produces the deliverable that feeds Goal 1 (Transcript Volume) and Goal 4 (Active Profile Pipeline).
- Every delivered transcript should also trigger the Subject Media upsell sequence draft (see daily workflow Step 2).
