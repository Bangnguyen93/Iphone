#!name=Unlock Nhaccuatui
#!desc=Nhaccuatui

[MITM]
hostname = %APPEND% graph.nhaccuatui.com

[Script]
Nhaccuatui = type=http-response,pattern=^https:\/\/graph\.nhaccuatui\.com\/.*\/users\/info,requires-body=1,max-size=0,script-path=https://raw.githubusercontent.com/langkhach270389/Surge-LK/new/scripts/langkhach/nhaccuatui.js,script-update-interval=-1 
