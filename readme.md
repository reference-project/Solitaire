##solitaire html5 微信小游戏，由于全用Javascript编写，涉及到很多小操作，相对计算量比较大，需要对算法和javascript掌握熟练。
##游戏玩法
Poker Solitai在一个5*5的游戏板上玩。洗好牌后每次从一副扑克牌里抽取一张，把它放到游戏板里的任何一个位置。
目标是使每一行每一列和对角线方向尽可能的形成好的poker hands（对，多对，同花，同花顺等等）。
* 得分统计：
	* 对子：1
	* 两对：2
	* 三条：3
	* 顺子：4
	* 葫芦：8（三条加一对）
	* 铁支：25（四张一样数字）
	* 同花：5
	* 同花顺：50
	* 同花大顺：250（花色相同的10，j，q，k，a）