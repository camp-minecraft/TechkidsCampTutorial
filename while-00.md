### @hideIteration true
# TechkidsCAMP

## エージェントをうごかしてみよう！

エージェントをみずいろのブロックのばしょまでいどうさせよう！
スタートのとなりのボタンをおせばリセットできるよ！

```ghost
player.onChat("run", function () {
    for (let index = 0; index < 8; index++) {
        agent.move(FORWARD, 1)
        agent.move(LEFT, 1)
    }
})

```

```template
player.onChat("run", function () {})
```