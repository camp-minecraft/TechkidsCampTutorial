### @hideIteration true
# TechkidsCAMP

## エージェントをつかって、ブロックをせっちしよう！

ブロックをつかってエージェントにブロックをせっちしてもらおう！

```ghost
player.onChat("run", function () {
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.turn(LEFT_TURN)
})
```

```template
player.onChat("run", function () {})
```
