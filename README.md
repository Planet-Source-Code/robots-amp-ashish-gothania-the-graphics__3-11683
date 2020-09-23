<div align="center">

## THE GRAPHICS


</div>

### Description

MY CODE PUTS THE GRAPHICAL IMAGE ON YOUR SCREEN WHEN YOU PRESS THE ESC BUTTON.
 
### More Info
 
NO INPUT PARAMETERS

YOU JUST HAVE TO PRESS ESC BUTTON TO RUN IT INTO YOUR C SCREEN...

THE CODE RETURNS ON SCREEN THE MOVING GRAPHICAL IMAGE

NO SIDE EFFECTS JUST FUN...


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[ ROBOTS &amp; ASHISH GOTHANIA](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/robots-amp-ashish-gothania.md)
**Level**          |Beginner
**User Rating**    |5.0 (15 globes from 3 users)
**Compatibility**  |C, C\+\+ \(general\)
**Category**       |[Graphics/ Sound](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/graphics-sound__3-15.md)
**World**          |[C / C++](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/robots-amp-ashish-gothania-the-graphics__3-11683/archive/master.zip)

### API Declarations

NO FILES


### Source Code

```
#INCLUDE<STDIO.H>
#INCLUDE<CONIO.H>
#INCLUDE<MATH.H>
#INCLUDE<GRAPHICS.H>
#INCLUDE<DOS.H>
VOID MAIN(); *//here is ASHISH GOTHANIA//*
{
int gd=DETECT,gm,a,b,c,d,maxx,maxy,i,j;
clrscr();
initgraph(&gd,&gm,"C:\tc\bgi");
maxx=getmaxx();
maxy=getmaxy();
for(i=0;i<640;i++)
{
setcolor(GREEN);
circle(maxx,maxy,i^2);
setcolor(RED);
circle(i,i,i^2);
getch();
}
for(j=640;j>0;j--)
{
setcolor(ORANGE);
circle(j,j,640/j);
setcolor(BLUE);
circle(j,j/640,j);
getch();
}
delay(10);
closegraph();
}
```

