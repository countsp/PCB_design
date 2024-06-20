## 1、信号层（Signal Layers）

Altium Designer最多可提供32个信号层，包括顶层（Top Layer）、底层（Bottom Layer）和中间层（Mid-Layer）。

各层之间可通过通孔（Via）、盲孔（Blind Via）和埋孔（Buried Via）实现互相连接。

![Screenshot from 2024-06-19 21-01-33](https://github.com/countsp/PCB_design/assets/102967883/b923af62-c484-43fe-afe6-ead770e37de7)

![image](https://github.com/countsp/PCB_design/assets/102967883/5e54680f-bf73-4ae2-a4b0-dbe94b2b45af)

（1）顶层信号层（Top Layer）

也称元件层，主要用来放置元器件，对于双层板和多层板可以用来布置导线或覆铜。在LCEDA中默认红色表示。

![Screenshot from 2024-06-19 21-18-45](https://github.com/countsp/PCB_design/assets/102967883/a6b40fa5-88e2-4259-b226-3fa28cbd82a5)

（2）底层信号层（Bottom Layer）

也称焊接层，主要用于布线及焊接，对于双层板和多层板可以用来放置元器件。在LCEDA中默认蓝色表示。

![Screenshot from 2024-06-19 21-19-27](https://github.com/countsp/PCB_design/assets/102967883/191a7df0-7905-4b43-98a9-e82264b9fa11)

（3）中间信号层（Mid-Layers）（可忽略）

最多可有30层，在多层板中用于布置信号线，这里不包括电源线和地线。中间信号层的目的是缩小PCB面积，其实仅顶层与底层信号层可以完成所有信号走线。

## 2、内部电源层（Internal Planes）

通常简称为内电层，仅在多层板中出现，PCB板层数一般是指信号层和内电层相加的总和数。一般有两层：电源层和地层。

与信号层相同，内电层与内电层之间、内电层与信号层之间可通过通孔、盲孔和埋孔实现互相连接。

![image](https://github.com/countsp/PCB_design/assets/102967883/7e70e261-b360-4d02-a00f-8e3b89cd7ff5)



## 3、丝印层（Silkscreen Layers）

可以理解为PCB上的图案，一块PCB板最多可以有2个丝印层，分别是顶层丝印层（Top Overlay）和底层丝印层（Bottom Overlay），主要用于放置印制信息，如元器件的轮廓和标注，各种注释字符等，方便PCB的元器件焊接和电路检查。

（1）顶层丝印层（Top Overlay）

用于标注元器件的投影轮廓、元器件的标号、标称值或型号以及各种注释字符。

![Screenshot from 2024-06-19 21-22-11](https://github.com/countsp/PCB_design/assets/102967883/4de6a9c6-0e22-491d-8c2c-c598f8b8f3de)

（2）底层丝印层（Bottom Overlay）

与顶层丝印层相同，只不过印刷在背面。

![image](https://github.com/countsp/PCB_design/assets/102967883/65e09a80-8d56-4e1e-b422-2399ae4b2efc)


## 4、机械层（Mechanical Layers）

Mechanical Layer：一般用来绘制PCB的边框，作为其机械外形，故也称为外形层。

![Screenshot from 2024-06-19 21-23-12](https://github.com/countsp/PCB_design/assets/102967883/7c0ba8df-1a8a-43d4-a5d6-de02575a6201)
