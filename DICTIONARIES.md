# Dictionaries

The `.ocd2` files in `Sources/OpenCC/Dictionary` come from OpenCC 1.4.2 (August 2026),
taken from the official `opencc` 1.4.2 Python package. The engine is unchanged (OpenCC 1.1.2).
`JPVariants.ocd2` and `JPVariantsRev.ocd2` are no longer shipped by OpenCC and stay as they were.

Checked against OpenCC 1.4.2 itself: on 3,000 Taiwan and 3,000 Hong Kong sentences converted
with `s2tw` and `s2hk`, the output of this package is byte-for-byte identical.
