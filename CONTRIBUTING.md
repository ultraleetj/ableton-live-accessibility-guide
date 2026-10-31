# Contributing

Thanks for helping make this guide more accurate. The most useful contribution is a tested correction.

## What to contribute

- Corrections to shortcuts, behaviors or workflows that do not work as written.
- New shortcuts or workflows you have tested yourself.
- Typo, translation and wording fixes.
- Notes on differences between Ableton Live versions, or between Windows and Mac.

## Rules for content

1. Only submit what you have tested. If you are not sure, say so in the issue or pull request instead of editing the guide.
2. State your setup: Ableton Live version (including beta), operating system, screen reader and version.
3. Where tested behavior conflicts with the official manual, the tested behavior wins. Mention the conflict in your pull request description, not in the guide.
4. Do not copy text from the official Ableton manual or other sources. Describe things in your own words.

## Style rules for the guide

- Plain, direct prose. Second person: "you press...", "select the...".
- No process narration in the text. Do not write "confirmed by testing" or "corrected from an earlier version". State the fact plainly.
- No tables. Use `<ul><li>` lists for shortcuts, dialog fields, menu items and parameters. Section 4.1 is the model.
- No emoji and no em-dashes.
- Refer to other sections by number ("see section 5.1") instead of repeating the explanation.
- Only rewrite the sentence that is wrong. Leave correct text alone.
- Keep the HTML plain: one `<h1>` per numbered section, paragraphs in `<p>` with `<br>` separators, no CSS.
- Known crash bugs are documented once, in section 4.3. Do not add repeated warnings elsewhere unless you found a new crash.

## How to contribute

1. Open an issue describing what is wrong or missing, with the section number and your setup. This is enough for most corrections.
2. For direct edits, fork the repository, change the HTML file, and open a pull request. Keep each pull request to one section or one topic.
3. Check that the file still reads cleanly with a screen reader after your edit.

## Accessibility of the repository

Issues and pull requests are plain text. If any part of the contribution process is hard to use with a screen reader, open an issue and say so.

## Licence

No licence has been chosen yet. Do not submit text you do not have the right to share.
