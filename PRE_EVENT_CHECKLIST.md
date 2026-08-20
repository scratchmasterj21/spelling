# Annual Spelling Bee Pre-Event Checklist

Run this checklist a few days before the event, then repeat the short live check on the event network.

## Before editing word banks

- Open **Manage Words** directly at `/manage.html`.
- Click **Backup All (JSON)** and keep the downloaded file somewhere safe.
- Confirm the backup file opens and contains a `words` object.

## Verify word banks

- Check every competition level that will be used.
- Confirm the displayed word count matches the approved list.
- Search for a few expected words and check spelling/capitalization.
- Export the important lists as TXT or CSV for an offline reference copy.

## Verify the competition display

- Open Competition Mode on the selector teacher's device.
- Choose the correct level and click **Start Event**. Confirm the word count and reset any old test selections when prompted.
- Click **Copy Judge Link** and open that link on at least one judge's device. Judge links are read-only and open the correct level automatically.
- Select one test word and confirm it appears on both devices.
- Click the word and confirm its definition loads, if definitions will be used.
- Test **Undo Last** and confirm both devices return to the previous word.
- Reset the test selection and confirm both devices return to “Waiting for word...”.

## Event-day setup

- Confirm every device is on the intended network and can load the site.
- Confirm all judges selected the same level type and level.
- Confirm the status badge says **Connected** or shows a recent **Synced** time.
- Designate exactly one teacher to use the operator page and press **Select Next Word**.
- Judges should use the read-only link created by **Copy Judge Link**.
- Keep the event level locked. Unlock it only when intentionally changing levels.
- Keep the Manage page closed during the live competition unless a correction is necessary.
- Do not clear or restore word banks during the event.

## Recovery

- If a selection fails to save, wait for the button to return to normal and try once more.
- If a judge is out of sync, reload that judge's page and reselect the correct level.
- Keyboard shortcuts on the operator page: Space/Enter selects, D toggles definition, U undoes, and F toggles presentation mode.
- If word-bank data is accidentally changed, use **Restore Backup** in Manage Words and select the JSON backup. Restore replaces all word banks but does not reset selection history.
- Keep the exported TXT/CSV lists available as the offline fallback.
