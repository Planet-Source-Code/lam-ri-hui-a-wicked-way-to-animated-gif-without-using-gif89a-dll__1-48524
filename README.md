<div align="center">

## A Wicked Way To Animated GIF Without Using GIF89a\.dll


</div>

### Description

This tutorial shows how to animate gif in your form without using GIF89a.dll
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Lam Ri Hui](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/lam-ri-hui.md)
**Level**          |Beginner
**User Rating**    |4.6 (32 globes from 7 users)
**Compatibility**  |VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Graphics](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/graphics__1-46.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/lam-ri-hui-a-wicked-way-to-animated-gif-without-using-gif89a-dll__1-48524/archive/master.zip)





### Source Code


<pre><font face="Comic Sans MS"><font size="4">Create a new project and click on Components... under Project menu. in the control tab,
scroll down until you see 'Microsoft Internet Control'. Check it and click OK. An icon will appear in the Toolbox. Double click the icon
to insert a control. Then, doucle click the form and insert the following code in Form_Load()
</font>
Webbrowser1.navigate <i>gifpath</i>
Example :</font></Pre><pre><font face="Comic Sans MS">webbrowser1.navigate app.path &amp; &quot;\&quot; &amp;
&quot;quick.gif&quot;
or
webbrowser1.navigate &quot;C:\draw.gif&quot;
</font></Pre><hr><pre><font face="Comic Sans MS"><font size="5">This tutorial ends here
</font>
</font></Pre>

