<div align="center">

## Random Picture Generator


</div>

### Description

This code simply generate a random picture and display. It also teaches beginners about random numbers.
 
### More Info
 
Create some pictures and name them as "pic1.jpg, "pic2.jpg", and so on. Enter the LowerBound and UpperBound of the picture number.

Displays a random picture.

The picture names are static.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Yu Chang](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/yu-chang.md)
**Level**          |Beginner
**User Rating**    |4.7 (14 globes from 3 users)
**Compatibility**  |ASP \(Active Server Pages\), HTML
**Category**       |[Graphics/ Sound](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/graphics-sound__4-15.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/yu-chang-random-picture-generator__4-6403/archive/master.zip)





### Source Code

```
<HTML>
<HEAD>
<TITLE>Random Generated Picture</TITLE>
</HEAD>
<BODY>
<!--Copy starting from here-->
<CENTER>
<%
	Randomize
	Dim RandomNum, UpperBound, LowerBound
	LowerBound = 1 'Put in the first picture #
	UpperBound = 10 'Put in the last picture #
	RandomNum = Int((UpperBound - LowerBound + 1) * Rnd + LowerBound)
%>
<IMG SRC="pic<% = RandomNum %>.jpg">
</CENTER>
<!--Copy end here-->
</BODY>
</HTML>
```

