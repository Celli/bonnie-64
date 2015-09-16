Bonnie, originally written in 1989-90 when I was in the employ of the Oxford English Dictionary project, is a C-language benchmark measuring the performance of Unix filesystems.  There is discussion at http://www.tbray.org/ongoing/misc/Software#p-1

There is another version of Bonnie, Bonnie++, developed by Russell Coker, which appears both at http://www.coker.com.au/bonnie++/ and
http://sourceforge.net/projects/bonnie/ - it is in C++ and includes many tests that Bonnie doesn't.  It works around the 32-bit limit by scattering the data across multiple files.

Bonnie64 is a slight rev of the original Bonnie, designed to run on 64-bit computers.  Also the output is a bit more useful since it reports in M/sec rather than K/sec.  Its construction is discussed at my blog see http://www.tbray.org/ongoing/When/200x/2004/11/16/Bonnie64 and http://www.tbray.org/ongoing/When/200x/2005/12/07/ZFS