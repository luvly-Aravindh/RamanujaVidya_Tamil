RAMANUJA VIDYA TAMIL PACK
Sri Bhashyam, free 60 minute session

FILES
  index.html       the landing page
  thank-you.html   where the form sends people after they register

DEPLOY
  Keep both files in the same folder. index.html redirects to thank-you.html
  by relative path, so renaming either one breaks the handoff. If you must
  rename, update THANKYOU_URL near the top of the script block in index.html.
  Both files are self contained. All images are inlined, nothing else to upload.

FILL THESE BEFORE GOING LIVE
  index.html
    {{LEAD_WEBHOOK_URL}}      where the form posts the lead
    {{VSL_URL}}               the video embed on the landing page
  thank-you.html
    {{CALENDAR_URL}}          add to calendar link
    {{YOUTUBE_CHANNEL_URL}}   Ramanuja Vidya channel
    {{SHARE_URL}}             the link people pass on

SESSION DETAILS BAKED IN
  Sunday 11 October 2026, 9:00 AM IST, on Google Meet.
  The countdown reads from WEBINAR_ISO in index.html: 2026-10-11T09:00:00+05:30
  Change the date in three places if it moves: WEBINAR_ISO, and the date chips
  in both files.

STILL OPEN
  The 13 written testimonials came from the student WhatsApp group. Each person
  should see the trimmed version and agree to it being published, per ASCI.

  thank-you.html is set to noindex, which is correct for a page behind a form.
