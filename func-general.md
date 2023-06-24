### @hideIteration true
# TechkidsCAMP

## ここからさきは、じぶんでプログラムをつくってみよう！
わからないことがあったらメンターさんをよんでね！

```ghost
player.onChat("run", function (num1) {
    mae(num1)
    for (let index = 0; index < 2; index++) {
        agent.move(UP, 1)
    }
})
function mae (数値: number) {
    agent.move(数値, 1)
    agent.place(FORWARD)
}

```

```template
player.onChat("run", function () {})

```