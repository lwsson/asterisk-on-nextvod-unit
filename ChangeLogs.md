#Change Logs

# Change Logs #

### 2013-02-02 version 1.0.4: ###
  * [修正] 設定檔 musiconhold.conf

### 2013-01-30 version 1.0.3: ###
  * [新增] 防止SIP暴力破解的保護機制
  * [修正] 目錄 /mnt/usb/asterisk\_record 不存在
  * [新增] 支援 OpenVPN
  * [修正] Voice Menu Prompts 無法上傳檔案

### 2013-01-05 version 0.7.2: ###
  * [修正] 修改 sip.conf，srvlookup = no
  * [新增] Web-UI: 網路設定 PPPoE
  * [新增] msmtp 外寄郵件功能(語音留言通知)

### 2012-12-19 version 0.6.3: ###
  * [新增] System Status 顯示 NextPBX 版號
  * [修正] System Status 移除 Conference Room
  * [修正] 停用遙控器服務程序
  * [修正] 修改 RTP port 10000-10100 (rtp.conf)
  * [新增] 新增防火牆機制且開機後自動啟動
  * [修正] Music on Hold(來電答鈴)功能修正

### 2012-12-10 version 0.5.4.1: ###
  * [新增] 語音信箱操作支援中文語音(台灣適用)，需依照教學先安裝相關語音檔。
  * [修正] Web-UI: System Status > System Info 不會自動斷行(reported by JerryChen)
  * [修正] Monitor 儲存路徑
  * [修正] 優化 Asterisk 服務，停用不必要的模組

### 2012-12-3 version 0.5.2: ###
  * [修正] Web-UI: Voice Menu Prompts 無法上傳錄音檔
  * [修正] Voicemail 儲存路徑
  * [修正] 移除 Conferencing 選項
  * [新增] 支援 PPPoE ADSL 網路連線
  * [修正] Web-UI: CDR 日期不正確

### 2012-11-27 version 0.5.0: ###
  * [新增] 維護用的靜態 IP 位址 192.168.199.199，使用方式在 OSSLab。
  * [新增] GoogleVoice 免費撥美/加電話，設定教學在 OSSLab。
  * ~~[修正] 修改 chan\_mgcp.c (by Terry)~~

### 2012-11-19 version 0.4.3: ###
  * [新增] 支援 iptables 指令
  * [新增] Cron 服務
  * [修正] Web-UI: Call Detail Records, Asterisk Logs 無法顯示
  * [新增] 每日零點網路校時
  * [修正] Web-UI: Backup/Restore 目錄搬移

### 2012-11-11 version 0.4: ###
  * [新增] Web-UI: 時區設定
  * [新增] Web-UI: 網路設定，支援固定IP/DHCP 模式

### 2012-10-29 version 0.3.1: ###
  * [修正] Asterisk 以下錯誤訊息:
    * WARNING 1858 res\_phoneprov.c: Unable to get IP of eth1: No such device
    * WARNING 411 chan\_sip.c: Codec configuration errors found in line 172 : allow = undefined,ulaw,alaw,gsm
    * ERROR 1874 cdr\_csv.c: Unable to re-open master file /mnt/usb/asterisk\_log//cdr-csv//Master.csv : No such file or directory
    * WARNING 2933 loader.c: Error loading module 'chan\_oss.so': libSDL-1.2.so.0: cannot open shared object file: No such file or directory

### 2012-10-28 version 0.3: ###
  * [修正] 系統重啟後自動網路校時
  * [新增] 支援 SFTP 傳檔
  * [新增] 網頁介面-設定網路

### 2012-10-25 version 0.2.1: ###
  * [修正] Web-UI 不能登入問題

### 2012-10-22 version 0.2: ###
  * 安裝 sshd 遠端登入，可以取代較不安全的 telnet
  * 修改 Console 的歡迎訊息
  * 設定 hostname=localhost

### 2012-10-14 version 0.1: ###
  * First release
  * 安裝 Asterisk 1.8 IP PBX 軟體
  * 安裝 asterisk-gui 管理介面
  * 安裝校時套件
  * 移除 IPTV.exe 等程序
  * 修改 Telnet 可以用帳號/密碼方式登入
  * 新增系統可以設定時區