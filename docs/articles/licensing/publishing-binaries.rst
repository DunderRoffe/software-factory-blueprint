Publishing binary images
========================== 

We release binary images of our products that are licensed under the 
[https://www.gnu.org/licenses/old-licenses/gpl-2.0.html](GNU Public License).
This is considered "distribution" under the GPL. When distributing binaries, 
or object code, covered under the GPL "complete and corresponding" source code 
is required to be provided as well. We comply with these obligations 
by publishing source code on GitHub and through our continuous integration 
system (CI).

In order to comply with all FOSS software licenses, public CI systems must 
plublish complete and corresponding source code in conjunction with the publishing
of object code. This include a yocto sstatecache, binary images for hardware 
targets, and binary packages, like rpms or debs.

Decision
--------
When doing a release of a full system or product this is not that a
problem (assuming that there is no external proprietary code).

However, in a context where publishing is done often the requirement
to store the source code leads to disk space issues. An example is when
doing rapid prototyping of applications to a system where the code needs
to be available for each published iteration of each publish binary.

Conclusion
----------
To avoid unforseen cost of storing old source code, do not publish any
binaries publically without first receiving approval.
