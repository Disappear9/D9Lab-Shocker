链接：

YY 9706.210-2021  
https://www.zhuangpeitu.com/article/92679863.html

IEC 60601-2-10:2012+AMD1:2016 CSV Consolidated versionMedical electrical equipment  
https://www.doc88.com/p-7018433722801.html

https://www.bilibili.com/video/BV1Zs411m77f/

https://www.bilibili.com/video/BV1Lx411P7KH/

Dungeon Labs Coyote teardown  
https://www.reddit.com/r/estim/comments/uadthp/dg_lab_coyote_review_by_an_electronics_engineer/

https://www.reddit.com/r/estim/comments/vnjr6r/something_you_might_want_to_know_about_estim_and/


输出规格：  
1.外接 500Ω 负载时，输出电流不超过：
|  频率  |  电流限制  |
|  ----  |  ----  |
|  <400Hz |  50mA  |
|  0.4k-1.5kHz |  80mA  |
|  >1.5kHz |  100mA  |

2.输出端开路时，输出电压峰值不超过500V.

3.输出单个脉冲不得长于0.1s，能量不超过300mJ

输出方式：

频率可变( 0.5 - 2 KHz ) / ( 1 - 2 KHz ) ，占空比可变 ( 200 - 400 us?) ，进入初级线圈的电压可变

电路架构：

电池 ->升降压到5V

5V -> 3.3V(ESP)

5V -> (???) -> 高压输出
