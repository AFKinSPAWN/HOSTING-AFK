# HOSTING-AFK
$X = 451
$Y = 250

HotKeySet("1", "Start")
HotKeySet("2", "Stop")

While 1
Sleep(10)
WEnd

Func Start()
WinActivate("Counter-Strike: Global Offensive")

While 1
	MouseMove(1430, 1001, 10)
	Sleep(20)
	MouseClick("left")


MouseMove($X, $Y, 10)
Sleep(20)
MouseClick("left")
Wend
EndFunc

Func Stop()
   Exit 0
EndFunc
