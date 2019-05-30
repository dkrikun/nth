# nth
Select nth line/column

Ever feeled tedious to write sed 'LINEq;d' and awk '{ print $COLUMN }'
to select nth line/column in pipelines?

Nth just provides a simple entry point without cumbersome syntax for
this trivial task.

Usage:

nth [-l|-c] NUMBER
