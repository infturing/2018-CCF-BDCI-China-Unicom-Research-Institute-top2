# 2018-CCF-BDCI-China-Unicom-Research-Institute-top2
===============================================================================================================
## 主办方：中国计算机学会 & DataFountain & 中国联通研究院
## 赛道：2018-CCF大数据与计算智能大赛-面向电信行业存量用户的智能套餐个性化匹配模型

赛道链接：https://www.datafountain.cn/competitions/311/details/data-evaluation       
**赛程时间**：*2018.08.28-2018.11.11*  
**参与人**:[郭大](https://github.com/guoday)、[林有夕](https://github.com/infturing) 、[小兔子乖乖](https://github.com/PandasCute)      
为避免数据丢失，提供数据集下载地址：链接：https://pan.baidu.com/s/1ow6PLYVvBKfvXwbT88jw5Q 提取码：5hwq     

**数据集解释**：官方下载数据集命名可能不一样
百度云分享数据集我将初赛训练集和测试集分别命名为：train_1.csv,test_1.csv   
百度云分享数据集我将复赛训练集和测试集分别命名为：train_2.csv,test_2.csv 

**数据说明**  


| 字段     | 中文名| 数据类型|  说明 |
|:-------:|:-------:|:-------:|:-------:|
|USERID|	用户ID|	VARCHAR2(50)|	用户编码，标识用户的唯一字段|
|current_type|	套餐	|VARCHAR2(500)	|/|
|service_type	|套餐类型	|VARCHAR2(10)	|0：23G融合，1：2I2C，2：2G，3：3G，4：4G|
|is_mix_service	|是否固移融合套餐|	VARCHAR2(10)|	1.是 0.否|
|online_time	|在网时长|	VARCHAR2(50)	|/|
|1_total_fee|	当月总出账金额_月	|NUMBER|	单位：元|
|2_total_fee	|当月前1月总出账金额_月|	NUMBER	|单位：元|
|3_total_fee|	当月前2月总出账金额_月|	NUMBER	单位：元|
|4_total_fee	|当月前3月总出账金额_月	|NUMBER|	单位：元|
|month_traffic	|当月累计-流量	|NUMBER|	单位：MB|
|many_over_bill|	连续超套	|VARCHAR2(500)|	1-是，0-否|
|contract_type|	合约类型|	VARCHAR2(500)	|ZBG_DIM.DIM_CBSS_ACTIVITY_TYPE|
|contract_time|	合约时长|	VARCHAR2(500)|	/|
|is_promise_low_consume	|是否承诺低消用户|	VARCHAR2(500)	|1.是 0.否|
|net_service	|网络口径用户|	VARCHAR2(500)	|20AAAAAA-2G|
|pay_times	|交费次数	|NUMBER	|单位：次|
|pay_num	|交费金额	|NUMBER	|单位：元|
|last_month_traffic	|上月结转流量|	NUMBER|	单位：MB|
|local_trafffic_month|	月累计-本地数据流量	|NUMBER	|单位：MB|
|local_caller_time|	本地语音主叫通话时长|	NUMBER|	单位：分钟|
|service1_caller_time	|套外主叫通话时长|	NUMBER	|单位：分钟|
|service2_caller_time	|Service2_caller_time|	NUMBER	|单位：分钟|
|gender|	性别	|varchar2(100)	|01.男 02女|
|age|	年龄|	varchar2(100)|	/|
|complaint_level	|投诉重要性|	VARCHAR2(1000)	|1：普通，2：重要，3：重大|
|former_complaint_num|交费金历史投诉总量|	NUMBER	|单位：次|
|former_complaint_fee|	历史执行补救费用交费金额	|NUMBER	|单位：分|
