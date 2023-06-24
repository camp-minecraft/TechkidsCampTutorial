### @hideIteration true
# TechkidsCAMP

## くりかえしってなにかな？ @unplugged

プログラミングでは、めんどうなさぎょうをくりかえすことができるよ！
「くりかえし」をつかえば、おなじさぎょうを100かいでも1000かいでもやらせることができるよ！

## エージェントにくりかえさせてみよう！

エージェントに「くりかえし」のプログラムをやらせるには、``||agent.くりかえし 4かい||``ブロックをつかうよ！
ブロックの中のすうじをかえて、くりかえすかいすうをきめることができるよ！

みぎしたの![](https://raw.githubusercontent.com/camp-minecraft/TechkidsCampTutorial/master/images/playbutton.png)をおして、「run」とチャットらんににゅうりょくしてプログラムをうごかしてみよう！

```template
player.onChat("run", function () {
    for (let index = 0; index < 4; index++) {
        agent.place(FORWARD)
        agent.turn(RIGHT_TURN)
    }
})

```