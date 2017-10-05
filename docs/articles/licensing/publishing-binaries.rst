Policy for publishing build artifacts
===================================== 

Since there are parts of the code which are licensed as GPL we are
obligated to provide complete and corresponding source code together with
publication of any binary artifact on request. Furthermore, the license
demands that the source code is available for three years.

Consequences
------------
In order to not violate the license, all public CI systems need to publish
corresponding source code together with _any_ build artifact. This includes
things like yocto sstatecache.

Desition
--------
When doing a release of a full systems or product this is not that a
problem (assuming that there is no external propriatary code).

However, in a context where publishing is done often the requirement
to store the source code leads to disk space issues. An example is when
doing rapid prototyping of applications to a system where the code needs
to be available for each published iteration of each publish binary.

Conclusion
----------
To avoid unforseen cost of storing old source code, do not publish any
binaries publically without first gotten the approval to do so.
