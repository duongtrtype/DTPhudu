## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[5] DTPhudu-Medium.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- ellipsis.001

	- i.loclTRK

	- uni004A0301

	- uni006A0301

	- uni013B.loclMAH

	- uni013C.loclMAH

	- uni0145.loclMAH

	- uni0146.loclMAH

	- uni03020300

	- uni03020301 

	- And 8 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: b	Contours detected: 3	Expected: 2

	- Glyph name: e	Contours detected: 1	Expected: 2

	- Glyph name: g	Contours detected: 1	Expected: 2 or 3

	- Glyph name: i	Contours detected: 1	Expected: 2

	- Glyph name: j	Contours detected: 1	Expected: 2

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 2	Expected: 3

	- Glyph name: egrave	Contours detected: 2	Expected: 3

	- Glyph name: eacute	Contours detected: 2	Expected: 3

	- Glyph name: ecircumflex	Contours detected: 2	Expected: 3 

	- And 72 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* OE (U+0152): L<<319.0,700.0>--<319.0,700.0>> -> L<<319.0,700.0>--<675.0,700.0>>

	* Ohorn (U+01A0): L<<319.0,712.0>--<319.0,712.0>> -> L<<319.0,712.0>--<319.0,712.0>>

	* Ohorn (U+01A0): L<<319.0,712.0>--<319.0,712.0>> -> L<<319.0,712.0>--<320.0,712.0>>

	* Ohorn (U+01A0): L<<319.0,712.0>--<320.0,712.0>> -> L<<320.0,712.0>--<324.0,712.0>>

	* oe (U+0153): L<<319.0,700.0>--<319.0,700.0>> -> L<<319.0,700.0>--<675.0,700.0>>

	* ohorn (U+01A1): L<<319.0,712.0>--<319.0,712.0>> -> L<<319.0,712.0>--<319.0,712.0>>

	* ohorn (U+01A1): L<<319.0,712.0>--<319.0,712.0>> -> L<<319.0,712.0>--<320.0,712.0>>

	* ohorn (U+01A1): L<<319.0,712.0>--<320.0,712.0>> -> L<<320.0,712.0>--<324.0,712.0>>

	* uni1EDA (U+1EDA): L<<319.0,712.0>--<319.0,712.0>> -> L<<319.0,712.0>--<319.0,712.0>>

	* uni1EDA (U+1EDA): L<<319.0,712.0>--<319.0,712.0>> -> L<<319.0,712.0>--<320.0,712.0>> 

	* And 32 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* A (U+0041): L<<164.0,700.0>--<396.0,699.0>>

	* AE (U+00C6): L<<164.0,700.0>--<321.0,699.0>>

	* Aacute (U+00C1): L<<164.0,700.0>--<396.0,699.0>>

	* Abreve (U+0102): L<<164.0,700.0>--<396.0,699.0>>

	* Acircumflex (U+00C2): L<<164.0,700.0>--<396.0,699.0>>

	* Adieresis (U+00C4): L<<164.0,700.0>--<396.0,699.0>>

	* Agrave (U+00C0): L<<164.0,700.0>--<396.0,699.0>>

	* Amacron (U+0100): L<<164.0,700.0>--<396.0,699.0>>

	* Aogonek (U+0104): L<<164.0,700.0>--<396.0,699.0>>

	* Aring (U+00C5): L<<164.0,700.0>--<396.0,699.0>> 

	* And 56 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[5] DTPhudu-Black.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- ellipsis.001

	- i.loclTRK

	- uni004A0301

	- uni006A0301

	- uni013B.loclMAH

	- uni013C.loclMAH

	- uni0145.loclMAH

	- uni0146.loclMAH

	- uni03020300

	- uni03020301 

	- And 8 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: ampersand	Contours detected: 4	Expected: 1, 2 or 3

	- Glyph name: at	Contours detected: 3	Expected: 2

	- Glyph name: b	Contours detected: 3	Expected: 2

	- Glyph name: e	Contours detected: 1	Expected: 2

	- Glyph name: g	Contours detected: 1	Expected: 2 or 3

	- Glyph name: i	Contours detected: 1	Expected: 2

	- Glyph name: j	Contours detected: 1	Expected: 2

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 2	Expected: 3

	- Glyph name: egrave	Contours detected: 2	Expected: 3 

	- And 76 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* OE (U+0152): L<<305.0,700.0>--<305.0,700.0>> -> L<<305.0,700.0>--<673.0,700.0>>

	* Ohorn (U+01A0): L<<307.0,712.0>--<308.0,712.0>> -> L<<308.0,712.0>--<308.0,712.0>>

	* oe (U+0153): L<<305.0,700.0>--<305.0,700.0>> -> L<<305.0,700.0>--<673.0,700.0>>

	* ohorn (U+01A1): L<<307.0,712.0>--<308.0,712.0>> -> L<<308.0,712.0>--<308.0,712.0>>

	* uni1EDA (U+1EDA): L<<307.0,712.0>--<308.0,712.0>> -> L<<308.0,712.0>--<308.0,712.0>>

	* uni1EDB (U+1EDB): L<<307.0,712.0>--<308.0,712.0>> -> L<<308.0,712.0>--<308.0,712.0>>

	* uni1EDC (U+1EDC): L<<307.0,712.0>--<308.0,712.0>> -> L<<308.0,712.0>--<308.0,712.0>>

	* uni1EDD (U+1EDD): L<<307.0,712.0>--<308.0,712.0>> -> L<<308.0,712.0>--<308.0,712.0>>

	* uni1EDE (U+1EDE): L<<307.0,712.0>--<308.0,712.0>> -> L<<308.0,712.0>--<308.0,712.0>>

	* uni1EDF (U+1EDF): L<<307.0,712.0>--<308.0,712.0>> -> L<<308.0,712.0>--<308.0,712.0>> 

	* And 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* A (U+0041): L<<125.0,700.0>--<422.0,699.0>>

	* AE (U+00C6): L<<125.0,700.0>--<292.0,699.0>>

	* Aacute (U+00C1): L<<125.0,700.0>--<422.0,699.0>>

	* Abreve (U+0102): L<<125.0,700.0>--<422.0,699.0>>

	* Acircumflex (U+00C2): L<<125.0,700.0>--<422.0,699.0>>

	* Adieresis (U+00C4): L<<125.0,700.0>--<422.0,699.0>>

	* Agrave (U+00C0): L<<125.0,700.0>--<422.0,699.0>>

	* Amacron (U+0100): L<<125.0,700.0>--<422.0,699.0>>

	* Aogonek (U+0104): L<<125.0,700.0>--<422.0,699.0>>

	* Aring (U+00C5): L<<125.0,700.0>--<422.0,699.0>> 

	* And 51 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[5] DTPhudu-Light.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- ellipsis.001

	- i.loclTRK

	- uni004A0301

	- uni006A0301

	- uni013B.loclMAH

	- uni013C.loclMAH

	- uni0145.loclMAH

	- uni0146.loclMAH

	- uni03020300

	- uni03020301 

	- And 8 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: b	Contours detected: 3	Expected: 2

	- Glyph name: e	Contours detected: 1	Expected: 2

	- Glyph name: g	Contours detected: 1	Expected: 2 or 3

	- Glyph name: i	Contours detected: 1	Expected: 2

	- Glyph name: j	Contours detected: 1	Expected: 2

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 2	Expected: 3

	- Glyph name: egrave	Contours detected: 2	Expected: 3

	- Glyph name: eacute	Contours detected: 2	Expected: 3

	- Glyph name: ecircumflex	Contours detected: 2	Expected: 3 

	- And 72 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Ohorn (U+01A0): L<<331.0,712.0>--<331.0,712.0>> -> L<<331.0,712.0>--<332.0,712.0>>

	* Ohorn (U+01A0): L<<331.0,712.0>--<332.0,712.0>> -> L<<332.0,712.0>--<333.0,712.0>>

	* ohorn (U+01A1): L<<331.0,712.0>--<331.0,712.0>> -> L<<331.0,712.0>--<332.0,712.0>>

	* ohorn (U+01A1): L<<331.0,712.0>--<332.0,712.0>> -> L<<332.0,712.0>--<333.0,712.0>>

	* uni1EDA (U+1EDA): L<<331.0,712.0>--<331.0,712.0>> -> L<<331.0,712.0>--<332.0,712.0>>

	* uni1EDA (U+1EDA): L<<331.0,712.0>--<332.0,712.0>> -> L<<332.0,712.0>--<333.0,712.0>>

	* uni1EDB (U+1EDB): L<<331.0,712.0>--<331.0,712.0>> -> L<<331.0,712.0>--<332.0,712.0>>

	* uni1EDB (U+1EDB): L<<331.0,712.0>--<332.0,712.0>> -> L<<332.0,712.0>--<333.0,712.0>>

	* uni1EDC (U+1EDC): L<<331.0,712.0>--<331.0,712.0>> -> L<<331.0,712.0>--<332.0,712.0>>

	* uni1EDC (U+1EDC): L<<331.0,712.0>--<332.0,712.0>> -> L<<332.0,712.0>--<333.0,712.0>> 

	* And 18 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* A (U+0041): L<<205.0,700.0>--<369.0,699.0>>

	* AE (U+00C6): L<<205.0,700.0>--<352.0,699.0>>

	* Aacute (U+00C1): L<<205.0,700.0>--<369.0,699.0>>

	* Abreve (U+0102): L<<205.0,700.0>--<369.0,699.0>>

	* Acircumflex (U+00C2): L<<205.0,700.0>--<369.0,699.0>>

	* Adieresis (U+00C4): L<<205.0,700.0>--<369.0,699.0>>

	* Agrave (U+00C0): L<<205.0,700.0>--<369.0,699.0>>

	* Amacron (U+0100): L<<205.0,700.0>--<369.0,699.0>>

	* Aogonek (U+0104): L<<205.0,700.0>--<369.0,699.0>>

	* Aring (U+00C5): L<<205.0,700.0>--<369.0,699.0>> 

	* And 80 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[5] DTPhudu-Regular.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- ellipsis.001

	- i.loclTRK

	- uni004A0301

	- uni006A0301

	- uni013B.loclMAH

	- uni013C.loclMAH

	- uni0145.loclMAH

	- uni0146.loclMAH

	- uni03020300

	- uni03020301 

	- And 8 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: b	Contours detected: 3	Expected: 2

	- Glyph name: e	Contours detected: 1	Expected: 2

	- Glyph name: g	Contours detected: 1	Expected: 2 or 3

	- Glyph name: i	Contours detected: 1	Expected: 2

	- Glyph name: j	Contours detected: 1	Expected: 2

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 2	Expected: 3

	- Glyph name: egrave	Contours detected: 2	Expected: 3

	- Glyph name: eacute	Contours detected: 2	Expected: 3

	- Glyph name: ecircumflex	Contours detected: 2	Expected: 3 

	- And 72 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* OE (U+0152): L<<326.0,700.0>--<326.0,700.0>> -> L<<326.0,700.0>--<677.0,700.0>>

	* Ohorn (U+01A0): L<<325.0,712.0>--<325.0,712.0>> -> L<<325.0,712.0>--<326.0,712.0>>

	* Ohorn (U+01A0): L<<325.0,712.0>--<326.0,712.0>> -> L<<326.0,712.0>--<326.0,712.0>>

	* oe (U+0153): L<<326.0,700.0>--<326.0,700.0>> -> L<<326.0,700.0>--<677.0,700.0>>

	* ohorn (U+01A1): L<<325.0,712.0>--<325.0,712.0>> -> L<<325.0,712.0>--<326.0,712.0>>

	* ohorn (U+01A1): L<<325.0,712.0>--<326.0,712.0>> -> L<<326.0,712.0>--<326.0,712.0>>

	* uni1EDA (U+1EDA): L<<325.0,712.0>--<325.0,712.0>> -> L<<325.0,712.0>--<326.0,712.0>>

	* uni1EDA (U+1EDA): L<<325.0,712.0>--<326.0,712.0>> -> L<<326.0,712.0>--<326.0,712.0>>

	* uni1EDB (U+1EDB): L<<325.0,712.0>--<325.0,712.0>> -> L<<325.0,712.0>--<326.0,712.0>>

	* uni1EDB (U+1EDB): L<<325.0,712.0>--<326.0,712.0>> -> L<<326.0,712.0>--<326.0,712.0>> 

	* And 20 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* A (U+0041): L<<185.0,700.0>--<383.0,699.0>>

	* AE (U+00C6): L<<185.0,700.0>--<337.0,699.0>>

	* Aacute (U+00C1): L<<185.0,700.0>--<383.0,699.0>>

	* Abreve (U+0102): L<<185.0,700.0>--<383.0,699.0>>

	* Acircumflex (U+00C2): L<<185.0,700.0>--<383.0,699.0>>

	* Adieresis (U+00C4): L<<185.0,700.0>--<383.0,699.0>>

	* Agrave (U+00C0): L<<185.0,700.0>--<383.0,699.0>>

	* Amacron (U+0100): L<<185.0,700.0>--<383.0,699.0>>

	* Aogonek (U+0104): L<<185.0,700.0>--<383.0,699.0>>

	* Aring (U+00C5): L<<185.0,700.0>--<383.0,699.0>> 

	* And 99 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[5] DTPhudu-Bold.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- ellipsis.001

	- i.loclTRK

	- uni004A0301

	- uni006A0301

	- uni013B.loclMAH

	- uni013C.loclMAH

	- uni0145.loclMAH

	- uni0146.loclMAH

	- uni03020300

	- uni03020301 

	- And 8 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: ampersand	Contours detected: 4	Expected: 1, 2 or 3

	- Glyph name: b	Contours detected: 3	Expected: 2

	- Glyph name: e	Contours detected: 1	Expected: 2

	- Glyph name: g	Contours detected: 1	Expected: 2 or 3

	- Glyph name: i	Contours detected: 1	Expected: 2

	- Glyph name: j	Contours detected: 1	Expected: 2

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 2	Expected: 3

	- Glyph name: egrave	Contours detected: 2	Expected: 3

	- Glyph name: eacute	Contours detected: 2	Expected: 3 

	- And 74 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* OE (U+0152): L<<312.0,700.0>--<312.0,700.0>> -> L<<312.0,700.0>--<674.0,700.0>>

	* oe (U+0153): L<<312.0,700.0>--<312.0,700.0>> -> L<<312.0,700.0>--<674.0,700.0>>

	* uniA78B (U+A78B): L<<208.0,700.0>--<183.0,218.0>> -> L<<183.0,218.0>--<183.0,206.0>>

	* uniA78B (U+A78B): L<<55.0,206.0>--<55.0,218.0>> -> L<<55.0,218.0>--<30.0,700.0>>

	* uniA78C (U+A78C): L<<208.0,700.0>--<183.0,218.0>> -> L<<183.0,218.0>--<183.0,206.0>> 

	* And uniA78C (U+A78C): L<<55.0,206.0>--<55.0,218.0>> -> L<<55.0,218.0>--<30.0,700.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* A (U+0041): L<<144.0,700.0>--<410.0,699.0>>

	* AE (U+00C6): L<<144.0,700.0>--<306.0,699.0>>

	* Aacute (U+00C1): L<<144.0,700.0>--<410.0,699.0>>

	* Abreve (U+0102): L<<144.0,700.0>--<410.0,699.0>>

	* Acircumflex (U+00C2): L<<144.0,700.0>--<410.0,699.0>>

	* Adieresis (U+00C4): L<<144.0,700.0>--<410.0,699.0>>

	* Agrave (U+00C0): L<<144.0,700.0>--<410.0,699.0>>

	* Amacron (U+0100): L<<144.0,700.0>--<410.0,699.0>>

	* Aogonek (U+0104): L<<144.0,700.0>--<410.0,699.0>>

	* Aring (U+00C5): L<<144.0,700.0>--<410.0,699.0>> 

	* And 51 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 0 | 25 | 557 | 31 | 462 | 0 |
| 0% | 0% | 2% | 52% | 3% | 43% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
