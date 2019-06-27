```
var_m      - map
var_a      - system
var_a[0]      - time constants
var_a[0][0]      - delta time
var_a[0][1]      - elapsed
var_a[0][2]      - 1000/fps = tick interval
var_l      - input buffer (>V<^ABKd)
var_l[0]      - →
var_l[1]      - ↓
var_l[2]      - ←
var_l[3]      - ↑
var_l[4]      - A
var_l[5]      - B
var_l[6]      - K=Konami code progress
var_l[7]      - d=direction to delta mapping (0 to `[1,0]`, 1 to `[1,1]`, etc)
var_l[7][0]      - → [1,0]
var_l[7][1]      - ↘ [1,1]
var_l[7][2]      - ↓ [0,1]
var_l[7][3]      - ↙ [-1,1]
var_l[7][4]      - ← [-1,0]
var_l[7][5]      - ↖ [-1,-1]
var_l[7][6]      - ↑ [0,-1]
var_l[7][7]      - ↗ [1, -1]
var_l[8]      - hand graphics
var_l[8][0]      - →
var_l[8][1]      - ↘
var_l[8][2]      - ↓
var_l[8][3]      - ↙
var_l[8][4]      - ←
var_l[8][5]      - ↖
var_l[8][6]      - ↑
var_l[8][7]      - ↗
var_b      - entity (player, monster etc)
var_b[0]      - config
var_b[0][0]      - player icon
var_b[0][1]      - cooldown config list
var_b[0][1][0]      - move cooldown
var_b[0][1][1]      - rotate cooldown
var_b[1]      - transform
var_b[1][0]      - x
var_b[1][1]      - y
var_b[1][2]      - rotation-8
var_b[1][3]      - width
var_b[1][4]      - height
var_b[2]      - state
var_b[2][0]      - current cooldown
var_b[2][1]      - enum action mode/ status effect (normal, strafe, channel, stun, guard)
var_b[2][2]      - (hp, maxhp)
var_b[2][2][0]      - hp
var_b[2][2][1]      - maxhp
var_b[3]      - player / monster specific variables
```
