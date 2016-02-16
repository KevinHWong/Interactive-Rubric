<!doctype html>
<head>

<style type="text/css"/>
    table tr {
    text-align:center;
    background-color:white;
}
.highlight {
    background-color:lime
}
.highlight1 {
    background-color:gold
}
.highlight2 {
    background-color:orange
}
.highlight3 {
    background-color:red
}
.highlight4 {
    background-color:white
}
</style>

</head>
<body>



<script type="text/javascript">





function ChangeColor(elem) {
    if (elem.className != "highlight") {
        elem.className = "highlight";
    } else {
        elem.className = "";
    }
}

function ChangeColor1(elem) {
if (elem.className != "highlight1") {
        elem.className = "highlight1";
    } else {
        elem.className = "";
    }
}

function ChangeColor2(elem) {
if (elem.className != "highlight2") {
        elem.className = "highlight2";
    } else {
        elem.className = "";
    }
}

function ChangeColor3(elem) {
if (elem.className != "highlight3") {
        elem.className = "highlight3";
    } else {
        elem.className = "";
    }
}

function ChangeColor4(elem) {
if (elem.className != "highlight4") {
        elem.className = "highlight4";
    } else {
        elem.className = "";
    }
}




function valueChanged(elem) {
    if (document.getElementById("A").checked == true) {
        document.getElementById("A").value = 1;
        document.getElementById("B").value = 0;
    } if (document.getElementById("B").checked == true) {
        document.getElementById("A").value = 0;
        document.getElementById("B").value = 1;
    } if (document.getElementById("A").checked == true) {
    	
    }
    console.log(document.getElementById("A").value);
    console.log(document.getElementById("B").value)
}

		







</script>




<table id="Table" style="width:90%; margin:auto" border="2" width="1400" cellpadding="10" cellspacing="5">
	

	<tr id="A">
		<td></td>
		<td>3</td>
		<td>2</td>
		<td>1</td>
		<td>0</td>
	</tr>
	
	<tr id="B">
		<th>Author:<br />What are the author's credentials and affiliation? Is the author an expert?</th>
		<td onClick="ChangeColor(this);" onChange="valueChanged();">
						The author's credentials indicate that he/she is an expert on this topic. The author gives contact info or professional affiliation.
						<br /><input type="radio" name="A" id="A" onchange="valueChanged()" /><br>

					</td> 
		<td onClick="ChangeColor1(this);">			The author is named but credentials and/or contact info (online sources) is incomplete. <br /><input type="radio" name="A" id="B" onchange="valueChanged()"/><br></td>
		
		<td onClick="ChangeColor2(this);">
						The author is unnamed and/or no credentials are given.<br /><input type="radio" name="A" id="C" onchange="valueChanged()"/><br>
</td>
		
		<td onClick="ChangeColor3(this);">			The author is named, but is clearly not an expert on the topic (published by student or fans). <br /><input type="radio" name="A" id="D" onchange="valueChanged()"/><br></td>
	</tr>

	<tr id="C">
		<th>Publisher:<br />Is the source published by a reputable publisher or organization?
</th>
		<td onClick="ChangeColor(this);">
Published by:


*U.S. Government (.gov)
*Scholarly Journal


or


in a Reference or academic book
<br /><input type="radio" name="B" id="E" onchange="valueChanged()" /><br>
</td>
		
		<td onClick="ChangeColor1(this);">Published by a known:


*organization
*university
*business
*magazine/newspaper
or
   in a print book <br /><input type="radio" name="B" id="F" onchange="valueChanged()" /><br> </td>

		<td onClick="ChangeColor2(this);">
Published by:


*a K-12 school


*an unknown business(.com)


*an unknown organization (.org).
<br /><input type="radio" name="B" id="G" onchange="valueChanged()" /><br>
</td>

		<td onClick="ChangeColor3(this);">

Self-published:

blogs, personal web pages, etc.


Look for the symbols ~% or the words "users" "members" etc. in the URL
<br /><input type="radio" name="B" id="H" onchange="valueChanged()" /><br>
</td>
	
	</tr>
	
	<tr id="D">
		<th>Sources Sited:<br />Is the information cited?
</th>
		<td onClick="ChangeColor(this);">
								The work is original research/info by a reputable source.  There is a Works Cited list and/or a Bibliography.<br /><input type="radio" name="C" id="I" onchange="valueChanged()" /><br>
</td>
		<td onClick="ChangeColor1(this);">
								The work is a compilation of research/info by a reputable source. No Works Cited information as a list.<br /><input type="radio" name="C" id="J" onchange="valueChanged()" /><br>
</td>
		<td onClick="ChangeColor2(this);">
								There is a statement about the source of information embedded in the source, but no Works Cited list.<br /><input type="radio" name="C" id="K" onchange="valueChanged()" /><br>
</td>
		<td onClick="ChangeColor3(this);">
								No indication of where the information came from.<br /><input type="radio" name="C" id="L" onchange="valueChanged()" /><br>
</td>
	</tr>
	
	
	<tr id="E">
		<th>Purpose:<br />Why was this information published?
</th>
		<td onClick="ChangeColor(this);">To promote scholarly research.<br /><input type="radio" name="D" id="M" onchange="valueChanged()" /><br>	</td>
		<td onClick="ChangeColor1(this);">
							To provide factual information. Some opinion may be included.<br /><input type="radio" name="D" id="N" onchange="valueChanged()" /><br>
</td>
		<td onClick="ChangeColor2(this);">
							To sell something, to persuade, or to promote an idea.<br /><input type="radio" name="D" id="O" onchange="valueChanged()" /><br>
</td>
		<td onClick="ChangeColor3(this);">
							For personal or entertainment purposes.<br /><input type="radio" name="D" id="P" onchange="valueChanged()" /><br>
</td>
	</tr>
	<tr id="F">
		
		<th >Date:<br />How current is the information?
</th>
		<td onClick="ChangeColor(this);">
Online:
The info is less than 1 year old.


Print:
The info is less than 3 years old.
<br /><input type="radio" name="E" id="Q" onchange="valueChanged()" /><br>
</td>
		<td onClick="ChangeColor1(this);">
Online: 
The info is less than 3 years old.


Print:
The information is more than 3 years old, but is not necessarily out of date.<br /><input type="radio" name="E" id="R" onchange="valueChanged()" /><br>
</td>
		<td onClick="ChangeColor2(this);">
The information is more than five years old.<br /><input type="radio" name="E" id="S" onchange="valueChanged()" /><br>
</td>
		<td onClick="ChangeColor3(this);">
There is no indication of when the information was published.<br /><input type="radio" name="E" id="T" onchange="valueChanged()" /><br>
</td>
	</tr>
	
	<tr id="G">
		<th>Substance:</th>
		<td onClick="ChangeColor(this);">
				Depth of coverage needed for your purpose and written at a college or professional level.<br /><input type="radio" name="F" id="U" onchange="valueChanged()" /><br>
</td>
		<td onClick="ChangeColor1(this);">
				Written for the general public.<br /><input type="radio" name="F" id="V" onchange="valueChanged()" /><br>
</td>
		<td onClick="ChangeColor2(this);">
				Lacking the depth needed for your purpose.<br /><input type="radio" name="F" id="W" onchange="valueChanged()" /><br>
</td>
		<td onClick="ChangeColor3(this);">
				No depth, contains excessive colloquialisms, slang, use of "I"<br /><input type="radio" name="F" id="X" onchange="valueChanged()" /><br>
</td>
	</tr>
</table>


	



</body>
<html>
