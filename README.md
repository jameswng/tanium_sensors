##Tanium Sensors

I have created three tanium sensors.

I have created two versions (*meminfo_withawk.xml*, *meminfo_withsh.xml*)
of the same sensor, one with bourne shell and one with awk.
The sensors extract some memory values and returns the percent of free real memory and free swap.

The third sensor *passwd_control1.xml* is a little more complicated. It implements a set of validations for the /etc/passwd and /etc/shadow files.
It returns two integers, indicating either a failure of the check or a failure running the check.

