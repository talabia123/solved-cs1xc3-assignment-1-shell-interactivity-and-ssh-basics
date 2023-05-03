Download Link: https://assignmentchef.com/product/solved-cs1xc3-assignment-1-shell-interactivity-and-ssh-basics
<br>
Primary Learning Objectives

<ul>

 <li>Use Unix shell commands to conduct work such as file management, search operations, etc.</li>

 <li>Access machines remotely using SSH.</li>

</ul>

<strong> </strong>

<h1>Requirements</h1>




<h2>Part A</h2>

For each question below provide the Unix command or sequence of commands that when entered into a Bash shell will produce the desired result in the current working directory.  You may need to research some specific information about commands beyond what we covered in the slides (e.g. use a command’s man page, or search online), but you should not need any commands that we didn’t already cover in lecture or lab.

Question 1 –

Give a series of commands that will:

<ol>

 <li>Create a blank file called <em>txt </em></li>

 <li>Create an empty subfolder called <em>folder</em></li>

 <li>Put a copy of <em>txt</em> named <em>filecopy.txt </em>into the subfolder <em>folder</em></li>

</ol>

<h3>Question 2</h3>

Give a single command that will print the operating system (i.e. kernel) version (and <strong><em>only</em></strong> the operating system version).

Question 3 – 10 marks

Give a <strong><em>single command </em></strong>that will create all subfolders in this path of subfolders: /test1/test2/test3 in the current working directory.  Assume that none of the subfolders in the path exist before the command is run.  (<strong>Hint:</strong> check out the mkdir man page…).

Question 4

Give the single OpenSSH command for connecting to a server with the hostname <em>mcmasterserver.com</em> and the username <em>lovelacea</em>.

Question 5

On a remote computer with hostname <em>mcmasterserver.com</em> the user <em>hopperg</em> has a home directory with a subfolder named <em>documents</em>, which contains a file <em>important.doc</em>.  On the local computer the parent directory of the current working directory has a subfolder named code.  <em> </em>

Give a single command that will transfer the <em>important.doc</em> file on the remote computer to the code folder on the local computer.

Question 6

Write a single command that will find all occurrences of <strong><em>any </em></strong>of the following items contained in any file in the current working directory that ends with the extension .csv.  Hint: You’ll want to use | as part of a regular expression.

<ul>

 <li><strong>ERROR###</strong> where # is a digit between 0 and 5 o <strong>ERROR123 </strong>would match o <strong>ERROR945 </strong>would not match

  <ul>

   <li><strong>ERROR1239 </strong>would contain a match (the first 8 characters still match!)</li>

  </ul></li>

 <li><strong>XXX, XXXX, XXXXX, XXXXXX, XXXXXXX, XXXXXXXX, XXXXXXXXX</strong> o In other words, between three and nine X characters in a row.

  <ul>

   <li><strong>X </strong>would not match o <strong>XXX</strong> would match</li>

   <li><strong>XXXXXXXXXX </strong>– 10 X characters in a row would contain a match (the first 9 characters still match!)</li>

  </ul></li>

 <li>The text <strong>ALERT</strong> followed by 1 or more of any character that is not X or Y o <strong>ALERTA</strong> would match o <strong>ALERTABC</strong> would match

  <ul>

   <li><strong>ALERTX</strong> would not match o <strong>ALERTY </strong>would not match</li>

   <li><strong>ALERTABCX</strong> would contain a match (the first 8 characters still match!)</li>

  </ul></li>

</ul>

<h2>Part B</h2>

<h3>Question 7</h3>

Using your account on pascal, create a folder called /public_html in your home directory.  Place or create an HTML file called cs1xc3.html in the folder with the following content:




&lt;html&gt;

&lt;head&gt;

&lt;title&gt;CS1XC3 Assignment #1&lt;/title&gt;

&lt;/head&gt;

&lt;body&gt;

&lt;h1&gt; MacID &lt;/h1&gt;

&lt;/body&gt;

&lt;/html&gt;




Where MacID is replaced with your MacID.  The file should be accessible in a browser at the URL: <strong>https://pascal.cas.mcmaster.ca/~</strong><strong>MacID/cs1xc3.html</strong> where MacID is your MacID.

After completing the above, provide this URL as your answer to this question, we will verify you have placed the file at this location by checking the URL.







<h2>Bonus</h2>

You do not need to complete this question, it is optional.

<h3>Question 8 – 20 marks</h3>

Find a Unix shell command (which we did not cover in-class) that will identify the differences between the contents of two files.  What is the command?  Explain how the command works using an example.  (Do not attach additional files to your submission, you can just put the file contents in your regular submission file).




This assignment is marked out of 100 total, see individual questions for the weight of each.  If your grade exceed 100 marks due to the bonus question, you will receive 100 marks total (though of course, answering the bonus question can help ensure you reach 100 marks total).


