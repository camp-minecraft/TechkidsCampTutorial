### @hideIteration true

# TechkidsCAMP

## エージェントをつかって、ブロックをせっちしよう！

エージェントをつかってブロックをせっちするには、
``||agent.エージェントにまえへおかせる||``ブロックをつかうよ！
右下の![](https://raw.githubusercontent.com/camp-minecraft/TechkidsCampTutorial/master/images/playbutton.png)を押して、「run」とチャットらんににゅうりょくしてプログラムをうごかしてみよう！

```template
player.onChat("run", function () {
    agent.place(DOWN)
})

```