# Encrypted Projects - Self-Labelled "Malbolge" Source Text

Two files of dense, unreadable high-ASCII text that call themselves encrypted. Each is a comment
line naming the language and the author, then one long run of characters from the printable
non-alphanumeric range with digits mixed in. Whatever they were meant to be, they are source text for
an esoteric self-modifying language rather than Python - the `.py` extension and the parent folder
are misdirection, in keeping with the header. Kept as-is from 2019.

**Suggested repo name:** `malbolge-esolang-py`
**Stack:** none runnable here - esoteric-language source text (header claims Malbolge); no interpreter bundled
**Status:** archived
**Last modified:** 2019-12-04

## What it does

Nothing verifiable. What can be read is in the headers and the shape:

- `____.py` - 19,393 bytes, first line `#Highly Encypted ?,Malbolge _/Ahura`, then one continuous
  statement of roughly 19,350 characters.
- `______.py` - 2,177 bytes, first line `#HEn/Mb/Ahura` (same three abbreviations: Highly ENcrypted /
  MalBolge / <author>), then about 2,160 characters of the same texture.
- Filenames are underscores only, so the two differ solely by length; the byte counts are the only
  other distinguishing feature.
- The character set is wider than Malbolge's own alphabet - 94 distinct printable characters appear
  across the body - so the label in the header does not match the language strictly, and there is no
  way to confirm either program ever ran. Treat "Malbolge" as the author's framing, not a spec.

## Layout

```
____.py      19,393 bytes of esolang text
______.py     2,177 bytes of the same
```

## Notes

- The companion folder `Rb/Encrypted Projects` holds a third file of this kind (17,532 bytes, two
  byte-identical copies) with the same header style; it is almost certainly a later save of the same
  experiment.
- To do anything with these you would need a Malbolge (or Malbolge-derivative) interpreter, and to
  know which dialect. Expect neither program to produce output under a strict interpreter, since
  out-of-alphabet characters are usually a parse error.
- Safe to publish as curiosities - there are no credentials, no hostnames and no behaviour in here,
  just text. It will simply look like a corrupted file to anyone who does not read this README,
  which is presumably the point.
