# mob_cow
Cow mob for Minetest

(c) 2018 AspireMint & 2021 Poikilos [CC BY-SA 3.0](http://creativecommons.org/licenses/by-sa/3.0/)


## Texture

Naming: `[mob]-[texture_size]-[color]-[type]-[show/hide part].[ext]`
- show/hide part:
  - h - horns size (0,1,2)
  - b - bell (0/1)
  - u - udders (0/1)


## Animations

- lying 1: 4 - 129
- lying 2: 132 - 256

- standing 1: 260 - 384
- standing 2: 387 - 512
- standing 3: 517 - 643 (eating)

- walking: 648 - 667
- running: 670 - 679

- attack 1: 682 - 687
- attack 2: 689 - 694
- attack 3: 697 - 702

```Lua
    animation = {
        speed_normal = 15,
        stand_start = 387,
        stand_end = 512,
        stand_speed = 15,
        walk_start = 648,
        walk_end = 667,
        walk_speed = 15,
        run_start = 670,
        run_end = 679,
        run_speed = 15,
        punch_start = 682,
        punch_end = 687,
        punch_speed = 15,
        punch2_start = 689,
        punch2_end = 694,
        punch2_speed = 15,
        die_start = 1,
        die_end = 2,
        die_speed = 2, -- 2fps since only 2 frames
        die_loop = false,
        die_rotate = 10,
    }
```

## Static positions

- standing: 1
- lying: 2


Preview:
![Image Cow mob](https://raw.githubusercontent.com/AspireMint/mob_cow/master/preview.png)
