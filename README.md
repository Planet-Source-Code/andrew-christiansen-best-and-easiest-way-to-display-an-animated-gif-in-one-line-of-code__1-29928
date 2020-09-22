<div align="center">

## Best AND easiest way to display an Animated GIF in ONE LINE OF CODE


</div>

### Description

OK well all know that the webbrowser control can display animated GIFs? But you really dont want to use that because of that ugly scrollbar on the side, or what about the top and left margins? This gets rid of those 3 annoying things. What you are doing in this is typing direct HTML into the webbrowser control, instead of directly pointing it to the image. With this you can set margins or scrollbar visability.
 
### More Info
 
Just add the Microsoft Internet Controls component.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Andrew Christiansen](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/andrew-christiansen.md)
**Level**          |Beginner
**User Rating**    |4.8 (24 globes from 5 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Graphics](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/graphics__1-46.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/andrew-christiansen-best-and-easiest-way-to-display-an-animated-gif-in-one-line-of-code__1-29928/archive/master.zip)





### Source Code

```
WebBrowser1.Navigate &quot;about:&lt;html&gt;&lt;body scroll='no'&gt;&lt;BODY TOPMARGIN='0'
LEFTMARGIN='0' MARGINWIDTH='0' MARGINHEIGHT='0'&gt;&lt;img scr='LOCATION OF GIF'&gt;&lt;/img&gt;&lt;/body&gt;&lt;/html&gt;&quot;</p>
```

