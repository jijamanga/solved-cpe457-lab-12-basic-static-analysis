Download Link: https://assignmentchef.com/product/solved-cpe457-lab-12-basic-static-analysis
<br>
<strong>Lab Description: </strong>The goal of this lab is to provide an application of the basic static analysis techniques and tools discussed in the lecture. Basic static analysis allows you to identify malicious files, begin to understand it’s behavior and share threat information.

<strong>Lab Environment:</strong> It’s recommended that a safe VM environment from be used. In addition, the REMnux Linux distribution (<a href="https://remnux.org/">https://remnux.org/</a>) may also be used, this Linux distribution comes pre-configured with many of the tools needed for this lab.

<strong>Lab Files that are Needed: </strong>The files required will be provided in the accompanying archive, 02_BasicStaticAnalysis.zip. The archive is password protected with the password: <em>infected</em>

<h3><strong>Lab Exercise 1:</strong></h3>

Using the following sample, “keylogger.exe”, answer these questions. Each question should include a screenshot, and brief explanation of it.

<ol>

 <li>Using a strings utility such as strings from a command line or the strings window in IDA Pro; what strings can you find that you think are relevant?</li>

 <li>Using a hashing utility, create an MD5 hash of the program, what is the hash value? Use this hash to find additional information about the sample on VirusTotal, what are the results?</li>

 <li>Now create a SHA256 and SHA512 hash, what are they?</li>

</ol>

<h3><strong>LAB EXERCISE 2:</strong></h3>

This exercise will utilize the REMnux VM found at <a href="https://remnux.org">https://remnux.org</a> and require you to create custom Clam-AV signatures.

<ol>

 <li>Create an ASCII-based signature based off of a custom program that you create. Show the results of scanning your custom program with Clam-AV from a terminal, the results should clearly demonstrate that Clam-AV identifies your sample program as malicious.</li>

</ol>