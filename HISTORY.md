Version 1.2
===========
October 5, 2018

+ Simplified adding new languages by extracting language-specific cleanup into separate class
  (contribution by [fabrichter](https://github.com/fabrichter))
+ Added basic support for 13 languages:
    * French
    * Breton
    * Catalan
    * Greek
    * Esperanto
    * Spanish
    * Galician
    * Italian
    * Dutch
    * Polish
    * Portuguese
    * Russian
    * Ukrainian


Version 1.1
===========
June 17, 2018

+ Added support for Kannada (contribution by [shivahr](https://github.com/shivahr))

Version 1.0
===========
June 14, 2017

+ Refactored WikipediaBz2DumpInputStream into WikipediaArticlesDump, which provides iterator and stream support.
+ Refactored builder.
+ Changed visibility methods and inner classes of WikiClean, test cases refactored accordingly.
+ Added documentation.

Version 0.5
===========
March 25, 2017

+ Issue #2: Wrap FileInputStream in a BufferedInputStream for ~10x speed improvement

Version 0.4
===========
January 1, 2017

+ Added convenience programs to parse out English Wikipedia.
+ Added Chinese support.

Version 0.3
===========
July 1, 2013

+ Refactoring of API to get rid of static methods.
+ Added initial multi-lingual support (German).
+ Minor cleaning improvements.

Version 0.2
===========
June 27, 2013

+ Added documentation.
+ Refactored WikiClean into a builder pattern.

Version 0.1
===========
June 26, 2013

+ Initial release: performs basic cleaning of Wikipedia pages, verified on a sampling of English articles.
