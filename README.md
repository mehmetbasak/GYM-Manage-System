# GYM-Management-System
<p dir="auto">Gym Management In Java ( JFrame - Mysql )</p>
<p dir="auto">First of all , dowload two material at below.</p>
<p dir="auto">&nbsp;</p>
<p dir="auto"><strong>1- JCalendar&nbsp;</strong>-<a href="http://www.java2s.com/Code/Jar/j/Downloadjcalendar14jar.htm" rel="nofollow">http://www.java2s.com/Code/Jar/j/Downloadjcalendar14jar.htm</a></p>
<p dir="auto"><strong>2- Mysql Connector&nbsp;</strong>-<a href="https://dev.mysql.com/downloads/connector/j/" rel="nofollow">https://dev.mysql.com/downloads/connector/j/</a></p>
<p dir="auto">&nbsp;</p>
<p dir="auto"><span style="text-decoration: underline;">I just created " Payment " interface. I did not connect with DB.</span></p>
<p dir="auto">&nbsp;</p>
<p dir="auto"><strong>Create Database whic is name " gymdb "</strong></p>
<p dir="auto">Create three table whic are name " <strong><span style="text-decoration: underline;">coachTbl</span></strong> " , " <span style="text-decoration: underline;"><strong>financeTbl</strong></span> " , " <span style="text-decoration: underline;"><strong>memberTbl</strong> </span>"</p>
<p dir="auto">-Create 6 columns under the " coachTbl " table</p>
<ul style="list-style-type: square;">
<li dir="auto">CId (PRI, int)</li>
<li dir="auto">CName (varchar)</li>
<li dir="auto">CPhone (varchar)</li>
<li dir="auto">CAge (int)</li>
<li dir="auto">CAddress (varchar)</li>
<li dir="auto">CGen (varchar)</li>
</ul>
<p dir="auto">-Create 8 columns under the "<span style="text-decoration: underline;"><strong> memberTbl</strong></span> " table</p>
<ul style="list-style-type: square;">
<li dir="auto">MId (PRI, int)</li>
<li dir="auto">Mname (varchar)</li>
<li dir="auto">MPhone (varchar)</li>
<li dir="auto">MAge (int)</li>
<li dir="auto">MAmount (int)</li>
<li dir="auto">MTiming (varchar)</li>
<li dir="auto">MCoach (varchar)</li>
<li dir="auto">MGen (varchar)</li>
</ul>
<p dir="auto">-Create 4 columns under the " <span style="text-decoration: underline;"><strong>financeTbl</strong></span> " table</p>
<ul style="list-style-type: square;">
<li dir="auto">PId (PRI, int)</li>
<li dir="auto">PPeriod (varchar)</li>
<li dir="auto">PMember (varchar)</li>
<li dir="auto">PAmount (int)</li>
</ul>





