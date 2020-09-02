<p align=center>
	<img src="https://raw.githubusercontent.com/ryeenii/dotnii-st/master/readme/dotnii.png" width="300">
</p>
<p align=center>
	<img src="https://raw.githubusercontent.com/ryeenii/dotnii-st/master/readme/dotnii-st.png" width="250">
</p>
<h1 align=center>
dotnii - st
</h1>
<h4 align=center>
<i>
Also known as the "Friendship Absurdly Destroyed with URxvt" terminal.
</i>
</h4>
<br> 
<h2 align=center> Contents: </h2>
<ol align=center>	
	<li> Overview</li>	
	<li> Installation</li>
</ol> 
<h2 align=center> Overview </h2> 
<p align=center> 
	This is a fork of suckless' st (simple terminal) program, mainly made to substitute my daily-usage terminal emulator for the past few months, rxvt-unicode. The main reason for this subtle change is mainly because of simplicity in questions of how patches are handled in suckless content and also because of a pleothra of issues I was having in the past with rxvt-unicode as a whole. 
	<br> 
	After a few hours trying to understand it's patches and applying some additional fixes, Hopefully, It was worth the hop! 
</p> 
<h2 align=center> Installation </h2> 
<p align=center> 
	Installing this fork shouldn't be that difficult. In fact, I even commited some small things in order to help you out on the process. 
	<br> 
	<br> 
	Clone the project using: <code> git clone https://github.com/ryeenii/dotnii-st</code>
	</p>
	And then to make/compile the binary, just use <code>make</code>.   
	<br>   
	In order to make it easier to apply additional patches or change some of the configuration files, there is a really simple script in the repo that removes the existing config.h (keeping only your edited config.def.h), compiles and installs the package immediatly.  
	<br>  
	You can execute it by running: <code>./stmake</code> .
	</p>
