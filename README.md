# Benchmark
The dataset repository for the paper - A Dataset for Dynamic Discovery of Semantic Changes in Version Controlled Software Histories.


## An overview of the dataset


| <sub>Functionality</sub> | <sub>History Start</sub> | <sub>History End</sub> | <sub>#Commits</sub> | <sub>#Files Edited</sub> | <sub>#LOC +</sub> | <sub>#LOC -</sub> | <sub>#Test cases</sub> | <sub>Slice Size</sub> | <sub>Reduction %</sub> |
|:-------------:|--------------:|------------:|---------:|--------------:|-------:|-------:|------------:|-----------:|---:|
|LANG-825|bae9f7c3|15a51f1d|475|265|27630|11935|2|118|75.16|
|LANG-839|bae9f7c3|15a51f1d|475|265|27630|11935|2|200|57.89|
|LANG-841|bae9f7c3|15a51f1d|475|265|27630|11935|2|200|57.89|
|LANG-906|bae9f7c3|15a51f1d|475|265|27630|11935|5|1|99.79|
|LANG-834|c4ecd75|66a3717|179|121|6889|1807|12|12|93.3|
|LANG-944|c4ecd75|66a3717|179|121|6889|1807|1|24|86.59|
|LANG-993|24767d6|76cc69c|262|146|6741|2076|10|6|97.71|
|LANG-999|24767d6|76cc69c|262|146|6741|2076|5|15|94.27|
|LANG-1006|24767d6|76cc69c|262|146|6741|2076|2|14|94.66|
|LANG-1033|24767d6|76cc69c|262|146|6741|2076|1|22|91.6|
|LANG-1088|24767d6|76cc69c|262|146|6741|2076|2|1|99.62|
|LANG-1050|0d5d666|36f98d8|515|309|18885|6395|4|8|98.45|
|LANG-1074|0d5d666|36f98d8|515|309|18885|6395|9|6|98.83|
|LANG-1119|0d5d666|36f98d8|515|309|18885|6395|1|1|99.81|
|CALCITE-627|f10ea367|d60f2aa3|51|135|8274|1446|2|19|62.75|
|CALCITE-655|f10ea367|d60f2aa3|51|135|8274|1446|1|19|62.75|
|CALCITE-674|d60f2aa3|495f1859|59|196|14861|9173|1|11|81.36|
|CALCITE-718|495f1859|0c0c203d|92|304|21348|7686|1|14|84.78|
|CALCITE-758|495f1859|0c0c203d|92|304|21348|7686|1|1|98.91|
|CALCITE-811|495f1859|0c0c203d|92|304|21348|7686|1|1|98.91|
|CALCITE-803|495f1859|0c0c203d|92|304|21348|7686|1|1|98.91|
|CALCITE-925|0c0c203d|ba6e43c6|120|468|68314|6096|3|1|99.17|
|CALCITE-767|ba6e43c6|c4d346b0|103|465|31647|13594|1|8|92.23|
|CALCITE-996|ba6e43c6|c4d346b0|103|465|31647|13594|1|1|99.03|
|CALCITE-1003|ba6e43c6|c4d346b0|103|465|31647|13594|25|14|86.41|
|CALCITE-1028|ba6e43c6|c4d346b0|103|465|31647|13594|1|6|94.17|
|CALCITE-1168|8eebfc6d|aeb6bf14|122|399|30975|4800|3|2|98.36|
|CALCITE-1200|8eebfc6d|aeb6bf14|122|399|30975|4800|3|2|98.36|
|CALCITE-991|aeb6bf14|08c56b15|78|295|14908|3637|5|1|98.72|
|CALCITE-1288|aeb6bf14|08c56b15|78|295|14908|3637|1|6|92.31|
|CALCITE-1309|aeb6bf14|08c56b15|78|295|14908|3637|8|7|91.03|
|CALCITE-1337|aeb6bf14|08c56b15|78|295|14908|3637|2|5|93.59|
|MNG-4904|b175144|308d4d4|51|78|1816|713|1|7|86.27|
|MNG-4909|b175144|308d4d4|51|78|1816|713|2|7|86.27|
|MNG-4910|b175144|308d4d4|51|78|1816|713|1|7|86.27|
|MNG-4953|38ced22|23226|47|96|2448|329|1|6|87.23|
|MNG-5159|089a9f8|6d37598|120|318|3003|1098|4|2|98.33|
|MNG-5530|b7e3ce2|ea8b2b0|97|160|4431|4144|1|1|98.97|
|MNG-5549|b7e3ce2|ea8b2b0|97|160|4431|4144|1|13|86.6|
|MNG-5754|d13c288|cab6659|97|235|9500|3930|4|8|91.75|
|MNG-5755|d13c288|cab6659|97|235|9500|3930|5|7|92.78|
|MNG-5767|d13c288|cab6659|97|235|9500|3930|3|21|78.35|
|MNG-5805|0ddab5f|bb52d85|98|341|3751|3030|2|11|88.78|
|COMPRESS-295|083e7a4|1dcab3f|169|181|6638|1580|2|1|99.41|
|COMPRESS-296|083e7a4|1dcab3f|169|181|6638|1580|3|37|78.11|
|COMPRESS-313|083e7a4|1dcab3f|169|181|6638|1580|3|40|76.33|
|COMPRESS-327|99bc508|b29395d|148|144|4644|2006|18|26|82.43|
|COMPRESS-368|99bc508|b29395d|148|144|4644|2006|6|12|91.89|
|COMPRESS-369|99bc508|b29395d|148|144|4644|2006|2|10|93.24|
|COMPRESS-373|99bc508|b29395d|148|144|4644|2006|1|14|90.54|
|COMPRESS-374|99bc508|b29395d|148|144|4644|2006|8|15|89.86|
|COMPRESS-375|99bc508|b29395d|148|144|4644|2006|2|1|99.32|
|FLUME-1710|31d45f1b|f7560038|133|258|15949|2783|1|1|99.25|
|FLUME-2052|cda3bd10|31d45f1b|101|181|14742|3097|5|3|97.03|
|FLUME-2056|cda3bd10|31d45f1b|101|181|14742|3097|1|5|95.05|
|FLUME-2130|cda3bd10|31d45f1b|101|181|14742|3097|1|3|97.03|
|FLUME-2206|cda3bd10|31d45f1b|101|181|14742|3097|1|4|96.04|
|FLUME-2498|f7560038|5e400ea8|100|428|17341|8187|17|65|35|
|FLUME-2628|f7560038|5e400ea8|100|428|17341|8187|7|1|99|
|FLUME-2955|f7560038|5e400ea8|100|428|17341|8187|1|65|35|
|FLUME-2982|f7560038|5e400ea8|100|428|17341|8187|2|35|65|
|PDFBOX-3307|a281f71|9e102f2|37|42|1138|268|2|1|97.3|
|PDFBOX-3069|3b5ae83|5.85E+93|272|255|9737|5398|2|1|99.63|
|PDFBOX-3418|3b5ae83|5.85E+93|272|255|9737|5398|2|3|98.9|
|PDFBOX-3461|3b5ae83|5.85E+93|272|255|9737|5398|24|3|98.9|
|PDFBOX-3262|7c1a2c8|69a8e03|162|135|3295|814|1|2|98.77|
|CONFIGURATION-466|5270237|f81ff1a|252|694|79920|80096|3|13|94.84|
|CONFIGURATION-624|89428f1|9fb4ad8|50|34|1201|655|11|48|4|
|CONFIGURATION-626|89428f1|9fb4ad8|50|34|1201|655|4|1|98|
|NET-436|d8812a3|4c3860e|77|99|2357|774|5|7|90.9|
|NET-525|d483631|abd6711|269|233|6845|2393|14|40|85.13|
|NET-527|d483631|abd6711|269|233|6845|2393|1|40|85.13|
