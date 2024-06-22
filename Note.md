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

电击器电路原理分析  
https://hvprvbo.blogspot.com/2019/10/sm.html

郊狼3.0拆解  
https://cf.blog.halfsweet.cn/posts/why_i_am_disappointed_with_the_third_generation_of_wolf/#%E4%B8%BB%E6%9C%BA%E6%8B%86%E8%A7%A3  
https://github.com/Disappear9/D9Lab-Shocker/blob/main/images/2024-03-16-01-32-31.png  
https://github.com/Disappear9/D9Lab-Shocker/blob/main/images/2024-03-16-01-33-14.png  

输出规格：  
1.外接 500Ω 负载时，输出电流不超过：
|  频率  |  电流限制  |
|  ----  |  ----  |
|  <400Hz |  50mA  |
|  0.4k-1.5kHz |  80mA  |
|  >1.5kHz |  100mA  |

2.输出端开路时，输出电压峰值不超过500V.

3.输出单个脉冲不得长于0.1s，能量不超过300mJ


===========================================================================
https://github.com/VRChatNext/Shocking-VRChat/blob/main/README.md  
- float
  - /avatar/parameters/pcs/contact/enterPass
    - 最常用，位于pcs触发入口处，可自动切换跟随被触发的位置
  - /avatar/parameters/pcs/contact/proximityA
  - /avatar/parameters/pcs/contact/proximityB
  - /avatar/parameters/pcs/contact/slide
    - 不推荐使用，pcs开启后前后移动会触发很多次
  - /avatar/parameters/pcs/smash-intensity
  - /avatar/parameters/pcs/sps/pussy
    - 如果需要仅通过指定位置触发，可尝试 pcs/sps 下的参数，不会跟随auto mode位置变化
  - /avatar/parameters/pcs/sps/ass
  - /avatar/parameters/pcs/sps/boobs
  - /avatar/parameters/pcs/sps/mouth
  - /avatar/parameters/pcs/sps/penis*
  - /avatar/parameters/lms-penis-proximityA*
    - 通过 LMS 触发可以使用的参数
- bool
  - /avatar/parameters/pcs/smash-intense
  - /avatar/parameters/pcs/contact/in
  - /avatar/parameters/pcs/contact/out
  - /avatar/parameters/pcs/contact/hit
  - /avatar/parameters/lms-stroke-in
  - /avatar/parameters/lms-stroke-out*
  - /avatar/parameters/lms-stroke-smash
