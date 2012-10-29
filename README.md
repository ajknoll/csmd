csmd
====

Character sheet markdown

# Project outline

 1. Write a sheet (Pathfinder) in a markdown-like format.
 2. Derive a grammar backwards from the sheet.
 3. Implement the grammar as a parser.

The key concept here will be to have "update rules", whereby certain values are marked as derivable
and can be updated by parsing the sheet file, finding their dependencies, and computing via the
appropriate equation.

Equations should be primarily specifiable via the grammar (a separate file, probably just a .hs
config as with Xmonad etc.). As a secondary goal, allow inline specifications in the sheet?
