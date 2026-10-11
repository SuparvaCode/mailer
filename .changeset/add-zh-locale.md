---
'@onetodone/mailer': patch
---

Add built-in text in Chinese (Simplified).

- `Locale` gains `zh`. The `locale` setting and the `locale` option of `send` and `render` accept it without `messages`.
- If you already send in Chinese (Simplified) through `messages`, your overrides still win, and the keys you leave out come from the built-in text instead of English.
