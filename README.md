# W25N01GVZEIG board change from W25Q80VSSIG_b

接口定义  
1-CS#->SPI_CS#  
2-DO(IO1)->SPI_MISO  
3-WP#(IO2)  
4-GND  
5-DI(IO0)->SPI_MOSI  
6-CLK->SPI_CLK  
7-HOLD#(IO3)  
8-VCC  
9-EP

NAND flash
tBE 2ms
memory 1Gbit
SPI
数据保留时间TDR 10year
Tpp 250us
package WSON-8-EP(6.1x8)

## W25Q80VSSIG_b

模块接口定义从从接口标准顺序出发
比如stm32f103的SPI1
VSS  
GND  
PA4 SPI1_NSS    CS#  
PA5 SPI1_SCK    CLK  
PA7 SPI1_MOSI   DI(IO0)  
PA6 SPI1_MISO   DO(IO1)  
                WP#(IO2)  
                HOLD#(IO4)  

## W25Q80VSSIG_a  

[W25Q80VSSIG](https://www.jlc-smt.com/lcsc/detail?componentCode=C14086)  

class   NOR FLASH  
package     SOIC-8-208mil  
memory  8Mbit  
interface   dual and quad spi  
檫除时间tBE     150mS@64KB  
fc  104Mhz  
写入时间Tpp     3ms  

接口定义  
1-CS#->SPI_CS#  
2-DO(IO1)->SPI_MISO  
3-WP#(IO2)   
4-GND  
5-DI(IO0)->SPI_MOSI  
6-CLK->SPI_CLK  
7-HOLD#(IO3)   
8-VCC  

[模块参考](https://item.taobao.com/item.htm?priceTId=undefined&utparam=%7B%22aplus_abtest%22%3A%226a56d4f83e5146ee0d4dd8b8974ab268%22%7D&id=660467426297&ns=1&abbucket=4&xxc=taobaoSearch&detail_redpacket_pop=true&query=flash+%E6%A8%A1%E5%9D%97&skuId=5631050961877&spm=a21n57.1.hoverItem.5&ltk2=1746922057202bi5ueergtsso7z386oxzxf)   

模块接口定义  
VCC CS DO GND CLK DI  

## GD25Q32CSIG_a board = W25Q80VSSIG_a  

## GD25Q32CSIG_b board = W25Q80VSSIG_b  