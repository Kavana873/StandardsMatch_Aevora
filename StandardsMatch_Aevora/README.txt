StandardsMatch - SIH26108 - Team Aevora (browser prototype)

HOW TO RUN
Double-click index.html (opens in Chrome / Edge / Firefox). No install needed.
Internet is needed only for reading PDF and Word files (pdf.js and mammoth load from cdnjs).
TXT files and pasted text work offline.

LOGIN
Landing page first. Sign up (stored in this browser only) or use the demo account: officer / standards123.

WHAT IT DOES
Upload/paste tender -> extraction -> requirement fingerprint -> hybrid search (keyword + TF-IDF)
-> applicability -> recommendations with reason and evidence -> Accept / Reject / Needs verification
-> report (Print / Save as PDF, or copy text). English, Kannada and Hindi UI.
Verified set: 28 BIS standards (see the Standards Library button).
Below 30% best match, an "Out of scope" banner is shown.

SAMPLE FILES (sample_tenders folder)
sample_tender_multi_item.txt      - many standards matched (also cites an old edition, IS 15683:2006)
sample_tender_out_of_scope.txt    - shows the Out of scope banner
Other sample_tender_*.txt files   - from your original Flask prototype

NOTE
Decision-support only. Verify against current official BIS records before procurement.
