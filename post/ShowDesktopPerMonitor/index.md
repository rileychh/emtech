---
authors: elvismao
tags: [Windows]
categories: [生活駭客]
date: 2022-08-18
---

# 【ShowDesktopPerMonitor】進化 Win+D！多螢幕不互相干擾/所有桌面視窗一鍵顯示

使用多個螢幕可以使工作效率大幅提升。不過如果使用 Win+D 來隱藏視窗、會一次隱藏所有螢幕的所有的視窗。
不過透過 ShowDesktopPerMonitor 可以模擬 Win+D 的隱藏視窗。除了可以分開螢幕控制以外，它的隱藏視窗是連工作列都看不到...（要怎麼使用就看你了！）

# 安裝

這個專案是開源在 Github 上的，基本上可以安心使用。雖然已經很久沒有更新了，但目前沒有任何問題。

{{notice}}
ShowDesktopPerMonitor

- 開發者:CryptKat
- 類型：免費開源軟體
- 網址：[Github](https://github.com/CryptKat/ShowDesktopPerMonitor/)
- [下載連結](https://github.com/CryptKat/ShowDesktopPerMonitor/releases/tag/1.0)
  {{noticed}}

# 設定

請先到上面下載連結下載`ShowDesktopPerMonitor_1.0.zip`並解壓縮。解壓縮後雙擊直接打開就可以了。

如果你是使用 Windows 10 可以將“Xbox Game Monitoring”關閉（原 Win+G）,，預防你的 G 會沒辦法按。
請到註冊表的`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\xbgm\Start`並將數值改成`4`

# 多個桌面

如果你會使用多個桌面（Ctrl+Win+D) 的話你會發現當你按下 Win+D 要顯示的時候，不只這個桌面，所有這個螢幕的桌面視窗都會跳出來。

可以說這是一個 Bug，也可以說是一個*特別的功能*

# 關閉軟體

如果要讓它停止運行，請點擊螢幕右下角往上的箭頭，對 ShowDesktopPerMonitor 圖示點擊右鍵，並結束它
