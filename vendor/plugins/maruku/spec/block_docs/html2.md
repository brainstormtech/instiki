Write a comment here
*** Parameters: ***
{} # params 
*** Markdown input: ***
One
<div></div>123

<div></div>123
*** Output of inspect ***
md_el(:document,[
	md_par(["One ", md_html("<div></div>"), "123"]),
	md_html("<div></div>")
],{},[])
*** Output of to_html ***
<p>One <div></div>123</p>
<div></div>
*** Output of to_latex ***
One 123
*** Output of to_md ***
One 123
*** Output of to_s ***
One 123
