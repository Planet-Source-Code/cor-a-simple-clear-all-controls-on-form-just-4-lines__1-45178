<div align="center">

## A simple Clear All Controls on Form \-\- Just 4 Lines\!


</div>

### Description

Need to perform the same action on multiple controls in your form? Then this simple code might just be for you..

This particular example will show you the most efficient way to clear every text box on a form.

This method can be especially useful if you're adding and removing controls during the development of a project.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Cor\!](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/cor.md)
**Level**          |Beginner
**User Rating**    |4.4 (131 globes from 30 users)
**Compatibility**  |VB 6\.0
**Category**       |[Libraries](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/libraries__1-49.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/cor-a-simple-clear-all-controls-on-form-just-4-lines__1-45178/archive/master.zip)





### Source Code

<br><br>I guessed there must be a better way than hard-coding each control name, but I searched PSC and couldn't find anything to do the job. So after I worked it out I felt this simple method should be added to PSC so those who don't already know how to do it can benefit too.
<br><br>
<br><blue>Dim <black>Control <blue>As <black>Control
<br><blue>For Each <black>Control <blue>In <black>Me
<br> <blue>If TypeOf <black>Control <blue>Is <black>TextBox <blue>Then <black>Control.Text = ""
<br><blue>Next <black>Control
<br><br><br>Please vote if you learnt something useful.<br><br><red>Cor!™<black><br><br>

