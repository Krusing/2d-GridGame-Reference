# Grid reference

## Render

### Direction

When asking for a new line on the grid, the values tell what side of the grid the new line is to be rendered.

Render direction table:

Direction|||
:-|-:|-:
Up|0|0
Right|0|1
Down|1|1
Left|1|0

## Tile

The order in wich the tiles transition between different material. Side arrangement must line up to create a transition between two tiles.

### Reference

Lineup

![](0-0.png)
![](0-1.png)
![](1-1.png)
![](1-0.png)

||Name
:-:|:-:
![](tile/x00.jpg)|0x00<br>
![](tile/x01.jpg)|0x01<br>
![](tile/x02.jpg)|0x02<br>
![](tile/x03.jpg)|0x03<br>
![](tile/x04.jpg)|0x04<br>
![](tile/x05.jpg)|0x05<br>
![](tile/x06.jpg)|0x06<br>
![](tile/x07.jpg)|0x07<br>
![](tile/x08.jpg)|0x08<br>
![](tile/x09.jpg)|0x09<br>
![](tile/x0A.jpg)|0x0A<br>
![](tile/x0B.jpg)|0x0B<br>
![](tile/x0C.jpg)|0x0C<br>
![](tile/x0D.jpg)|0x0D<br>
![](tile/xFF.jpg)|0xFF

### Arrangement

Tile|Up|Right|Down|Left
:-:|:-:|:-:|:-:|:-:
![](tile/x00.jpg) 0x00|![](tile/x00.jpg) 0x00<br>![](tile/x05.jpg) 0x05<br>![](tile/x06.jpg) 0x06<br>![](tile/x07.jpg) 0x07|![](tile/x00.jpg) 0x00<br>![](tile/x01.jpg) 0x01<br>![](tile/x07.jpg) 0x07<br>![](tile/x08.jpg) 0x08|![](tile/x00.jpg) 0x00<br>![](tile/x01.jpg) 0x01<br>![](tile/x02.jpg) 0x02<br>![](tile/x03.jpg) 0x03|![](tile/x00.jpg) 0x00<br>![](tile/x03.jpg) 0x03<br>![](tile/x04.jpg) 0x04<br>![](tile/x05.jpg) 0x05<br>
![](tile/x01.jpg) 0x01|![](tile/x00.jpg) 0x00<br>![](tile/x05.jpg) 0x05<br>![](tile/x06.jpg) 0x06<br>![](tile/x07.jpg) 0x07|![](tile/x02.jpg) 0x02<br>![](tile/x03.jpg) 0x03<br>![](tile/x0A.jpg) 0x0A|![](tile/x07.jpg) 0x07<br>![](tile/x08.jpg) 0x08<br>![](tile/x0A.jpg) 0x0A|![](tile/x00.jpg) 0x00<br>![](tile/x03.jpg) 0x03<br>![](tile/x04.jpg) 0x04<br>![](tile/x05.jpg) 0x05<br>
![](tile/x02.jpg) 0x02|![](tile/x00.jpg) 0x00<br>![](tile/x05.jpg) 0x05<br>![](tile/x06.jpg) 0x06<br>![](tile/x07.jpg) 0x07|![](tile/x02.jpg) 0x02<br>![](tile/x03.jpg) 0x03<br>![](tile/x0A.jpg) 0x0A|![](tile/x06.jpg) 0x06<br>![](tile/x09.jpg) 0x09<br>![](tile/x0C.jpg) 0x0C<br>![](tile/x0D.jpg) 0x0D|![](tile/x01.jpg) 0x01<br>![](tile/x02.jpg) 0x02<br>![](tile/x0B.jpg) 0x0B<br>
![](tile/x03.jpg) 0x03|![](tile/x00.jpg) 0x00<br>![](tile/x05.jpg) 0x05<br>![](tile/x06.jpg) 0x06<br>![](tile/x07.jpg) 0x07|![](tile/x00.jpg) 0x00<br>![](tile/x01.jpg) 0x01<br>![](tile/x07.jpg) 0x07<br>![](tile/x08.jpg) 0x08|![](tile/x04.jpg) 0x04<br>![](tile/x05.jpg) 0x05<br>![](tile/x0B.jpg) 0x0B|![](tile/x01.jpg) 0x01<br>![](tile/x02.jpg) 0x02<br>![](tile/x0B.jpg) 0x0B<br>
![](tile/x04.jpg) 0x04|![](tile/x03.jpg) 0x03<br>![](tile/x04.jpg) 0x04<br>![](tile/x0C.jpg) 0x0C|![](tile/x00.jpg) 0x00<br>![](tile/x01.jpg) 0x01<br>![](tile/x07.jpg) 0x07<br>![](tile/x08.jpg) 0x08|![](tile/x04.jpg) 0x04<br>![](tile/x05.jpg) 0x05<br>![](tile/x0B.jpg) 0x0B|![](tile/x08.jpg) 0x08<br>![](tile/x09.jpg) 0x09<br>![](tile/x0A.jpg) 0x0A<br>![](tile/x0D.jpg) 0x0D<br>
![](tile/x05.jpg) 0x05|![](tile/x03.jpg) 0x03<br>![](tile/x04.jpg) 0x04<br>![](tile/x0C.jpg) 0x0C|![](tile/x00.jpg) 0x00<br>![](tile/x01.jpg) 0x01<br>![](tile/x07.jpg) 0x07<br>![](tile/x08.jpg) 0x08|![](tile/x00.jpg) 0x00<br>![](tile/x01.jpg) 0x01<br>![](tile/x02.jpg) 0x02<br>![](tile/x03.jpg) 0x03|![](tile/x06.jpg) 0x06<br>![](tile/x07.jpg) 0x07<br>![](tile/x0C.jpg) 0x0C<br>
![](tile/x06.jpg) 0x06|![](tile/x02.jpg) 0x02<br>![](tile/x09.jpg) 0x09<br>![](tile/x0A.jpg) 0x0A<br>![](tile/x0B.jpg) 0x0B|![](tile/x05.jpg) 0x05<br>![](tile/x06.jpg) 0x06<br>![](tile/x0D.jpg) 0x0D|![](tile/x00.jpg) 0x00<br>![](tile/x01.jpg) 0x01<br>![](tile/x02.jpg) 0x02<br>![](tile/x03.jpg) 0x03|![](tile/x06.jpg) 0x06<br>![](tile/x07.jpg) 0x07<br>![](tile/x0C.jpg) 0x0C<br>
![](tile/x07.jpg) 0x07|![](tile/x01.jpg) 0x01<br>![](tile/x08.jpg) 0x08<br>![](tile/x0D.jpg) 0x0D|![](tile/x05.jpg) 0x05<br>![](tile/x06.jpg) 0x06<br>![](tile/x0D.jpg) 0x0D|![](tile/x00.jpg) 0x00<br>![](tile/x01.jpg) 0x01<br>![](tile/x02.jpg) 0x02<br>![](tile/x03.jpg) 0x03|![](tile/x00.jpg) 0x00<br>![](tile/x03.jpg) 0x03<br>![](tile/x04.jpg) 0x04<br>![](tile/x05.jpg) 0x05<br>
![](tile/x08.jpg) 0x08|![](tile/x01.jpg) 0x01<br>![](tile/x08.jpg) 0x08<br>![](tile/x0D.jpg) 0x0D|![](tile/x04.jpg) 0x04<br>![](tile/x09.jpg) 0x09<br>![](tile/x0B.jpg) 0x0B<br>![](tile/x0C.jpg) 0x0C|![](tile/x07.jpg) 0x07<br>![](tile/x08.jpg) 0x08<br>![](tile/x0A.jpg) 0x0A|![](tile/x00.jpg) 0x00<br>![](tile/x03.jpg) 0x03<br>![](tile/x04.jpg) 0x04<br>![](tile/x05.jpg) 0x05<br>
![](tile/x09.jpg) 0x09|![](tile/x02.jpg) 0x02<br>![](tile/x09.jpg) 0x09<br>![](tile/x0A.jpg) 0x0A<br>![](tile/x0B.jpg) 0x0B|![](tile/x04.jpg) 0x04<br>![](tile/x09.jpg) 0x09<br>![](tile/x0B.jpg) 0x0B<br>![](tile/x0C.jpg) 0x0C|![](tile/x06.jpg) 0x06<br>![](tile/x09.jpg) 0x09<br>![](tile/x0C.jpg) 0x0C<br>![](tile/x0D.jpg) 0x0D|![](tile/x08.jpg) 0x08<br>![](tile/x09.jpg) 0x09<br>![](tile/x0A.jpg) 0x0A<br>![](tile/x0D.jpg) 0x0D<br>
![](tile/x0A.jpg) 0x0A|![](tile/x01.jpg) 0x01<br>![](tile/x08.jpg) 0x08<br>![](tile/x0D.jpg) 0x0D|![](tile/x04.jpg) 0x04<br>![](tile/x09.jpg) 0x09<br>![](tile/x0B.jpg) 0x0B<br>![](tile/x0C.jpg) 0x0C|![](tile/x06.jpg) 0x06<br>![](tile/x09.jpg) 0x09<br>![](tile/x0C.jpg) 0x0C<br>![](tile/x0D.jpg) 0x0D|![](tile/x01.jpg) 0x01<br>![](tile/x02.jpg) 0x02<br>![](tile/x0B.jpg) 0x0B<br>
![](tile/x0B.jpg) 0x0B|![](tile/x03.jpg) 0x03<br>![](tile/x04.jpg) 0x04<br>![](tile/x0C.jpg) 0x0C|![](tile/x02.jpg) 0x02<br>![](tile/x03.jpg) 0x03<br>![](tile/x0A.jpg) 0x0A|![](tile/x06.jpg) 0x06<br>![](tile/x09.jpg) 0x09<br>![](tile/x0C.jpg) 0x0C<br>![](tile/x0D.jpg) 0x0D|![](tile/x08.jpg) 0x08<br>![](tile/x09.jpg) 0x09<br>![](tile/x0A.jpg) 0x0A<br>![](tile/x0D.jpg) 0x0D<br>
![](tile/x0C.jpg) 0x0C|![](tile/x02.jpg) 0x02<br>![](tile/x09.jpg) 0x09<br>![](tile/x0A.jpg) 0x0A<br>![](tile/x0B.jpg) 0x0B|![](tile/x05.jpg) 0x05<br>![](tile/x06.jpg) 0x06<br>![](tile/x0D.jpg) 0x0D|![](tile/x04.jpg) 0x04<br>![](tile/x05.jpg) 0x05<br>![](tile/x0B.jpg) 0x0B|![](tile/x08.jpg) 0x08<br>![](tile/x09.jpg) 0x09<br>![](tile/x0A.jpg) 0x0A<br>![](tile/x0D.jpg) 0x0D<br>
![](tile/x0D.jpg) 0x0D|![](tile/x02.jpg) 0x02<br>![](tile/x09.jpg) 0x09<br>![](tile/x0A.jpg) 0x0A<br>![](tile/x0B.jpg) 0x0B|![](tile/x04.jpg) 0x04<br>![](tile/x09.jpg) 0x09<br>![](tile/x0B.jpg) 0x0B<br>![](tile/x0C.jpg) 0x0C|![](tile/x07.jpg) 0x07<br>![](tile/x08.jpg) 0x08<br>![](tile/x0A.jpg) 0x0A|![](tile/x06.jpg) 0x06<br>![](tile/x07.jpg) 0x07<br>![](tile/x0C.jpg) 0x0C<br>


## Row

Example of a row with 10 tiles:

![](tile/x00.jpg)![](tile/x07.jpg)![](tile/x06.jpg)![](tile/x0D.jpg)![](tile/x04.jpg)![](tile/x00.jpg)![](tile/x08.jpg)![](tile/x0B.jpg)![](tile/x02.jpg)![](tile/x03.jpg)

||||||||||||
:-|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:
Offset|0|1|2|3|4|5|6|7|8|9
Tile|0x00|0x07|0x06|0x0D|0x04|0x00|0x08|0x0B|0x02|0x03
Image|![](tile/x00.jpg)|![](tile/x07.jpg)|![](tile/x06.jpg)|![](tile/x0D.jpg)|![](tile/x04.jpg)|![](tile/x00.jpg)|![](tile/x08.jpg)|![](tile/x0B.jpg)|![](tile/x02.jpg)|![](tile/x03.jpg)


✔️❌
