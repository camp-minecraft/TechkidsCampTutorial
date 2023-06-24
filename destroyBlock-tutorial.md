### @hideIteration true
# TechkidsCAMP

## エージェントをつかって、ブロックをせっちしよう！

エージェントをつかってブロックをこわすには、
``||agent.エージェントにまえをはかいさせる||``ブロックをつかうよ！
ほうこうをえらんで、エージェントがどのほうこうのブロックをはかいするかきめよう！

みぎしたの![](https://raw.githubusercontent.com/camp-minecraft/TechkidsCampTutorial/master/images/playbutton.png)をおして、「run」とチャットらんににゅうりょくしてプログラムをうごかしてみよう！

```template
player.onChat("run", function () {
    agent.destroy(LEFT)
    agent.destroy(FORWARD)
    agent.destroy(RIGHT)
})

```