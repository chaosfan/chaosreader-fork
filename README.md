chaosreader-fork
================

Project to expand and update Brendan Gregg's original Chaosreader perl script

The purpose of this project is to expand on BG's original code and to make Chaosreader (much) more memory tolerant. The trade off being disk space and speed. The code as it stands now has been adapted to use on-disk hashing and upon execution determines whether to use this on-disk method, or to resort to in-memory execution depending on how much memory is installed in the system.

Biggest drawback right now is it is TOO SLOW to be practical. Therefore, switching from on-disk hashes to database storage may be a better way to proceed.

Comments and additions more than welcome.
