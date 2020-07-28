# Infragistics

<b>UltraLabel</b>
屬性 -> Appearance -> foreColor(字體顏色)
                   -> backColor(背景顏色) -> transparent(透明)
                   -> visibel(顯示)
                   
<b>UltraGrid</b>
屬性 -> DisplayLayout -> Appearance -> TextHAlign(標題對齊位置)
                     -> GroupByButton -> Hidden(GroupBy隱藏)
                     
# N-Tier Architecture

1. <b>DB</b> -> .xsd / .cs / ModelVDB / ViewVDB
2. <b>PO</b> -> interface / SQL / cmd
3. <b>CTL</b> -> VDB 轉換 / PO 委派 / <ModelVDB>轉型<ViewVDB>
4. <b>PXY</b> -> 執行CTL裡的Method
5. <b>UI</b> -> add 事件 / add 屬性 -> 驗證功能
