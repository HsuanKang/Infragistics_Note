# Infragistics

<b>UltraLabel</b>
屬性 -> Appearance -> foreColor(字體顏色)
                   -> backColor(背景顏色) -> transparent(透明)
                   -> visibel(顯示)
                   
<b>UltraGrid</b>
屬性 -> DisplayLayout -> Appearance -> TextHAlign(標題對齊位置)
                     -> GroupByButton -> Hidden(GroupBy隱藏)
                     
<b>UltraGridColumn.CellActivation</b>  (To prevent the cell from going into edit mode)
                     
# N-Tier Architecture

1. <b>DB</b> -> .xsd / .cs / ModelVDB / ViewVDB
2. <b>PO</b> -> interface / SQL / cmd
3. <b>CTL</b> -> 實作 interface / 建構解構 / VDB 轉換 / PO 委派 / <ModelVDB>轉型<ViewVDB>
4. <b>PXY</b> -> 實作Ctl / 執行CTL裡的Method
5. <b>UI</b> -> add 事件 / add 屬性 -> 驗證功能

# c#

<a href="https://coolong124220.nidbox.com/diary/read/8045390">ArgumentException 參考</a><br/>
<a href="https://docs.microsoft.com/zh-tw/dotnet/api/system.environment.newline?view=netcore-3.1">Environment.NewLine 換行</a><br/>
<a href="https://www.itread01.com/content/1545667219.html">UltraGridColumn.CellActivation</a><br/>
<a href="https://dotblogs.com.tw/abbee/2012/08/22/74207">DataSet 序列化傳送</a><br/>
<a href="https://docs.microsoft.com/zh-tw/dotnet/api/system.string.format?view=netcore-3.1#System_String_Format_System_String_System_Object_System_Object_">String.Format()</a><br/>
<a href="https://docs.microsoft.com/zh-tw/dotnet/api/system.string.isnullorempty?view=netcore-3.1">IsNullOrEmpty() // 空字串 or Null -> True // string.Empty</a><br/>
str(變數).PadRight(Left)(int , "###") ->填補字串</br>
<a href="https://dotblogs.com.tw/stanley14/2017/03/27/string_split_merge">SQL Server 多筆資料列轉字串</a><br/>
<a href="https://dotblogs.com.tw/chichiBlog/2017/10/16/155514">(搭配)SqlDataReader</a><br/>

# Crystal Report

<a href="https://www.itread01.com/content/1546470727.html">Defining  Variable</a><br/>
<a href="https://help.sap.com/viewer/5e655af038844318b5686fe80d91af27/4.1.10/zh-TW/4786f5d86e041014910aba7db0e91070.html">加總、基本語法</a><br/>
<a href="http://markshutest.blogspot.com/2018/04/crystal-report-1.html">常用語法</a><br/>
