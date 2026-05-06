2026-04-23
Implemented recursive DFS function in main.cpp.
Added base cases for out-of-bounds, walls, and already visited cells.
Used visited matrix to prevent infinite loops.
Verified DFS correctly stops when exit cell is found.
Tested with multiple maze sizes to confirm traversal works.

2026-04-24
Added parent tracking using parent_r and parent_c arrays.
Stored previous cell before making recursive DFS calls.
Connected DFS results to printPath() for path reconstruction.
Tested both cases where a path exists and where no path exists.
Confirmed program outputs correct path or "No path exists.".

2026-04-25
Fixed DFS so it explores all four directions correctly.
Found issue where some paths were being missed.
Checked how dr and dc were being used.
Updated neighbor traversal logic.
Tested again and confirmed paths are now found correctly.

2026-04-26
Tested program with different maze sizes.
Checked both path and no-path cases.
Verified DFS returns correct result.
Confirmed output prints path or "No path exists." correctly.
Final testing shows program works as expected.

2026-05-05
Ran additional tests with different maze sizes.
Verified DFS works for both path and no-path cases.
Confirmed output is correct.

2026-05-05
Cleaned up DFS code formatting.
Simplified base case checks.
Made sure code is readable and consistent.
Tested again to confirm no errors after changes.
Final version of program is complete.
