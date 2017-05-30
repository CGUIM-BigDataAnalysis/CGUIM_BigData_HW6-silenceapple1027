HIV 感染病例分析
================

作業說明 （繳交時請直接刪除這個章節）
-------------------------------------

作業目的：期末專題暖身

依下列指示，完成期末分析專題作業規劃：

-   分析議題動機 (`10pt`)
-   資料處理與清洗 (`10pt`) 說明 (`10pt`)
-   對資料們進行探索式資料分析，圖文並茂佳!(`20pt`)

組員姓名
--------

黃詩茜 許定楠

分析議題背景
------------

愛滋病是由愛滋病毒所引起的疾病。愛滋病毒會破壞人體原本的免疫系統，使病患的身體抵抗力降低，當免疫系統遭到破壞後，原本不會造成生病的病菌，變得有機會感染人類，嚴重時會導致病患死亡。 愛滋病毒為人類免疫缺乏病毒（Human Immunodeficiency Virus,HIV）的簡稱，是一種破壞免疫系統的病毒。

分析動機
--------

分析動機分析動機

使用資料
--------

資料集描述 : 2003年起各地區、各年齡層、性別之病例數統計表 (疾病名稱：HIV感染，日期種類：診斷日，病例種類：確定病例，感染來源：本國籍、非本國籍)。 主要欄位說明 : 「確定病名」、「診斷年份」、「診斷月份」、「縣市」、「性別」、「國籍」、「年齡層」、「確定病例數」。

載入使用資料們

``` r
library(readxl)
```

    ## Warning: package 'readxl' was built under R version 3.3.3

``` r
Age_County_Gender_044 <- read_excel("D:/data/Desktop/Age_County_Gender_044.xlsx")
View(Age_County_Gender_044)
```

資料處理與清洗
--------------

說明處理資料的步驟

處理資料

``` r
#這是R Code Chunk
```

探索式資料分析
--------------

圖文並茂圖文並茂

``` r
library(dplyr)
```

    ## Warning: package 'dplyr' was built under R version 3.3.3

    ## 
    ## Attaching package: 'dplyr'

    ## The following objects are masked from 'package:stats':
    ## 
    ##     filter, lag

    ## The following objects are masked from 'package:base':
    ## 
    ##     intersect, setdiff, setequal, union

期末專題分析規劃
----------------

期末專題要做HIV感染交叉分析，對於不同年份、縣市、性別、年齡層等因素進行分析與統計， 將以圖表方式呈現、文字輔助說明。

一、折線圖表示各年份的確定病例數，分析感染病例是否逐漸上升/下降。 二、探討各縣市確定HIV感染之統計。 三、探討男性、女性確定HIV感染之人數差異。 四、探討不同年齡層的確定病例數之排名。 五、以國籍區分，分析台灣的HIV感染病例。
