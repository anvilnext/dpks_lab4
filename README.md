# dpks_lab4
This is a repository for Laboratory Work #4 for DPKS.

"<b>lab4</b>" contains files for Basic task, and "<b>lab4_advanced</b>" contains files for Advanced task.

The param for both projects to check the hello function is "<b>p</b>". To test it, use "insmod hello.ko p=0", where 0 is the specified value. The output for different values:<br>
&nbsp;&nbsp;&nbsp;&nbsp;• <b>0, 5-10</b> - "Warning, continuing.."<br>
&nbsp;&nbsp;&nbsp;&nbsp;• <b>1-4</b> - "Hello, world!" printed that number of times that you've specified.<br>
&nbsp;&nbsp;&nbsp;&nbsp;• <b>>10</b> - "Error, exiting.."<br>
