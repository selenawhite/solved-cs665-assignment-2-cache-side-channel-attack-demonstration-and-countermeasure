Download Link: https://assignmentchef.com/product/solved-cs665-assignment-2-cache-side-channel-attack-demonstration-and-countermeasure
<br>
The programming assignment is designed to ensure that you are acquainted with the working principle of CPU Cache and its related security issues. In this assignment you are going to perform side channel attack on the CPU cache and last-level cache (LLC) and to exploit its vulnerability to leak information.

<strong>[You must be kidding: 3 points]</strong> Prior to perform your own attack, you are urged to emulate <strong>“FLUSH+RELOAD”</strong> attack to get familiarized with the methodologies. The details about the attack is available in the web-link <u><a href="https://github.com/IAIK/cache_template_attacks">https://github.com/IAIK/cache_template_attack</a></u><u>​ </u><u><a href="https://github.com/IAIK/cache_template_attacks">s</a></u><a href="https://github.com/IAIK/cache_template_attacks">.</a><u>​</u> You will find FLUSH+RELOAD attacks performed over multiple applications, viz. Automated keypress profiling on “gedit”, OpenSSL AES T-table attack.

Once you have acquired the knowledge, begin with the following task lists.

<ol>

 <li><strong>[Hmmm. makes sense: 4 points] </strong>Perform​ <strong>PRIME+PROBE</strong>​ attack on L1 Dcache by running two threads in an SMT core. Mimic the similar approach used in <strong>“FLUSH+RELOAD”</strong> keypress profiling in “gedit”. You can use your own PC/laptop for the hardware framework.</li>

 <li><strong>[Hmmm. makes sense: 6 points] </strong>​In ​<strong>Task A</strong> it is limited to L1 and/or L2 cache that happens to be in the same core for a particular CPU. Overcome the limitation of the attack by performing over ​<strong>LLC</strong> that is shared across multiple cores. Try attacking an application called GnuPG (version 1.4.13).</li>

 <li><strong>[It’s easy right: 3 points] </strong>​Mount the ​<strong>Task B </strong>​on the gem5 simulator. Get visualization of the attack vector and its effect on LLC latency. Also, show the cache block addresses of interest through which the information get leaked.</li>

 <li><strong>[OK, no big deal: 4 points]</strong> Propose a mitigation method to combat attack done in <strong>Task</strong>​<strong> A</strong> and ​<strong>Task B</strong>​. Biswa will talk about mitigation techniques in class. Implement any of them.</li>

</ol>




<strong>[Note: All the task(s) has to be be done on Linux Operating System. We will accept your submission via Canvas only, and other submission mode is strictly prohibited such as submitting via email or piazza. While using Piazza/email, use PA1 in the header] </strong>