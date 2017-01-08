
#簡介

讓大家了解自己的手機門號在合約尚未到期時若想進行解約時所需要繳交的解約金是多少, 開發此一版本讓大家直接查詢

## 版本
先開發此網路版本, 日後再開發 APP

### 違約金計算方式

已中華電信 智慧大玩家 <a href="http://www.emome.net/channel?chid=829&pid=6">平板699方案</a>來看
其合約如此份 <a href="https://github.com/deternan/Phone-damages/blob/master/Contract/CHT/4G%E5%B9%B3%E6%9D%BF%E5%A4%A7%E7%8E%A9%E5%AE%B6%E6%96%B9%E6%A1%88%E5%90%8C%E6%84%8F%E6%9B%B8(24%E5%80%8B%E6%9C%88).pdf"> PDF </a> 檔 

* 終端設備及/或電信費用補貼款 (終端設備補貼) 	NT 6700
* 月租費優惠 (已享月租費優惠)					NT 36/month
* 其他補助 (優惠平板購買減價)					NT 1000

公式計算
(已享月租費優惠+終端設備補貼) * (合約剩餘日數 / 合約總長度日數)

某使用者門號起始的日期為 2015年8月10日; 合約24個月, 共730天
至今 (假設為 2016年12月28日) 共 506天, 離合約結束時間為 224天

[((36/30) * (730-240))+6700+1000] * (224/730) = NT 2543

故若在2016年12月28日這一天解約, 則需要賠償 NT 2543


### Reference
日期相隔天數計算機 : [link](http://daybetween.0123456789.tw)

### History

* January 07, 2017	Prepared different phone company contract
* January 05, 2017	alpha version released
* January 03, 2017	Start this repository

### 版權
若各家的門號申請文件屬於機密資訊不允許被公告, 煩請告知, 將立即撤下

### Comments
如果各位使用者覺得系統有問題, 請隨時與我聯絡, thanks
E-mail : phelpske.dev at gmail dot com

Last updated: January 09, 2017 00:47 AM



