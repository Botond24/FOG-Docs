Arcanus
Hexcasting > Teleportaion


Player (entity)
Ipetus pos (vector)
\[0,1,0\]
+3
mult > \[0,3,0\]
Impetus dir (vector)
mult >

| Command              | Stack                                         |
| -------------------- | --------------------------------------------- |
| Player               | Player                                        |
| Impetus pos          | \[161,62,251\], Player                        |
| Vec Literal          | \[0,1,0\], \[161,62,251\], Player             |
| Num Literal          | +3, \[0,1,0\], \[161,62,251\], Player         |
| Mult/Div             | \[0,3,0\], \[161,62,251\], Player             |
| Impetus dir          | \[-1,0,0\], \[0,3,0\], \[161,62,251\], Player |
| Mult/Div             | \[0,0,0], \[161,62,251\], Player              |
| Add                  | \[161,62,251\], Player                        |
| Item/Not item        | Item, Player                                  |
| Read Item            | pos, Player                                   |
| Player               | Player, pos, Player                           |
| Compass (Entity pos) | \[161,62,251\], pos, Player                   |
| Add                  | \[161,62,251\] + pos, Player                  |
| Teleport             |                                               |

