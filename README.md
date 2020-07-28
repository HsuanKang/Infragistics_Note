# Infragistics

UltraLabel
屬性 -> Appearance -> foreColor(字體顏色)
                   -> backColor(背景顏色) -> transparent(透明)
                   -> visibel(顯示)
                   
UltraGrid
屬性 -> DisplayLayout -> Appearance -> TextHAlign(標題對齊位置)
                     -> GroupByButton -> Hidden(GroupBy隱藏)
                     
# N-Tier Architecture

DB         | PO         | CTL         | PXY         | UI
.xsd       |            |             |             |  
.cs         interface    VDB 轉換       執行CTL       add 事件
ModelVDB    SQL          PO 委派        裡的Method    add 屬性
ViewVDB     cmd          執行 PO 方法                 驗證功能
                        <ModelVDB>轉型<ViewVDB>
