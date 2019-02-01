# bdlauncher
BedRockServer launcher with mods support

LD_LIBRARY_PATH=. LD_PRELOAD=./bin/launch.so ./bedrock_server

put mods(bin/a.so,amoney.so,ban.so,land.so) into folder mods,and start the server.

example plugin intro:
# ban 黑名单
<pre>
/ban PlayerName
/unban PlayerName
</pre>
# money 简单经济
<pre>
/money query [Playername] 查钱（初始500)
/monry set <playername> <int:money> 设置钱
</pre>
 
# land 迫真领地
 <pre>
/land start
/land end
then touch the ground to determine the pos of land 先输指令，然后点地确定起点终点
/land buy
buy the land 买(价格 每个方块10）
/land invite <PlayerName>
share permissions with others (分享)
/land sell
sell the land on which you stand.(OP can force sell lands) （卖)
 </pre>
