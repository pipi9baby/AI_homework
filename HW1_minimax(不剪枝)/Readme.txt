1.輸入檔案需為txt檔
2.輸入檔案格式
  a.第一行：分支數量
  b.第二行：階層數量
  c.第三行：輸入各個葉子的值，以逗號分割，最後加上換行符號
3.程式操作方式
  輸入input檔的檔案位置及檔名(含附檔名)後，按下Enter
4.程式功能
  程式會將，輸入的葉子值做minimap，ROOT層存分支下的最大值，下一層找分支下的最小值，找大找小隨階層互換
5.輸出模式
  a.第一部分輸出：分支數量、階層數量、葉子數量、除葉子以外要新增的節點數
  b.第二部分輸出：minimap後，更新過的每個node值按DFS搜尋路徑輸出
  c.第三部分輸出：minimap後，最終ROOT的值