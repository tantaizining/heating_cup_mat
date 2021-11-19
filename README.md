# heating_cup_mat
小巧可爱的加热杯垫，温牛奶神器


#以下为图片，如加载不出来，请访问https://gitee.com/tantaizining/heating_cup_mat


![image1](https://gitee.com/tantaizining/heating_cup_mat/raw/master/images/1.jpg)


若直接全功率加热，需在保险位置短接，或焊接自恢复保险丝，推荐6V4A或以上

将丝印对应的0R电阻短接，将mos的D和S短接（上脚和右下脚）

焊接好type—c接口

使用5V充电器，充电器输出电流需在2A及以上

注意安全，谨防烫伤、起火。电热DIY有一定危险性，谨慎模仿，后果自负哦。


如需自由控温，请按照底面丝印信息补全电路。
sop8为lm358，B3950热敏电阻为10k，拨盘电位器为3脚50k，mos为AO3400，自恢复保险不可采用2A，建议9V4A或以上（未测试）或直接短接（注意安全）。
6V2A的自恢复保险在50℃时的动作电流约为1.2A，为了使其能稳定工作，需选用工作电流更高的保险。
