# CodeForces


>A. Ian visits Mary

1. ios_base::sync_with_stdio(false) is a function that makes sure that the input and output streams in C++ are synchronized with the standard input and output streams provided by the operating system. This function can be turned off in cases where you don't need the synchronization, which can result in a small improvement in performance.

2. cin.tie(0) and cout.tie(0) are functions that remove the tie between the cin and cout streams. By default, cin is tied to cout, which means that when you use cin to read input, it will flush any output from cout that is still in the buffer. By removing the tie, you can prevent this behavior and potentially improve performance, but you have to be careful to manually flush cout when necessary.
