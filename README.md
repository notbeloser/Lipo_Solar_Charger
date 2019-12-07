# Lipo Solar Charger
###[開發筆記](http://blog.hardnote.net/2019/12/lipo_solar_charger/ "開發筆記")
## Lipo Solar Charger 技術規格
採用CN3791作為MPPT太陽能充電ic，最大功率電壓設定在6V(可透過置換電阻改變最大功率電壓)
採用MT3608做3.7V to 5V/12V的boost電路，有一個JMP可以選擇輸出是5V/12V
輸入輸出全部採用XH2.54作為標準接頭
- 輸入 ：6V 2.5A
- 輸出 ：3.7V & 5V 2A / 3.7V & 12V 0.6A (3.7V電池直接輸出)
- 充電滿電雙指示燈

## 電路圖
![](http://blog.hardnote.net/wp-content/uploads/2019/12/%E6%93%B7%E5%8F%96%E9%81%B8%E5%8F%96%E5%8D%80%E5%9F%9F_012-1024x793.png)

## 實際電路組裝照片
![](http://blog.hardnote.net/wp-content/uploads/2019/12/79531813_614350809105481_2424398056637071360_n-768x1024.jpg)

![](http://blog.hardnote.net/wp-content/uploads/2019/12/78480530_552882678594220_5721896804874715136_n-768x1024.jpg)

## 實際應用充電曲線
10W 6V太陽能板 + 10000mAh 3.7V LiPo
![](https://scontent.ftpe9-1.fna.fbcdn.net/v/t1.0-9/78063273_3443633719010095_7785702395320729600_o.jpg?_nc_cat=111&_nc_ohc=7yeX2J-grjwAQni4K8S6Y51LW-ix_bpyKIPkzQD5_6oG47b4cF6veOCRg&_nc_ht=scontent.ftpe9-1.fna&oh=9084535b6db85b388bbec4afbc3b7e2c&oe=5E769A40)

## 聯絡方式
### 如有電路問題，或是相關客制需求，歡迎發Issue 或是透過email聯繫我 
- notbeloser@hardnote.net
