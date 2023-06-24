### @hideIteration true
# TechkidsCAMP

## ここからさきは、じぶんでプログラムをつくってみよう！
わからないことがあったらメンターさんをよんでね！

```ghost
player.onChat("run", function () {
    for (let index = 0; index < 2; index++) {
        for (let index = 0; index < 4; index++) {
            agent.destroy(FORWARD)
            agent.turn(RIGHT_TURN)
            agent.place(FORWARD)
        }
        agent.move(UP, 1)
    }
})

```

```template
player.onChat("run", function () {})

```