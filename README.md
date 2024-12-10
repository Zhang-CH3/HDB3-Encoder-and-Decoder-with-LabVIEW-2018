# HDB3-Encoder-and-Decoder-with-LabVIEW-2018
用LabVIEW 2018实现HDB3编码/译码。

内含：

 - HDB3编码器
   - 主程序；
   - 连0判断器；
   - 将B00V码转换为X00V码(X = 0 or 1)；
   - 将X00V码转换为最终的HDB3码。
 
 - HDB3译码器
   - 主程序；
   - "1001"结构判断器；
   - "10001"结构判断器。
   
  使用时，可根据需要调整代码。若要改为HDBn编码，则几个子VI也需同时修改。
