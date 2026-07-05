# Transient Carbon classes

Every class in this folder is transient: it is destined for a shared Carbon
library and lives here only until that library exists. Do not grow package-
specific behaviour onto these classes, and do not import them from outside
this package — they will move.
