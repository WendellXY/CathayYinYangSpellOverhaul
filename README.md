# Yin Yang Spell Overhaul

> 阴阳法术大修

## 相关表格 Related Tables

```text
[1] unit_special_abilities_tables
[2] special_ability_phases_tables
[3] special_ability_phase_stat_effects_tables
[4] battle_vortexs_tables
[5] special_ability_to_special_ability_phase_junctions_tables
[6] unit_abilities_to_additional_ui_effects_juncs_tables
```

## 修改 Modification

> 所有阴阳法术都可以在龙形态使用
> All Yin-Yang Spell could be used in dragon shape

### 阴之力 Power Of Yin

`wh3_main_lore_passive_power_of_yin`

* 作用范围 Effect Range: 55 -> 200 [1]

### 阳之强 Strength Of Yang

`wh3_main_lore_passive_strength_of_yang`

* 作用范围 Effect Range: 55 -> 200 [1]

### 墨衣诀 Cloak Of Jet

`wh3_main_spell_yin_cloak_of_jet`

* 魔法之风消耗 Mana Cost: 4 -> 2 [1]
* (过载) 作用范围 (Overload) Effect Range: 35 [1]

### 退箭诀 Missile Mirror

`wh3_main_spell_yin_missile_mirror`

* 魔法之风消耗 Mana Cost: 10 -> 6 [1]
* 持续时间 Active Time: 18 -> 22 [1] [2]
* (过载) 魔法之风消耗 (Overload) Mana Cost: 15 -> 10 [1]
* (过载) 持续时间 (Overload) Active Time: 36 -> 44 [1] [2]
* (过载) 作用范围 (Overload) Effect Range: 35 [1]

### 和风诀 Blossom Wind

`wh3_main_spell_yin_blossom_wind`

* 魔法之风消耗 Mana Cost: 9 -> 8 [1]
* (过载) 魔法之风消耗 (Overload) Mana Cost: 14 -> 12 [1]
* 基础伤害 Base Damage: 0 -> 4 [4]
* (过载) 基础伤害 Base Damage: 0 -> 6 [4]

### 夜鸮决 Talons of Night

`wh3_main_spell_yin_talons_of_night`

* (过载) 魔法之风消耗 (Overload) Mana Cost: 21 -> 20 [1]

### 先魂决 Ancestral Warriors

`wh3_main_spell_yin_ancestral_warriors`

* 魔法之风消耗 Mana Cost: 16 -> 10 [1]
* (过载) 魔法之风消耗 (Overload) Mana Cost: 22 -> 12 [1]

### 翠御诀 Jade Shield

`wh3_main_spell_yang_jade_shield`

* (过载) 魔法之风消耗 (Overload) Mana Cost: 6 -> 12 [1]
* (过载) 作用范围 (Overload) Effect Range: 35 [1]

### 龙息诀 Dragons Breath

`wh3_main_spell_yang_dragons_breath`

* (过载) 伤害 (Overload) Base Damage: 56 -> 36 [4]
* (过载) 破甲伤害 (Overload) AP Damage: 0 -> 6 [4]

### 风火诀 Wall Of Wind & Fire

`wh3_main_spell_yang_wall_of_wind_and_fire`

* (过载) 破甲伤害 (Overload) Base Damage: 6 -> 12 [4]

### 坚岩决 Stone Ground Stance

`wh3_main_spell_yang_stone_ground_stance`

* 魔法之风消耗 Mana Cost: 8 -> 6 [1]
* (过载) 魔法之风消耗 (Overload) Mana Cost: 12 -> 10 [2]
* (过载) 作用范围 (Overload) Effect Range: 55 -> 70 [1]
* (过载) 质量 (Overload) Mass: +100% -> +200% [3]

### 天地诀 Might of Heaven & Earth

`wh3_main_spell_yang_might_of_heaven_and_earth`

* 魔法之风消耗 Mana Cost: 11 -> 10 [1]
* (过载) 魔法之风消耗 (Overload) Mana Cost: 20 -> 14 [1]

### 龙星诀 Constellation of the Dragon

`wh3_main_spell_yang_constellation_of_the_dragon`

* 魔法之风消耗 Mana Cost: 18 -> 14 [1]
* (过载) 魔法之风消耗 (Overload) Mana Cost: 24 -> 20 [2]
