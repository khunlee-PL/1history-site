# Website page translations (SEPARATE from the app corpus)

These files translate the /world country pages into national languages for the
WEBSITE ONLY. They live in the site repo and NEVER touch C:\1History\corpus\*.translations.json
(the app's 200-language corpus effort). The two tracks are independent:
no shared files, no shared pipeline.

- chrome.<lang>.json  — the page chrome for a language (shared by every country page in that lang)
- <slug>.<lang>.json  — one country page's translated anchor + meanwhile (title/text + localized place labels)

Build a localized page with tools/build_country_page_i18n.py (in C:\1History\tools).
