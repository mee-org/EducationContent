### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

### @hideIteration true 
### @flyoutOnly 1
### @explicitHints 1


# Program the Agent to move along the turtle tracks!

## Step 1
使用 ``||agent: agent move forward||`` 代码块让代理沿着海龟轨迹移动到大门处。完成后，别忘了在Minecraft中按下**Play**按钮运行你的代码。
```ghost
player.onChat("tracks", function () {
    agent.move(FORWARD, 1)
    agent.turn(LEFT_TURN)
})
for (let index = 0; index < 4; index++) {
    	
 }
``` 
