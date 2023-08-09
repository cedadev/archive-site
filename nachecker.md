--- 
permalink: /nachecker
layout: base_ceda
title: Dataex NASA-Ames file format checker
---



<h1>Dataex NASA-Ames file format checker</h1>

This form allows you to run the dataex program which checks for NASA-Ames format
compliance. This program was written by S.E.Gaines, NASA Ames Research Center.
<p>
To check your file, please enter the file name in the box below then press
<em>Check file</em>. You can use the <em>Browse...</em> button to help you 
select the file. 
<p>
For details of the NASA-Ames format, including help on error messages produced
by this checking program, go to the 
<a href="http://cedadocs.ceda.ac.uk/73/4/index.html">NASA Ames format</a> page.
<p>
<form METHOD="post"  ENCTYPE="multipart/form-data">
<input TYPE="hidden" NAME="mission" VALUE="y"/>
<table>
<tr>
<td>File:</td>
<td><input TYPE="file" NAME="upload" VALUE="" SIZE=40></td>
<td><input TYPE="submit" NAME="submit" VALUE="Check file"></td>
</tr>
</table>
</form>
</p>
