# bench-sh-2.1
Benchmark Script Version 2.1<br /><br />
Demo Output: http://pastebin.com/QiRCCV8T<br /><br /><br />

Hello, I forked the script over from https://github.com/hidden-refuge who had a nice base bench.sh script. I simply added more mirrors to the list for testing (IPv4 Only) which are also 100MB bin test files.

* Note, Online.net is a 100Mo.dat file, which is roughly ~95.4MB and not a true 100MB bin file. They do not have a 100MB bin/dat file on there website for testing purposes. 

<strong>Parameters</strong><br /><br />
Help Page:<br />
<code>./bench.sh -h</code><br /><br />
System Info + Speedtest IPv4 + Drive Speed:<br />
<code>./bench.sh</code><br />
Classic mode. This will use 1 GB bandwidth!<br /><br />
System Info + Speedtest IPv6 + Drive Speed:<br />
<code>./bench.sh -6</code><br />
IPv6 only speed test. This will use 1 GB bandwidth!<br /><br />
System Info + Speedtest IPv4 & IPv6 + Drive Speed:<br />
<code>./bench.sh -46 or ./bench.sh -64</code><br />
Dual stack speed test. This will use 2 GB bandwidth!<br /><br />
System Info:<br />
<code>./bench.sh -sys</code><br />
System information only.<br /><br />
Drive Speed:<br />
<code>./bench.sh -io</code><br />
Drive speed test via DD only.<br /><br />
System Info + Speedtest IPv4 + Drive Speed + System Benchmark:<br />
<code>./bench.sh -b</code><br />
Classic mode with system benchmark. This will use 1 GB bandwidth!<br /><br />
System Info + Speedtest IPv6 + Drive Speed + System Benchmark:<br />
<code>./bench.sh -b6</code><br />
IPv6 only speed test with system benchmark. This will use 1 GB bandwidth!<br /><br />
System Info + Speedtest IPv4 & IPv6 + Drive Speed + System Benchmark:<br />
<code>./bench.sh -b46 or ./bench.sh -b64</code><br />
Dual stack speed test with system benchmark. This will use 2 GB bandwidth.<br /><br /><br />
<strong>This script is based on bench.sh by akamaras/camarg from <a href="http://www.akamaras.com/linux/linux-server-info-script/">here</a>.</strong><br />
Copyright (C) 2011 by akamaras/camarg<br /><br />
<strong>dmmcinytre3 from FreeVPS has added the speed test.</strong><br />
Copyright (C) 2011 by dmmcinytre3 for the modifications he made<br />
dmmcintyre3's modified version: https://freevps.us/thread-2252.html<br /><br />
Copyright for this (bench-sh-2) (C) 2015 by me (Hidden Refuge)<br /><br />
Copyright for this (bench-sh-2.1) (C) 2016 by me (SavageWS6) (Forked Revision)<br />
