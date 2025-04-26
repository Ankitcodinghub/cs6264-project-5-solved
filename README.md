# cs6264-project-5-solved
**TO GET THIS SOLUTION VISIT:** [CS6264 Project 5 Solved](https://www.ankitcodinghub.com/product/cs6264-project-5-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;126411&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS6264 Project 5 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
“Good work on the IDS design!”

There seems to be a trend in your boss’ tone of voice versus the amount of work he is about to assign to you…

“To further develop your IDS, our clients want you to implement a Network-based IDS to monitor malicious network traffic”

“They want you to set up Snort and analyze any executable files flowing to a client using your new sandbox. ”

Your boss also seems pretty fixated on this two-week cycle, you think as you open up Google and&nbsp;<a href="https://gatech.instructure.com/courses/404614/files/52679773?wrap=1">another tutorial once again</a>

<a href="https://gatech.instructure.com/courses/404614/assignments/1776150?module_item_id=4225304">Actions</a>

.

<strong>&nbsp; Assignment</strong>

The purpose of this assignment is to apply your knowledge of IDS’s learned in class to implement your own network-based IDS to detect malicious executable files in network traffic. Before you get started, please install&nbsp;<a href="https://www.vagrantup.com/">VagrantLinks to an external site.</a>&nbsp;and make sure you have&nbsp;<a href="https://www.virtualbox.org/">VirtualBoxLinks to an external site.</a>&nbsp;installed.

Note: Please download the vagrant file from&nbsp;<a href="https://gatech.instructure.com/courses/404614/files/52679779?wrap=1">Files &gt; Lab Files &gt; Lab 05 &gt; Vagrantfile</a>&nbsp;and the hooks.c file from&nbsp;<a href="https://gatech.instructure.com/courses/404614/files/52679653?wrap=1">Files &gt; Lab Files &gt; Lab 05 &gt; hooks.c</a>&nbsp;instead of the links in the writeup. And here is the same link to the&nbsp;<a href="https://gatech.instructure.com/courses/404614/files/52679781?wrap=1">test_binaries</a><a href="https://gatech.instructure.com/courses/404614/files/52679781/download?download_frd=1">&nbsp;Download test_binaries</a>as in the tutorial.

There are 5-6 steps to this project:

<ol>
<li>Implement&nbsp;<a href="http://manual-snort-org.s3-website-us-east-1.amazonaws.com/">Snort rulesLinks to an external site.</a>&nbsp;so that you will log any packets that are involved in the sending of an executable file</li>
<li>Upon the creation of a log, send the packets to the sandbox (this should be done over FTP, as an FTP client has been installed on the sandbox). This should probably be done using a&nbsp;<a href="https://stackoverflow.com/questions/17954432/creating-a-daemon-in-linux">daemonLinks to an external site.</a>&nbsp;(Please use this link as the link to the blog in the writeup is broken).</li>
<li>Upon receiving the Snort log in the sandbox, reconstruct the executable by extracting it from the log (which is essentially a PCAP file). This should also probably be a daemon.</li>
<li>(You may have to update your LKM rules a little bit so that you are hooking the necessary syscalls)</li>
<li>Run the executable with your Linux Kernel Module and report any issues to the kernel log (this is done already if you used printk())</li>
<li>Generate an IDS alert by tweaking the&nbsp;<a href="https://www.rsyslog.com/doc/v8-stable/configuration/index.html">rsyslog configurationLinks to an external site.</a>&nbsp;so that any of your Linux Kernel Module messages are printed out into another log in /var/log called ids_alerts.log</li>
</ol>
<strong>Points Breakdown:</strong>

– Proof of successful file transfer over FTP:&nbsp;<strong>10 pts</strong>

– Snort rule correctly written:&nbsp;<strong>20 pts</strong>

– Daemon to send file from Vicky to Sandy correctly written:&nbsp;<strong>20 pts</strong>

– LKM updated for new malicious program:&nbsp;<strong>10 pts</strong>

– Daemon written to analyze program on sandy:&nbsp;<strong>20 pts

</strong>– Rsyslogd config correctly written:<strong>&nbsp;10 pts</strong>

– Report:&nbsp;<strong>10 pts</strong>

<strong>Bonus:</strong>

– Analyzed benign file in Sandy transfer back to client Vicky and malicious file get dropped:&nbsp;<strong>5 pts

</strong>&nbsp;– Using Zeek/Bro to detect executable files sent over network and log the binary drop:<strong>&nbsp;5 pts</strong>

<strong>Supplementary Material:</strong>

<a href="https://gatech.instructure.com/courses/404614/files/52679775?wrap=1">Lab 5_Supplementary_Material.pptx</a>

<a href="https://gatech.instructure.com/courses/404614/assignments/1776150?module_item_id=4225304">Actions</a>

&nbsp;

<strong>&nbsp; Deliverables</strong>

<ul>
<li>Zip the following files in a .tar.gz file called [GT username]_cs6264_lab5.tar.gz
<ul>
<li>Snort configuration</li>
<li>Various daemons that you wrote for both the sandbox and the client</li>
<li>Your LKM C file and Makefile</li>
<li>The new rsyslog configuration</li>
</ul>
</li>
<li>A report of your NIDS that includes:
<ul>
<li>Screenshots of each step of the process from when you send the file to the client to when an alert is logged. These should probably include: sending the executable, receiving the executable, alerting the executable, sending the PCAP to the sandbox, the sandbox alerting/not alerting on the executable</li>
<li>Implementation details</li>
</ul>
</li>
</ul>
&nbsp;
