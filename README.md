# ait-info
移動販売とかシャトルバスとか


## シャトルバス
[愛工大ホームページ](https://www.ait.ac.jp/access/yakusa/)のpdfを参照して手動で頑張って変換した。  

### 該当日のダイヤ
`https://gh.hyouhyan.com/ait-info/bus/bus_ABC-R5.json`  
bus_ABC-R5.jsonには該当日のダイヤが記載されている。  
該当日がAダイヤの場合は"A"、Bダイヤの場合は"B"、Cダイヤの場合は"C"、運休の場合はnull。  

### 各ダイヤの運行スケジュール
`https://gh.hyouhyan.com/ait-info/bus/bus_diagram-R5.json`  
bus_diagram-R5.jsonには各ダイヤの運行スケジュールが記載されている。  
八草駅発のダイヤは"yakusa"、愛工大発のダイヤは"ait。  


## 移動販売
学内連絡で配布されるxlsxファイルをExcelでcsvに変換。  
pdfの場合はWebサービス経由でcsvに変換。  
`https://gh.hyouhyan.com/ait-info/idou/{yyyy}{mm}.csv`  