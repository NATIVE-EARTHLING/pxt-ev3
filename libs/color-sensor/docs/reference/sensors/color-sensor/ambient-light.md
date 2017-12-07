# Ambient Light

```blocks
loops.forever(function () {
    if (sensors.color1.ambientLight() > 20) {
        brick.setStatusLight(LightsPattern.Green)
    } else {
        brick.setStatusLight(LightsPattern.Orange)
    }
})
```