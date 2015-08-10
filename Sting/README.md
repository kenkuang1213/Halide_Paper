q1.這是台大碩士論文的模板(2015/7) 裡面示範了大多數會遇到的狀況
2.語法請自行google 網路上很多中文教學
3.關於圖片 有些人想要控制圖片在自己想要的位置 所以我裡面示範了一下
語法如下
\usepackage{float}
\begin{figure}[H]  ％重點是後面的[H]
foo
\end{figure}
不過這樣大小和排版要自己控制
4.關於參考書目 因為latex排序方式有點詭異 看起來不自然
要修改順序請改thesis.tex中
\bibliographystyle{unsrt} %這樣可以依照被參考到的順序做排序
5.編譯方式
For Windows(Ref: http://leavedcorn.pixnet.net/blog/post/24773932-新手安裝LaTeX懶人教學(step-by-step) )
	Install MiKTex: http://www.miktex.org/  %compiler
	Install Texmaker: http://www.xm1math.net/texmaker/  %IDE
	編譯方式Bibtex thesis.bib -> (xelatex thesis.tex)*2 
	缺的套件會自動補上
For Ubuntu (Ref: http://pangomi.blogspot.tw/2012/11/latex-in-ubuntu.html)
	Install Tex Live: Go to Softcenter
	sudo apt-get install texlive-latex-extra  %other packages
	Install 標楷體:  Copy kaiu.ttf to $HOME/.fonts 
	做到這邊make其實就可以了
	如果你要IDE的話	
	Install Texmaker: http://www.xm1math.net/texmaker/  %IDE 
	編譯方式如 windows
For Mac
	我討厭有錢人 誰理你
For ShareLatex
	國外網站怎麼可能會有標楷體 Yellow Monkeys Kappa

