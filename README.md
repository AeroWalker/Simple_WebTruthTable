# Simple_WebTruthTable
一个基于C# Blazor Webassembly的真值表计算器。支持C/C++/C#的逻辑运算符和+ * ' ^直接表达，大小写不敏感
适用于 模电真值表验算 直接输入表达式即可计算与比较

输入：  
A+(B+C')'(A+B'+C)(A+B+C)  
A+B'C  
A+BC  
输出：  
A B C |  
0 0 0 | 0 0 0  
0 0 1 | 1 1 0  
0 1 0 | 0 0 0  
0 1 1 | 0 0 1  
1 0 0 | 1 1 1  
1 0 1 | 1 1 1  
1 1 0 | 1 1 1  
1 1 1 | 1 1 1  
Not same  

测试用网站：https://toolbox.galigali.xyz/
