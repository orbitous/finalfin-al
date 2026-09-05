<!--
  finalfin.al — puzzles.md format
  ====================================
  Each day's puzzle starts with a marker on its own line:
      <<PUZZLE:DD-MM-YYYY>>
  Everything from one marker up to the next (or end of file) is that day's
  content — parsed exactly the same way as a single-puzzle file, so every
  rule in sample-challenge.md's header comment (error types, tag syntax,
  markdown subset) applies unchanged inside each day's section.

  The game picks a puzzle like this: exact date match wins; if today isn't
  listed yet, it shows the most recent past date instead; if every date is
  still in the future, it shows the earliest one. That's why the two short
  puzzles below are deliberately placed a few days apart with gaps — it's
  a live demonstration of the fallback, not an oversight. Try opening the
  game with e.g. ?date=02-09-2026 in the URL (no puzzle on the 2nd — falls
  back to the 1st) or ?date=06-09-2026 (nothing till the 5th — falls back
  to that). Note the date resolves DD-MM-YYYY, not MM-DD-YYYY.

  Only ONE puzzle per real calendar day is meant to exist below — don't
  duplicate a date, the second one silently overwrites the first when the
  file is split.
-->

<<PUZZLE:01-09-2026>>

# Weekly Status Memo

## Update

The vendor confirmed delivery for [[Q3]]<<ERR:font>> and pricing remains at S$1,200 per unit[[,]]<<ERR:punctuation>> with the balance due on receipt.

<<PUZZLE:05-09-2026>>

# Notice of Amendment — Consulting Agreement

## 1. Background

This Amendment is entered into by the parties for the purpose of updating certain terms under the original Consulting Agreement dated 14 March 2024. The revised fee schedule reflects current<<ERR:sizeBig>> market rates and shall take effect on the Effective Date –<<ERR:dash>> as defined in Section 3 below — unless otherwise agreed in writing.

## 2. Revised Fees

| Service | Rate | Notes |
| --- | --- | --- |
| Strategy review | S$4,500 | Billed monthly |
| Implementation support | S$2,800 | Billed monthly |
| Ad-hoc advisory | [[US$]]<<ERR:currency>>2,800 | Billed hourly |

## 5.<<ERR:heading-number>> Term and Termination

Either party may terminate this arrangement upon thirty (30) days' written notice. The parties agree that the term [[“]]<<ERR:quotes:id=q1>>Confidential Information[["]]<<ERR:quotes:id=q1>> shall retain the meaning given to it in the [[original Agreement]]<<ERR:font>>, in contrast to the defined term “Effective Date,” which appears throughout. All confidentiality obligations survive termination¹<<ERR:footnote>>. Notice must be delivered in writing[[:]]<<ERR:punctuation>> electronic delivery is acceptable, provided delivery is confirmed in writing by the recipient.²

## 4. Notice Requirements

- Notice must be delivered to the address on file.
- Notice is deemed recieved<<ERR:spelling>> three (3) business days after mailing.
-<<ERR:indent>> Electronic notice is permitted if confirmed in writing.
- The invoice [[_must be paid promptly_]]<<ERR:formatting>> to avoid penalties.

<<PUZZLE:20-09-2026>>

# Client Onboarding Checklist

## Steps

1. Collect signed engagement letter
2. Confirm billing contact and address
5.<<ERR:listnum>> Schedule kickoff call
