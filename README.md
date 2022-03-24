# Installation
WinWait("TestRun","") If Not WinActive("TestRun","") Then WinActivate("TestRun","") WinWaitActive("TestRun","") Send("{ALTDOWN}n{ALTUP}") While 1 &lt;> 1 WinWait("TestRun ","Driver Installation") If Not WinActive("TestRun ","Driver Installation") Then WinActivate("TestRun ","Driver Installation") WinWaitActive("TestRun ","Driver Installation") Send("{ENTER}") WinWait("TestRun
