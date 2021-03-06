---
TOCTitle: 'MS11-JUL'
Title: 2011 年 7 月份 Microsoft 資訊安全公告摘要
ms:assetid: 'ms11-jul'
ms:contentKeyID: 61237718
ms:date: '04/18/2014'
ms:mtpsurl: 'https://technet.microsoft.com/zh-TW/library/ms11-jul(v=Security.10)'
---

2011 年 7 月份 Microsoft 資訊安全公告摘要
=========================================

發行: 2011年7月13日

**版本:** 1.0

此公告摘要列出 2011 年 7 月份發行之資訊安全公告。

發行 2011 年 7 月份資訊安全公告之後，此公告摘要將取代原先於 2011 年 7 月 7 日發行的公告預先通知。如需更多有關公告預先通知服務的資訊，請參閱 [Microsoft 資訊安全公告預先通知](http://go.microsoft.com/fwlink/?linkid=217213)。

如需有關如何在 Microsoft 資訊安全公告發佈時收到自動通知之詳細資訊，請造訪 [Microsoft 技術安全性通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 將利用網路廣播於 2011 年 7 月 13 日，太平洋時間早上十一點 (美國與加拿大) 解答客戶對於這些公告的問題。 [立即註冊參加 7 月份資訊安全公告網路廣播](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032487855&eventcategory=4)。 在這個日期後，此網路廣播將可隨選取得。 如需更多資訊，請參閱 [Microsoft 資訊安全公告摘要和網路廣播](http://go.microsoft.com/fwlink/?linkid=217214)。

Microsoft 也會提供資訊協助客戶排定每月資訊安全更新以及任何非資訊安全更新的優先順序，其中這些非資訊安全更新的發行日期與每月資訊安全更新的發行日期相同。 請參閱＜其他資訊＞一節。

### 公告資訊

提要
----

<span></span>
下表依嚴重性摘要說明本月份資訊安全公告。

如需受影響的軟體之詳細資料，請參閱下節＜受影響的軟體及下載位置＞。

 
<p> </p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >公告編號</th>
<th style="border:1px solid black;" >公告標題與提要</th>
<th style="border:1px solid black;" >最高的嚴重性等級與資訊安全風險影響</th>
<th style="border:1px solid black;" >重新開機需求</th>
<th style="border:1px solid black;" >受影響的軟體</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-053">MS11-053</a></td>
<td style="border:1px solid black;"><strong>Bluetooth 堆疊中的資訊安全風險可能會允許遠端執行程式碼 (2566220)</strong><br />
<br />
這個資訊安全更新可解決 Windows Bluetooth 堆疊中一項未公開報告的資訊安全風險。 如果攻擊者傳送蓄意製作的 Bluetooth 封包系列到受影響的系統，則此資訊安全風險可能會允許遠端執行程式碼。 攻擊者接下來將能安裝程式，檢視、變更或刪除資料，或建立具有完整使用者權限的新帳戶。 此資訊安全風險僅會影響具備 Bluetooth 功能的系統。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重大</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-054">MS11-054</a></td>
<td style="border:1px solid black;"><strong>Windows 核心模式驅動程式的資訊安全風險可能會允許權限提高 (2555917)</strong><br />
<br />
這個資訊安全更新可解決 Microsoft Windows 中 15 項未公開報告的資訊安全風險。 如果攻擊者從本機登入並執行蓄意製作的應用程式，則最嚴重的資訊安全風險可能會允許權限提高。 攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這些資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-056">MS11-056</a></td>
<td style="border:1px solid black;"><strong>Windows Client/Server Run-time Subsystem 中的資訊安全風險可能會允許權限提高 (2507938)</strong><br />
<br />
此資訊安全更新能解決 Microsoft Windows Client/Server Runtime Subsystem (CSRSS) 中五項未公開報告的資訊安全風險。 如果攻擊者登入使用者的系統並執行蓄意製作的應用程式，則這些資訊安全風險可能允許權限提高。 攻擊者必須擁有有效的登入認證，並能夠登入本機，才能利用這些資訊安全風險。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
權限提高</td>
<td style="border:1px solid black;">需要重新開機</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-055">MS11-055</a></td>
<td style="border:1px solid black;"><strong>Microsoft Visio 中的資訊安全風險可能會允許遠端執行程式碼 (2560847)</strong><br />
<br />
此資訊安全更新可解決 Microsoft Visio 中一項公開揭露的資訊安全風險。 如果使用者開啟與蓄意製作之程式庫檔案位於相同網路目錄的正常 Visio 檔案，此資訊安全風險可能會允許遠端執行程式碼。 成功利用此資訊安全風險的攻擊者可以取得與登入使用者相同的使用者權限。 系統上帳戶使用者權限較低的使用者，其受影響的程度比擁有系統管理權限的使用者要小。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
遠端執行程式碼</td>
<td style="border:1px solid black;">可能需要重新開機</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>
  
資訊安全風險索引  
----------------
  
<span></span>
下表提供本月所述每個資訊安全風險的利用性評估。 資訊安全風險皆根據公告編號和 CVE 編號依序列出。 僅包含資訊安全公告中，嚴重性等級為「重大」或「重要」的資訊安全風險。
  
**我該如何使用這個表格？**
  
您可以運用此表格，針對您可能需要安裝的每一項資訊安全更新，瞭解資訊安全風險在資訊安全公告發行 30 日內遭成功利用而導致程式碼執行與拒絕服務的可能性。 請根據您特定的組態設定，檢閱下列各項評估，決定部署本月份更新的優先次序。 如需關於這些分級意義的資訊，以及決定分級方式的詳細資訊，請參閱 [Microsoft 資訊安全風險索引](http://technet.microsoft.com/zh-tw/security/cc998259.aspx)。
  
在下方欄位中，「最新軟體版本」意指受影響軟體，「較舊軟體版本」意指受影響軟體所有較舊的支援版本，如公告中的「受影響的軟體」或「不受影響的軟體」表格裡所示。
  
| 公告編號                                                            | 資訊安全風險標題                             | CVE ID                                                                           | 最新軟體版本的程式碼執行資訊安全風險評估                                                            | 較舊軟體版本的程式碼執行資訊安全風險評估                                                            | 拒絕服務資訊安全風險評估 | 主要重點 |  
|---------------------------------------------------------------------|----------------------------------------------|----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|--------------------------|----------|  
| [MS11-053](http://technet.microsoft.com/security/bulletin/ms11-053) | Bluetooth 堆疊資訊安全風險                   | [CVE-2011-1265](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1265) |                                                                                                     |                                                                                                     |                          | 1        |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k 釋放後使用資訊安全風險                | [CVE-2011-1874](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1874) |                                                                                                     |                                                                                                     |                          | 2        |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k 釋放後使用資訊安全風險                | [CVE-2011-1875](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1875) |                                                                                                     |                                                                                                     |                          | 3        |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k 釋放後使用資訊安全風險                | [CVE-2011-1876](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1876) |                                                                                                     |                                                                                                     |                          | 4        |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k 釋放後使用資訊安全風險                | [CVE-2011-1877](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1877) |                                                                                                     |                                                                                                     |                          | 5        |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k 釋放後使用資訊安全風險                | [CVE-2011-1878](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1878) |                                                                                                     |                                                                                                     |                          | 6        |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k 釋放後使用資訊安全風險                | [CVE-2011-1879](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1879) |                                                                                                     |                                                                                                     |                          | 7        |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k Null 指標取值資訊安全風險             | [CVE-2011-1880](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1880) |                                                                                                     |                                                                                                     |                          | 8        |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k Null 指標取值資訊安全風險             | [CVE-2011-1881](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1881) |                                                                                                     |                                                                                                     |                          | 9        |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k 釋放後使用資訊安全風險                | [CVE-2011-1882](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1882) |                                                                                                     |                                                                                                     |                          | 10       |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k 釋放後使用資訊安全風險                | [CVE-2011-1883](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1883) |                                                                                                     |                                                                                                     |                          | 11       |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k 釋放後使用資訊安全風險                | [CVE-2011-1884](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1884) |                                                                                                     |                                                                                                     |                          | 12       |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k Null 指標取值資訊安全風險             | [CVE-2011-1885](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1885) |                                                                                                     |                                                                                                     |                          | 13       |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k 不正確的參數允許資訊洩漏資訊安全風險  | [CVE-2011-1886](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1886) |                                                                                                     |                                                                                                     |                          | 14       |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k Null 指標取值資訊安全風險             | [CVE-2011-1887](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1887) |                                                                                                     |                                                                                                     |                          | 15       |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k Null 指標取值資訊安全風險             | [CVE-2011-1888](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1888) |                                                                                                     |                                                                                                     |                          | 16       |  
| [MS11-056](http://technet.microsoft.com/security/bulletin/ms11-056) | CSRSS 本機 EOP AllocConsole                  | [CVE-2011-1281](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1281) |                                                                                                     |                                                                                                     |                          | 17       |  
| [MS11-056](http://technet.microsoft.com/security/bulletin/ms11-056) | CSRSS 本機 EOP SrvSetConsoleLocalEUDC        | [CVE-2011-1282](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1282) |                                                                                                     |                                                                                                     |                          | 18       |  
| [MS11-056](http://technet.microsoft.com/security/bulletin/ms11-056) | CSRSS 本機 EOP SrvSetConsoleNumberOfCommand  | [CVE-2011-1283](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1283) |                                                                                                     |                                                                                                     |                          | 19       |  
| [MS11-056](http://technet.microsoft.com/security/bulletin/ms11-056) | CSRSS 本機 EOP SrvWriteConsoleOutput         | [CVE-2011-1284](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1284) |                                                                                                     |                                                                                                     |                          | 20       |  
| [MS11-056](http://technet.microsoft.com/security/bulletin/ms11-056) | CSRSS 本機 EOP SrvWriteConsoleOutputString   | [CVE-2011-1870](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1870) |                                                                                                     |                                                                                                     |                          | 21       |  
| [MS11-055](http://technet.microsoft.com/security/bulletin/ms11-055) | Microsoft Visio 不安全程式庫載入資訊安全風險 | [CVE-2010-3148](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3148) |                                                                                                     |                                                                                                     |                          | 22       |  
| 範例                                                                | 範例                                         | 範例                                                                             | [2](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) – 可能撰寫出偶爾可利用此漏洞的程式碼 | [2](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) – 可能撰寫出偶爾可利用此漏洞的程式碼 | 暫時                     | (無)     |  
| 範例                                                                | 範例                                         | 範例                                                                             | [3](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) – 不太可能撰寫出可利用此漏洞的程式碼 | [1](http://technet.microsoft.com/zh-tw/security/cc998259.aspx) - 可能撰寫出可持續利用此漏洞的程式碼 | 暫時                     | (無)     |
  
受影響的軟體及下載位置  
----------------------
  
<span></span>
下表依據主要的軟體類別和嚴重性依序列出公告。
  
**我該如何使用這些表格？**
  
請用這些表格來瞭解可能需要安裝的資訊安全更新有哪些。 您應該查看此處列出的每一種軟體程式或元件，看看是否有與安裝相關的�全性更新。 若軟體程式或更新出現在清單中，則相關可用軟體更新也會以超連結方式提供，也會列出軟體更新的嚴重性等級。
  
**注意：**一項資訊安全風險可能需要安裝數個資訊安全更新才能妥善解決。 請參閱各公告的相關欄位以確認您必須安裝的更新。安裝的項目視您系統上所安裝的程式或元件而定。
  
#### Windows 作業系統與元件

 
<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="4">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-053**](http://technet.microsoft.com/security/bulletin/ms11-053)
</td>
<td style="border:1px solid black;">
[**MS11-054**](http://technet.microsoft.com/security/bulletin/ms11-054)
</td>
<td style="border:1px solid black;">
[**MS11-056**](http://technet.microsoft.com/security/bulletin/ms11-056)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=d7a47370-f415-46ea-9a82-a943f743c8b6)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=425c705e-94f2-4fa6-9df2-dc71897215fa)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=db89d88f-d0d4-4ed6-8589-bf27557c0304)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c389fa20-677e-49b6-af44-781e5522d08b)  
(重要)
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-053**](http://technet.microsoft.com/security/bulletin/ms11-053)
</td>
<td style="border:1px solid black;">
[**MS11-054**](http://technet.microsoft.com/security/bulletin/ms11-054)
</td>
<td style="border:1px solid black;">
[**MS11-056**](http://technet.microsoft.com/security/bulletin/ms11-056)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7a26a437-a705-4d48-8389-50f159a39891)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=dff4c67a-8c8b-4d7d-84c7-57429becf0ff)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=95393f89-0b05-4243-95ed-17bcdad24bfb)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1615a995-9a04-440a-ae52-5917738f0ecb)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2003 SP2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=3b094bdb-4150-44f2-a638-afd5f41b00a3)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2003 SP2](http://www.microsoft.com/downloads/details.aspx?familyid=a81c011d-eeea-4383-9efb-df70515ab357)  
(重要)
</td>
</tr>
<tr>
<th colspan="4">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-053**](http://technet.microsoft.com/security/bulletin/ms11-053)
</td>
<td style="border:1px solid black;">
[**MS11-054**](http://technet.microsoft.com/security/bulletin/ms11-054)
</td>
<td style="border:1px solid black;">
[**MS11-056**](http://technet.microsoft.com/security/bulletin/ms11-056)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 1 和 Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=6bff74ac-45f3-4585-92da-316921b458fa)<sup>[1]</sup>
(KB2561109)  
(重大)  
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a1e5aa7d-5f38-4ce2-9575-4b4cb7520160)  
(KB2532531)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c1fe1e53-34d5-497e-8ba2-50caa8dc1158)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a5e192af-dae5-47ef-a9d0-f761a8caa974)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=849d2694-c8b3-4670-8203-912661bccabf)<sup>[1]</sup>
(KB2561109)  
(重大)  
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4287eeb4-ab29-4727-83f2-260d838b44d4)  
(KB2532531)  
(重大)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7bc0a285-cc32-4c6b-abee-d92130d459b7)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1007f5d3-9be1-4f03-a3f0-12ddb555653c)  
(重要)
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-053**](http://technet.microsoft.com/security/bulletin/ms11-053)
</td>
<td style="border:1px solid black;">
[**MS11-054**](http://technet.microsoft.com/security/bulletin/ms11-054)
</td>
<td style="border:1px solid black;">
[**MS11-056**](http://technet.microsoft.com/security/bulletin/ms11-056)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b88d0471-4427-4835-9446-db71116481f0)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows Server 2008 和適用於 32 位元系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=36e3dbaf-36f5-4c74-8f11-ecbef46f58e1)\*  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d3df6184-3e3c-4949-a1ee-293ec68f8149)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 和適用於 x64 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b43d2ab5-e281-4c6b-bb37-1f1b5d86ac82)\*  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9e021d69-7f0c-457f-af86-07e760d8f421)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 和適用於 Itanium 型系統的 Windows Server 2008 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b70209f2-1c51-45af-b3c4-3473aebcdb35)  
(重要)
</td>
</tr>
<tr>
<th colspan="4">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-053**](http://technet.microsoft.com/security/bulletin/ms11-053)
</td>
<td style="border:1px solid black;">
[**MS11-054**](http://technet.microsoft.com/security/bulletin/ms11-054)
</td>
<td style="border:1px solid black;">
[**MS11-056**](http://technet.microsoft.com/security/bulletin/ms11-056)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重大**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7f811b75-c3ff-411a-aaa9-126dce34cc01)  
(KB2532531)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=41db1b2f-f862-43bb-89bc-4b97737e5cb9)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 32 位元系統的 Windows 7 和適用於 32 位元系統的 Windows 7 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ac3b435c-8caf-40cc-8f13-b52261b3b9e6)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows 7 和適用於 x64 型系統的 Windows 7 Service Pack 1
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7 和適用於 x64 型系統的 Windows 7 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=90b2da71-18f9-46ee-9e3d-b08620ca06aa)  
(KB2532531)  
(重大)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7 和適用於 x64 型系統的 Windows 7 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=211abdc6-40c7-4bfc-8c2d-be72981f311e)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows 7 和適用於 x64 型系統的 Windows 7 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=64e5f889-fa46-4884-9b22-3ba4e2fba1b9)  
(重要)
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-053**](http://technet.microsoft.com/security/bulletin/ms11-053)
</td>
<td style="border:1px solid black;">
[**MS11-054**](http://technet.microsoft.com/security/bulletin/ms11-054)
</td>
<td style="border:1px solid black;">
[**MS11-056**](http://technet.microsoft.com/security/bulletin/ms11-056)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
無
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=4f54e498-3825-407d-a036-1900a65d34f1)\*  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 x64 型系統的 Windows Server 2008 R2 和適用於 x64 型系統的 Windows Server 2008 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=b99a40cf-8a31-43d9-bd0b-a458a533068b)\*  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
適用於 Itanium 型系統的 Windows Server 2008 R2 和適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1
</td>
<td style="border:1px solid black;">
不適用
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2 和適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=e7ae39e8-1154-4a13-8598-29d4a6358762)  
(重要)
</td>
<td style="border:1px solid black;">
[適用於 Itanium 型系統的 Windows Server 2008 R2 和適用於 Itanium 型系統的 Windows Server 2008 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=784efc20-3a41-42ab-b48d-51fd59d71523)  
(重要)
</td>
</tr>
</table>
 
**Windows Server 2008 和 Windows Server 2008 R2 注意事項**

**\*Server Core 安裝會受影響。** 無論上述受支援的 Windows Server 2008 或 Windows Server 2008 R2 版本是否使用 Server Core 安裝選項安裝，這個更新均以相同的嚴重性等級套用。 如需此安裝選項的詳細資訊，請參閱 TechNet 文章：[管理 Server Core 安裝](http://technet.microsoft.com/zh-tw/library/ee441255(ws.10).aspx)和[維護 Server Core 安裝](http://technet.microsoft.com/zh-tw/library/ff698994(ws.10).aspx) (英文)。 請注意，Server Core 安裝選項不適用於某些 Windows Server 2008 和 Windows Server 2008 R2 版本；請參閱[比較 Server Core 安裝選項](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (英文)。

**MS11-053 注意事項**

<sup>[1]</sup>只有在安裝選用的 Windows Vista Feature Pack for Wireless 時，才會影響 Windows Vista Service Pack 1。

#### Microsoft Office 套件及軟體

 
<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Office 套件和元件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告編號**
</td>
<td style="border:1px solid black;">
[**MS11-055**](http://technet.microsoft.com/security/bulletin/ms11-055)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**彙總嚴重性等級**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=1c7b2a5b-4aa6-4006-90bf-89f8b2b7becd)  
(KB2493523)  
(重要)
</td>
</tr>
</table>
 

偵測與部署工具及指南
--------------------

<span></span>
**資訊安全中心**

管理您必須部署到您組織中的伺服器、桌上型電腦及�動電腦的軟體和資訊安全更新。 如需更多資訊，請參閱 [TechNet 更新管理中心](http://technet.microsoft.com/zh-tw/updatemanagement/default.aspx) (英文)。 [TechNet Security Center](http://technet.microsoft.com/zh-tw/security/default.aspx) 提供 Microsoft 產品安全性的其他資訊。 消費者可以造訪[在家上網的安全性](http://www.microsoft.com/taiwan/security/default.mspx)網站，只要按一下 \[最新資訊安全更新\] 即可在此網站取得此資訊。

資訊安全更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 以及 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) 取得。 資訊安全更新也可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得。 您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。

對於 Microsoft Office for Mac 的客戶，Microsoft AutoUpdate for Mac 可協助您保持最新的 Microsoft 軟體。 如需使用 Microsoft AutoUpdate for Mac 的詳細資訊，請參閱[自動檢查軟體更新](http://mac2.microsoft.com/help/office/14/zh-tw/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea) (英文)。

最後，您可以從 [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155) 下載資訊安全更新。 Microsoft Update Catalog 提供透過 Windows Update 及 Microsoft Update 所公佈內容的搜尋式目錄，包括資訊安全更新、驅動程式和 Service Pack。 只要以資訊安全公告編號 (例如：MS07-036) 執行搜尋，您就可新增所有適用的更新到置物籃 (包括同一項更新的不同語言)，再下載到您自選的資料夾中。 如需更多關於 Microsoft Update Catalog 的相關資訊，請參閱 [Microsoft Update Catalog 常見問題集](http://go.microsoft.com/fwlink/?linkid=97900)。

**偵測與部署指南**

Microsoft 針對資訊安全更新提供偵測和部署指南。 本指南所含之建議和資訊，能幫助 IT 專業人員瞭解如何使用用於資訊安全更新的偵測和部署的各種工具。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 961747](http://support.microsoft.com/kb/961747/zh-tw)。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) 能讓系統管理員掃描本機和遠端系統，偵查任何缺少資訊安全更新以及一般資訊安全設定錯誤的狀況。 如需更多有關 MBSA 的資訊，請造訪 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) 網站 (英文)。

**Windows Server Update Services**

透過 Windows Server Update Services (WSUS)，系統管理員可迅速而可靠地將 Microsoft Windows 2000 作業系統及更新版本、Office XP 及更新版本、Exchange Server 2003 及 SQL Server 2000 適用的最新重大更新與資訊安全更新部署到 Microsoft Windows 2000 及更新版本的作業系統中。

如需更多關於利用 Windows Server Update Services 部署資訊安全更新的資訊，請造訪 [Windows Server Update Services](http://technet.microsoft.com/zh-tw/wsus/default.aspx) 網站。

**System Center Configuration Manager 2007**

Configuration Manager 2007 軟體更新管理可簡化遞送和管理企業中 IT 系統更新的繁複作業。 IT 系統管理員可以使用 Configuration Manager 2007 遞送 Microsoft 產品更新給各種裝置，包括桌上型電腦、筆記型電腦、伺服器及行動裝置。

Configuration Manager 2007 中的自動資訊安全風險評估會找出更新需求並報告建議動作。 Configuration Manager 2007 中的軟體更新管理是建置在 Microsoft Windows Software Update Services (WSUS) 上，經過時間考驗，為全球 IT 系統管理員所熟悉的更新基礎架構。 如需更多有關系統管理員如何使用 Configuration Manager 2007 來部署更新的資訊，請參閱[軟體更新管理](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx) (英文)。 如需更多有關 Configuration Manager 的資訊，請造訪 [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx)。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) 提供了深具彈性的企業解決方案，能夠對更新程式進行方便的管理。 透過 SMS，系統管理員能判斷有哪些 Windows 系統需要資訊安全更新，並控制更新程式在企業中的部署，同時將對使用者造成的干擾降到最低。

**注意：System Management Server 2003 自 2010 年 1 月 12 日起不受主流支援。**如需更多有關產品生命週期的資訊，請造訪 [Microsoft 產品技術支援週期](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle)。 現已推出新版的 SMS，System Center Configuration Manager 2007；請參閱前段的＜System Center Configuration Manager 2007＞一節。

如需更多有關系統管理員如何使用 SMS 2003 來部署資訊安全更新的資訊，請參閱 [Microsoft Systems Management Server 2003 的案例與程序： 軟體發佈和補充程式管理](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en) (英文)。 如需 SMS 的相關資訊，請造訪 [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/zh-tw/systemcenter/bb545936.aspx)。

**注意：**SMS 使用 Microsoft Baseline Security Analyzer 提供廣泛的資訊安全公告更新偵測與部署支援。 不過這些工具可能無法偵測部分的軟體更新。 在這些情況中，系統管理員可以利用 SMS 的清查功能，判斷特定系統所需要的更新程式。 如需關於此程序的詳細資訊，請參閱[使用 SMS 軟體發佈功能部署軟體更新](http://go.microsoft.com/fwlink/?linkid=33341)。 某些資訊安全更新程式在電腦重新啟動之後，會需要系統管理員的權限。 系統管理員可使用 Elevated Rights Deployment Tool (隨 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en) (英文) 提供) 來安裝這些更新。

**Update Compatibility Evaluator 和 Application Compatibility Toolkit**

更新時常會寫入您應用程式執行所需的相同檔案和登錄設定。 這可能會觸發不相容性，而拉長部署資訊安全更新的時間。 您可以使用 [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 隨附的 [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 元件，針對所安裝的應用程式簡化其測試和驗證 Windows 更新的過程。

Application Compatibility Toolkit (ACT) 包含必要的工具和文件，可讓您在環境中部署 Microsoft Windows Vista、Windows Update、Microsoft 資訊安全更新或新版 Windows Internet Explorer 之前，評估及減輕應用程式相容性問題。

### 其他資訊

#### Microsoft Windows 惡意軟體移除工具 (英文)

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services，及下載中心發行 Microsoft Windows 惡意軟體移除工具的更新版本。

#### MU、WU 及 WSUS 上的非資訊安全更新

如需在 Windows Update 和 Microsoft Update 上發行的非資訊安全更新之相關資訊，請參閱：

-   [icrosoft 知識庫文件編號 894199](http://support.microsoft.com/kb/894199)： Software Update Services 與 Windows Server Update Services 的說明內容有所變動。 其中也包括所有 Windows 的內容。
-   [過去幾個月發行的 Windows Server Update Services 更新](http://technet.microsoft.com/zh-tw/wsus/bb456965.aspx)。 顯示除了 Microsoft Windows 以外其他 Microsoft 產品的所有全新、修訂版或重新發行的更新。

#### Microsoft 主動保護計畫 (MAPP)

為了增強客戶的資訊安全保護，Microsoft 將在每月發行資訊安全更新之前，提前向重要資訊安全軟體提供者提供資訊安全風險資訊。 資訊安全軟體提供者可利用此資訊安全風險資訊，透過其資訊安全軟體或裝置 (如防毒軟體、網路入侵偵測系統、或主機入侵預防系統)，為客戶提供更新的保護措施。 如果要判斷是否有資訊安全軟體提供者的主動保護可用，請造訪由 [Microsoft 主動保護計畫 (MAPP) 合作夥伴](http://go.microsoft.com/fwlink/?linkid=215201)上列出的計畫合作夥伴所提供的主動保護計畫網站。

#### 資訊安全策略與社群

**更新程式管理策略**

[更新程式管理資訊安全指南](http://technet.microsoft.com/zh-tw/library/bb466251(en-us).aspx)提供您有關套用資訊安全更新的 Microsoft 最佳實作建議的其他資訊。

**取得其他資訊安全更新**

其他資訊安全問題的更新可由下列位置取得：

-   資訊安全更新可以從 [Microsoft 下載中心](http://go.microsoft.com/fwlink/?linkid=21129)取得， 您也可以利用「資訊安全更新」("security update") 關鍵字搜尋輕易地找到資訊安全更新。
-   客戶平台的更新可從 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 取得。
-   您可透過下載中心，以安全性和重大更新 ISO CD 影響檔的方式取得本月份 Windows Update 提供的資訊安全更新。 如需更多資訊，請參閱 [Microsoft 知識庫文件編號 913086](http://support.microsoft.com/kb/913086/zh-tw)。

**IT 專業人員資訊安全社群**

在 [IT 專業人員資訊安全區社群](http://technet.microsoft.com/zh-tw/security/cc136632.aspx)上，學習如何提升安全性以及改善您的 IT 基礎結構，與其他的 IT 專業人員共同參與各類安全性議題的討論。

#### 感謝

Microsoft [感謝](http://go.microsoft.com/fwlink/?linkid=21127)下列人士協助我們一同保護我們的客戶：

-   感謝 [Norman](http://www.norman.com) 的 Tarjei Mandt 回報 ms11-054 中描述的 14 項問題
-   感謝[北京大學資訊安全系](http://www.ss.pku.edu.cn/en/)的 Liang Yin 先生、Sihan Qing 和 Weiping Wen 教授、Husheng Zhou 先生回報 ms11-054 中描述的一項問題
-   感謝 [Hispasec](http://www.hispasec.com/)[Virustotal](http://www.virustotal.com/) 的 Matthew 'j00ru' Jurczyk 回報 ms11-056 中描述的五項問題

#### 支援

-   所列出的受影響軟體版本已經過測試判斷哪些版本會受到影響。 其他版本超出它們的支援週期。 若要瞭解您的軟體版本的支援週期，請造訪 [Microsoft 產品技術支援週期網站](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美國及加拿大地區客戶可洽詢[資訊安全支援](http://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 以取得技術支援。 與資訊安全更新有關的支援電話不另外收費。 如需更多可用支援選項的資訊，請參閱 [Microsoft 技術支援服務](http://support.microsoft.com/?ln=zh-tw)。
-   不同國家的客戶，可以從當地的 Microsoft 分公司取得支援。 與資訊安全更新有關的支援電話不另外收費。 如需更多關於連絡 Microsoft 技術支援的資訊，請造訪[世界各地技術支援](http://go.microsoft.com/fwlink/?linkid=21155)網站。

#### 免責聲明

Microsoft 知識庫 (Microsoft Knowledge Base) 中的資訊係以其「現狀」提供，並不提供任何形式之擔保。 Microsoft 不做任何明示或默示的責任擔保，包括適售性以及適合某特定用途之擔保責任。 無論任何情況下的損害，Microsoft Corporation 及其供應商皆不負任何法律責任，包括直接、間接、偶發、衍生性、所失業務利益或特殊損害。即使 Microsoft Corporation 及其供應商已被告知此類損害的可能性亦不負任何責任。 某些地區不允許排除及限制衍生性或附隨損害賠償責任，因此前述限制不適用於這些地區。

#### 修訂

-   V1.0 (2011 年 7 月 13 日)： 公告摘要發行。

*Built at 2014-04-18T01:50:00Z-07:00*
