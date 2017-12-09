

_Use this document to describe whatever memory leaks you find in `clean_whitespace.c` and how you might fix them. You should also probably remove this explanatory text._

In the file checkwhite.space.c line 41 cause leak. We cannot free the result becuase result return later. 
