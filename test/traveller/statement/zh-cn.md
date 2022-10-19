{{ self.title() }}

{{ s('background') }}

公元114514年,旅行者来到了遥远的提瓦特大陆。

热心肠的XioasDog会帮助普通人打怪捏

但是最近XioasDog忙着练AK来不及打怪,所以找来了你帮忙

相信你一定不会拒绝的吧！

{{ s('description') }}

已知从起点出发，到终点共有$m$个怪点($m+1$是终点)，每个怪点可能会出现一些怪，你的队伍共有$n$个人，第$i$个人会受到第$j$个怪点的攻击，发起的概率为$p_{i,j}，p_{i,j}={G_{i,j}\over
\sum\limits_{k=1}^nG_{k,j}}$

（如果某人被攻击,状态记为死亡,怪物下一次对他的攻击不计,一个怪点只会对一人发起攻击）

如若队伍里的所有人都记为死亡状态，就会复活并回到出生点。

现求从起点走到终点的步数期望

{{ s('input format') }}

{{ self.input_file() }}

第一行两个正整数 $n,m$

接下来 $n$ 行，每行 $m$ 个整数，分别代表 $G_{i,j},G_{i,j}\le 10^3$

含义皆如题目表示

{{ s('output format') }}

{{ self.output_file() }}

一个数,**表示从起点走到终点模$10^9+7$下的步数期望**

(无法走到输出inf)

{{ s('sample', 1) }}

{{ self.sample_text() }}

{{ s('sample', 2) }}

{{ self.sample_text() }}

{{ s('subtasks') }}

{{ tbl('data',width = [1,1,1]) }}