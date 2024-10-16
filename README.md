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
![](tile_x00.jpg)|0x00<br>
![](tile_x01.jpg)|0x01<br>
![](tile_x02.jpg)|0x02<br>
![](tile_x03.jpg)|0x03<br>
![](tile_x04.jpg)|0x04<br>
![](tile_x05.jpg)|0x05<br>
![](tile_x06.jpg)|0x06<br>
![](tile_x07.jpg)|0x07<br>
![](tile_x08.jpg)|0x08<br>
![](tile_x09.jpg)|0x09<br>
![](tile_x0A.jpg)|0x0A<br>
![](tile_x0B.jpg)|0x0B<br>
![](tile_x0C.jpg)|0x0C<br>
![](tile_x0D.jpg)|0x0D<br>
![](tile_xFF.jpg)|0xFF

### Arrangement

Tile|Up|Right|Down|Left
:-:|:-:|:-:|:-:|:-:
![](tile_x00.jpg) 0x00|![](tile_x00.jpg) 0x00<br>![](tile_x05.jpg) 0x05<br>![](tile_x06.jpg) 0x06<br>![](tile_x07.jpg) 0x07|![](tile_x00.jpg) 0x00<br>![](tile_x01.jpg) 0x01<br>![](tile_x07.jpg) 0x07<br>![](tile_x08.jpg) 0x08|![](tile_x00.jpg) 0x00<br>![](tile_x01.jpg) 0x01<br>![](tile_x02.jpg) 0x02<br>![](tile_x03.jpg) 0x03|![](tile_x00.jpg) 0x00<br>![](tile_x03.jpg) 0x03<br>![](tile_x04.jpg) 0x04<br>![](tile_x05.jpg) 0x05<br>
![](tile_x01.jpg) 0x01|![](tile_x00.jpg) 0x00<br>![](tile_x05.jpg) 0x05<br>![](tile_x06.jpg) 0x06<br>![](tile_x07.jpg) 0x07|![](tile_x02.jpg) 0x02<br>![](tile_x03.jpg) 0x03<br>![](tile_x0A.jpg) 0x0A|![](tile_x07.jpg) 0x07<br>![](tile_x08.jpg) 0x08<br>![](tile_x0A.jpg) 0x0A|![](tile_x00.jpg) 0x00<br>![](tile_x03.jpg) 0x03<br>![](tile_x04.jpg) 0x04<br>![](tile_x05.jpg) 0x05<br>
![](tile_x02.jpg) 0x02|![](tile_x00.jpg) 0x00<br>![](tile_x05.jpg) 0x05<br>![](tile_x06.jpg) 0x06<br>![](tile_x07.jpg) 0x07|![](tile_x02.jpg) 0x02<br>![](tile_x03.jpg) 0x03<br>![](tile_x0A.jpg) 0x0A|![](tile_x06.jpg) 0x06<br>![](tile_x09.jpg) 0x09<br>![](tile_x0C.jpg) 0x0C<br>![](tile_x0D.jpg) 0x0D|![](tile_x01.jpg) 0x01<br>![](tile_x02.jpg) 0x02<br>![](tile_x0B.jpg) 0x0B<br>
![](tile_x03.jpg) 0x03|![](tile_x00.jpg) 0x00<br>![](tile_x05.jpg) 0x05<br>![](tile_x06.jpg) 0x06<br>![](tile_x07.jpg) 0x07|![](tile_x00.jpg) 0x00<br>![](tile_x01.jpg) 0x01<br>![](tile_x07.jpg) 0x07<br>![](tile_x08.jpg) 0x08|![](tile_x04.jpg) 0x04<br>![](tile_x05.jpg) 0x05<br>![](tile_x0B.jpg) 0x0B|![](tile_x01.jpg) 0x01<br>![](tile_x02.jpg) 0x02<br>![](tile_x0B.jpg) 0x0B<br>
![](tile_x04.jpg) 0x04|![](tile_x03.jpg) 0x03<br>![](tile_x04.jpg) 0x04<br>![](tile_x0C.jpg) 0x0C|![](tile_x00.jpg) 0x00<br>![](tile_x01.jpg) 0x01<br>![](tile_x07.jpg) 0x07<br>![](tile_x08.jpg) 0x08|![](tile_x04.jpg) 0x04<br>![](tile_x05.jpg) 0x05<br>![](tile_x0B.jpg) 0x0B|![](tile_x08.jpg) 0x08<br>![](tile_x09.jpg) 0x09<br>![](tile_x0A.jpg) 0x0A<br>![](tile_x0D.jpg) 0x0D<br>
![](tile_x05.jpg) 0x05|![](tile_x03.jpg) 0x03<br>![](tile_x04.jpg) 0x04<br>![](tile_x0C.jpg) 0x0C|![](tile_x00.jpg) 0x00<br>![](tile_x01.jpg) 0x01<br>![](tile_x07.jpg) 0x07<br>![](tile_x08.jpg) 0x08|![](tile_x00.jpg) 0x00<br>![](tile_x01.jpg) 0x01<br>![](tile_x02.jpg) 0x02<br>![](tile_x03.jpg) 0x03|![](tile_x06.jpg) 0x06<br>![](tile_x07.jpg) 0x07<br>![](tile_x0C.jpg) 0x0C<br>
![](tile_x06.jpg) 0x06|![](tile_x02.jpg) 0x02<br>![](tile_x09.jpg) 0x09<br>![](tile_x0A.jpg) 0x0A<br>![](tile_x0B.jpg) 0x0B|![](tile_x05.jpg) 0x05<br>![](tile_x06.jpg) 0x06<br>![](tile_x0D.jpg) 0x0D|![](tile_x00.jpg) 0x00<br>![](tile_x01.jpg) 0x01<br>![](tile_x02.jpg) 0x02<br>![](tile_x03.jpg) 0x03|![](tile_x06.jpg) 0x06<br>![](tile_x07.jpg) 0x07<br>![](tile_x0C.jpg) 0x0C<br>
![](tile_x07.jpg) 0x07|![](tile_x01.jpg) 0x01<br>![](tile_x08.jpg) 0x08<br>![](tile_x0D.jpg) 0x0D|![](tile_x05.jpg) 0x05<br>![](tile_x06.jpg) 0x06<br>![](tile_x0D.jpg) 0x0D|![](tile_x00.jpg) 0x00<br>![](tile_x01.jpg) 0x01<br>![](tile_x02.jpg) 0x02<br>![](tile_x03.jpg) 0x03|![](tile_x00.jpg) 0x00<br>![](tile_x03.jpg) 0x03<br>![](tile_x04.jpg) 0x04<br>![](tile_x05.jpg) 0x05<br>
![](tile_x08.jpg) 0x08|![](tile_x01.jpg) 0x01<br>![](tile_x08.jpg) 0x08<br>![](tile_x0D.jpg) 0x0D|![](tile_x04.jpg) 0x04<br>![](tile_x09.jpg) 0x09<br>![](tile_x0B.jpg) 0x0B<br>![](tile_x0C.jpg) 0x0C|![](tile_x07.jpg) 0x07<br>![](tile_x08.jpg) 0x08<br>![](tile_x0A.jpg) 0x0A|![](tile_x00.jpg) 0x00<br>![](tile_x03.jpg) 0x03<br>![](tile_x04.jpg) 0x04<br>![](tile_x05.jpg) 0x05<br>
![](tile_x09.jpg) 0x09|![](tile_x02.jpg) 0x02<br>![](tile_x09.jpg) 0x09<br>![](tile_x0A.jpg) 0x0A<br>![](tile_x0B.jpg) 0x0B|![](tile_x04.jpg) 0x04<br>![](tile_x09.jpg) 0x09<br>![](tile_x0B.jpg) 0x0B<br>![](tile_x0C.jpg) 0x0C|![](tile_x06.jpg) 0x06<br>![](tile_x09.jpg) 0x09<br>![](tile_x0C.jpg) 0x0C<br>![](tile_x0D.jpg) 0x0D|![](tile_x08.jpg) 0x08<br>![](tile_x09.jpg) 0x09<br>![](tile_x0A.jpg) 0x0A<br>![](tile_x0D.jpg) 0x0D<br>
![](tile_x0A.jpg) 0x0A|![](tile_x01.jpg) 0x01<br>![](tile_x08.jpg) 0x08<br>![](tile_x0D.jpg) 0x0D|![](tile_x04.jpg) 0x04<br>![](tile_x09.jpg) 0x09<br>![](tile_x0B.jpg) 0x0B<br>![](tile_x0C.jpg) 0x0C|![](tile_x06.jpg) 0x06<br>![](tile_x09.jpg) 0x09<br>![](tile_x0C.jpg) 0x0C<br>![](tile_x0D.jpg) 0x0D|![](tile_x01.jpg) 0x01<br>![](tile_x02.jpg) 0x02<br>![](tile_x0B.jpg) 0x0B<br>
![](tile_x0B.jpg) 0x0B|![](tile_x03.jpg) 0x03<br>![](tile_x04.jpg) 0x04<br>![](tile_x0C.jpg) 0x0C|![](tile_x02.jpg) 0x02<br>![](tile_x03.jpg) 0x03<br>![](tile_x0A.jpg) 0x0A|![](tile_x06.jpg) 0x06<br>![](tile_x09.jpg) 0x09<br>![](tile_x0C.jpg) 0x0C<br>![](tile_x0D.jpg) 0x0D|![](tile_x08.jpg) 0x08<br>![](tile_x09.jpg) 0x09<br>![](tile_x0A.jpg) 0x0A<br>![](tile_x0D.jpg) 0x0D<br>
![](tile_x0C.jpg) 0x0C|![](tile_x02.jpg) 0x02<br>![](tile_x09.jpg) 0x09<br>![](tile_x0A.jpg) 0x0A<br>![](tile_x0B.jpg) 0x0B|![](tile_x05.jpg) 0x05<br>![](tile_x06.jpg) 0x06<br>![](tile_x0D.jpg) 0x0D|![](tile_x04.jpg) 0x04<br>![](tile_x05.jpg) 0x05<br>![](tile_x0B.jpg) 0x0B|![](tile_x08.jpg) 0x08<br>![](tile_x09.jpg) 0x09<br>![](tile_x0A.jpg) 0x0A<br>![](tile_x0D.jpg) 0x0D<br>
![](tile_x0D.jpg) 0x0D|![](tile_x02.jpg) 0x02<br>![](tile_x09.jpg) 0x09<br>![](tile_x0A.jpg) 0x0A<br>![](tile_x0B.jpg) 0x0B|![](tile_x04.jpg) 0x04<br>![](tile_x09.jpg) 0x09<br>![](tile_x0B.jpg) 0x0B<br>![](tile_x0C.jpg) 0x0C|![](tile_x07.jpg) 0x07<br>![](tile_x08.jpg) 0x08<br>![](tile_x0A.jpg) 0x0A|![](tile_x06.jpg) 0x06<br>![](tile_x07.jpg) 0x07<br>![](tile_x0C.jpg) 0x0C<br>


## Row

Example of a row with 10 tiles:

![](tile_x00.jpg)![](tile_x07.jpg)![](tile_x06.jpg)![](tile_x0D.jpg)![](tile_x04.jpg)![](tile_x00.jpg)![](tile_x08.jpg)![](tile_x0B.jpg)![](tile_x02.jpg)![](tile_x03.jpg)

||||||||||||
:-|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:
Offset|0|1|2|3|4|5|6|7|8|9
Tile|0x00|0x07|0x06|0x0D|0x04|0x00|0x08|0x0B|0x02|0x03
Image|![](tile_x00.jpg)|![](tile_x07.jpg)|![](tile_x06.jpg)|![](tile_x0D.jpg)|![](tile_x04.jpg)|![](tile_x00.jpg)|![](tile_x08.jpg)|![](tile_x0B.jpg)|![](tile_x02.jpg)|![](tile_x03.jpg)


✔️❌
