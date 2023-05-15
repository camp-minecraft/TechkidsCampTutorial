### @hideIteration true
# QureoMinecraft

## エージェントをつかって、ブロックをおいてもらおう！

エージェントをつかってブロックをおいてもらうには、
``||agent.エージェントに前へ置かせる||``ブロックをつかうよ！
ほうこうをえらんで、エージェントがどのほうこうにブロックをおいてもらうかきめよう！

みぎしたの![](https://raw.githubusercontent.com/camp-minecraft/TechkidsCampTutorial/master/images/playbutton.png)をおしたあと、tキーをおして「run」とチャットににゅうりょくしてプログラムをうごかしてみよう！

```ghost
player.onChat("run", function () {
    agent.place(FORWARD)
})
```

```template
player.onChat("run", function () {})

```