### @hideIteration true
# TechkidsCAMP

## エージェントをうごかしてみよう！

![](https://raw.githubusercontent.com/camp-minecraft/TechkidsCampTutorial/master/images/move-tutorial.gif)
エージェントをみずいろのブロックのばしょまでいどうさせよう！

![](https://raw.githubusercontent.com/camp-minecraft/TechkidsCampTutorial/master/images/move-reset.gif)
スタートのとなりのボタンをおせばリセットできるよ！

```ghost
player.onChat("run", function () {
    agent.move(FORWARD, 1)
})
```

```template
player.onChat("run", function () {})
```