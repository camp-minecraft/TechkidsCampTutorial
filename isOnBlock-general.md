### @hideIteration true
# TechkidsCAMP

## ここからさきは、じぶんでプログラムをつくってみよう！
わからないことがあったらメンターさんをよんでね！

```ghost
player.onChat("run", function () {
    for (let index = 0; index < 4; index++) {
        agent.move(FORWARD, 1)
        if (!(agent.detect(AgentDetection.Block, FORWARD))) {
            agent.place(FORWARD)
        }
        agent.turn(RIGHT_TURN)
    }
})


```

```template
player.onChat("run", function () {})

```