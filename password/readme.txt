basic.txt       http basic 认证
birthday.txt    生日 example. 20021015
china-id-6.txt  中国公民身份证后 6 位
iot.txt         iot all
jwt.txt         jwt


top100.txt      概率降序 top100  - admin & user & cn & iot & 通用 (命中率最高, 无注释)
top500.txt      概率降序 top500  - 累加扩充 top100 (100 < add <= 500)
top2000.txt     概率降序 top2000 - 累加扩充 top500 (500 < add <= 2000)
top10000.txt    complex - top 长尾 (2000 < add)

small.txt       admin & user & cn & us & iot & complex - (2000 < add <= 1w)
large.txt       admin & user & cn & us & iot & complex - ( add < 1w)

说明: top100/500/2000 为无注释纯口令、按命中概率降序排列、严格累加
      (top100 ⊂ top500 ⊂ top2000), 可直接喂 hydra/ffuf 等工具。