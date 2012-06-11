CLDR Plural Rule Evaluator
==========================
Find out the plural form for a given number in a language
---------------------------------------------------------

Unlike English, for many languages, the plural forms are just not 2 forms. If you look at the <A href="http://unicode.org/repos/cldr-tmp/trunk/diff/supplemental/language_plural_rules.html#pl">CLDR plural rules table</a>
you can easily understand this.The Rules are defined in a particular syntax(an eg: for Russian, the plural few is applied when the rule "n mod 10 in 2..4 and n mod 100 not in 12..14;" is passed.)
This tool is a demonstration of a <a href="cldrpluralparser.js"> javascript parser </a>for the plural rules in that syntax. For a given number in a language, this tool tells which plural form it belongs.
The plural rules are taken from the CLDR <a href="plural.xml"> plural.xml </a> data file.

See a demonstration of the javascript parser http://thottingal.in/projects/js/plural/