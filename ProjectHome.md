A generic Windows crash dump filter driver illustrating the technique published at No Such Con 2013 to read/write to disk through the crash I/O path by leveraging internal logging functions in crashdmp.sys.  This code was originally used in the Source Boston 2013 CTF, so some of it is specific to the design of that challenge.  Please see http://crashd.mp/?p=58