```
entity{
  _template:t="level"
  level__blk:t="%ugm0/levels/battle_of_moscow_volokolamsk_countryside_winter.blk"
  level__timeRange:p2=5, 19.2

  "level__weatherChoice:object"{
    "content/common/gamedata/weather/weather_clear.blk":r=1
  }

  "level__timeVec:array"{
    level__timeVec:r=9
  }
}
```

注意会被其他entity覆盖

```
entity{
  _template:t="dynamic_environment"
  dynamic_environment__weather_datablock:t="content/common/gamedata/weather/weather_light_clouds.blk"
  dynamic_environment__time:r=18.5
  dynamic_environment__skies_seed:i=1
}
```
