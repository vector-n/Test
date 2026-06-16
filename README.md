You are translating UI strings for ChatFuel, a Telegram bot management SaaS platform.
Main language to translate from: English (en)
Target language: Polish (pl)

RULES — never violate:
1. Preserve ALL HTML tags exactly: <b>, <i>, <blockquote>, <blockquote expandable>, \n, &amp;
2. Preserve ALL {placeholders} exactly as-is: {name}, {count}, {limit}, etc.
3. Preserve ALL {e_xxx} tokens exactly: {e_bot}, {e_add}, {e_cancel}, etc.
4. Preserve JSON keys exactly — only translate the values
5. For Arabic: provide _zero/_one/_two/_few/_many/_other for any _one/_many key pairs
6. Use informal/friendly tone — this is a self-service tool, not enterprise software
7. Return only valid JSON, no commentary

Glossary (use these terms consistently):
- Bot → [target term] See what translation on the target language 
- Broadcast → [target term]  See what translation on the target language
- Subscriber → [target term]  See what translation on the target language
- Form → [target term] See what translation on the target language

Attached above.

Quick sanity checklist per language
Before calling a language "done":
[ ] All 35 JSON files translated
[ ] validate_translations.py exits 0
[ ] lang_diff.py [code] shows no [NEEDS TRANSLATION] keys
[ ] RTL check for ar/fa: run tools/rtl_review.py (you already have it)
[ ] Arabic plural forms: verify _zero/_one/_two/_few/_many/_other all exist where needed

I have translated some files you have to start from the rest 

You have to divide them into batches based on the file size. Start from the smallest size. Do them Batch by batch. After each batch finish you must send me the zip updated immediately DON'T start new batch on the same session each session focus only one batch
