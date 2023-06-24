### @hideIteration true
# TechkidsCAMP

## エージェントをうごかしてみよう！

くりかえしをつかってエージェントにブロックをおいてもらおう！
スタートのとなりのボタンをおせばリセットできるよ！

```ghost
player.onChat("run", function () {
    for (let index = 0; index < 10; index++) {
        agent.move(FORWARD, 1)
        agent.place(DOWN)
    }
})

```

```template
player.onChat("run", function () {})
```