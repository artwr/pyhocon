# Changelog

# Version 0.3.12

* Fixed list merge. PR[#51]

# Version 0.3.11

* Added default indent to 2. PR[#47]
* Fix dotted notation merge. PR[#49]

# Version 0.3.10

* Backward compatibility with imports

# Version 0.3.9

* Added from_dict to convert a dict or ordered dict into a config tree. PR[#42]

# Version 0.3.8

* Fix multi line string (don't escape). PR[#41]
* Added HOCON export. PR[#40]

# Version 0.3.7

* Added with_fallback method. PR[#38]

# Version 0.3.6

* Added with_fallback method. PR[#37]

# Version 0.3.5

* Fixed substitutions to be evaluated after all files are loaded. PR[#36]

# Version 0.3.4

* Fixed substitutions that are overriden later on by a non substitution. PR[#34]
* Added logging. PR[#30] and PR[#31]

# Version 0.3.3

* Fixed optional substitution when overriding elements at the same level. PR[#28]
* Silent IOErrors when including non-existent files. PR[#24]
* Fixed when assign key to a value, list or dict that starts with eol. PR[#22]

## Version 0.3.2

* implemented optional substitution (e.g., ${?abc}) and fixed substitution logic when having dict merge. PR[#20]

## Version 0.3.1

* can specify default value in get, get_int, ... PR[#17]

## Version 0.3.0

* fixed list of dict merge and includes in list. PR [#16]

## Version 0.2.9

* fixed expression assignment (only dictionaries with no concat can omit the : or = sign). PR [#15]

## Version 0.2.8

* fixed parse_URL

## Version 0.2.7

* fixed dict merge. PR [#14]

## Version 0.2.6

* fixed string substitutions. PR [#13]

## Version 0.2.5

* added list and dict inheritance. PR [#11]

## Version 0.2.4

* added python 2.6 support. PR [#8]

## Version 0.2.3

* fixed bug when we insert None values that shouldn't raise an exception when getting them. PR [#7]

## Version 0.2.2

* simplified code (ConfigTree extends OrderedDict) and other features. PR [#6]
