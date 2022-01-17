No operators, no conditions, no loops this time, function call is all you need!

nc eof.h4ck3r.quest 1337

The English version of this description is provided in share/README.md

Rules

跟絕大多數的 online judge 一樣，輸入是從 standard input 輸入的。
你只能用：(function) name (e.g. print), function call (e.g. str()), constants (int, float, byte, string etc.) 來撰寫程式。
你的程式只能包含一個 expression —— 也就是說它應該是可以被 eval 的。
你無法使用 exec、eval、import 或類似的東西來作弊（直接寫普通的 Python 就不好玩了嘛）
反正原始碼都給了，如果你仍然有不理解的地方，直接去讀就對了（或直接來問我）
解完三題即可拿到 FLAG！
Note

你不一定需要讀原始碼，但是：

如果你不明白為什麼它說「This is not leetcall!」 你可以看 main.py 裡的 is_valid_source 是怎麼檢查的

如果你好奇我是怎麼擋掉 eval、exec 等東西，或是不明白究竟擋了哪些你可以看 sandbox.tpl.py

這不是一個 sandbox escape challenge（但如果你想 escape 看看還是可以啦）

