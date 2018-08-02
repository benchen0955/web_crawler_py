# web_crawler_py
#####################
1.pycharm 說明
C:\Users\BC\AppData\Local\Programs\Python\Python36-32
2.正則表達式符號與方法
(.*?)
for eachh in ddd

s = '''sdfxxhello
xxfsdfxxworldxxasdf'''  #換行

d = re.findall('xx(.*?)xx',s,re.S) #re.S 可包含換行符
print d

findall与search的区别
#search 找第一次匹配的
findall 找所有匹配的

sub的使用举例功能是替換

# from re import findall,search,S不要使用這種方法
3.正則表達式的應用舉例

4.應用
極客網頁抓圖

股票價格網頁
http://www.twse.com.tw/exchangeReport/STOCK_DAY?response=html&date=20180722&stockNo=2330






##################################








1 Requests 介紹和安裝
C:\Users\BC\AppData\Local\Programs\Python\Python36-32
requests介紹
用pip 安裝 requests ,亦可解除安裝
下載三方庫有問題可查 https://www.lfd.uci.edu/~gohlke/pythonlibs/
ctrl+f 找requests*.whl 改為.ZIP 解壓 複製到lib內

2.第一個網頁爬蟲
擷取網頁內容

3.get post 異步加載

4.實戰——極客學院課程爬蟲










####################################################






1.神器 XPath 的介紹與配置
python -m pip install lxml

2.神器 XPath 的使用
//*[@id="useful"]/li[1]

3.神器 XPath 的特殊用法
starts-with(@id,"test")
string(.)

4.Python 並行化介紹與演示
https://www.zhihu.com/question/31110175
解決 reload(sys)











###################################
