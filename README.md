emoji
=====

show emoji characters

## Requirements
     Python 2.*
     Emoji enabled terminal.


## How to install

```
  wget https://github.com/takekawa/emoji/raw/master/emoji
  chmod 0755 emoji
```

## Examples

you can show help.
 
```
 $ ./emoji -h  

     Usage: emoji [Options] [Message ...]
     Options:
        -h --help
           Print this message
        -l --list 
           Print all emoji-characters with the name 
        -a --all 
           Print all emoji-characters without the name 
```

You can show sushi emoji.
```
 $ ./emoji sushi 
 🍣
```

You can find name using grep
```
 $ ./emoji -l | grep clock
 alarm_clock	⏰
 arrows_clockwise	🔃
 arrows_counterclockwise	🔄
 clock1	🕐
 clock10	🕙
 clock1030	🕥
 clock11	🕚
 clock1130	🕦
 clock12	🕛
 clock1230	🕧
 clock130	🕜
 clock2	🕑
 clock230	🕝
 clock3	🕒
 clock330	🕞
 clock4	🕓
 clock430	🕟
 clock5	🕔
 clock530	🕠
 clock6	🕕
 clock630	🕡
 clock7	🕖
 clock730	🕢
 clock8	🕗
 clock830	🕣
 clock9	🕘
 clock930	🕤
```

You can also know emoji name using emoji
```
 $ ./emoji -l | grep 🎻
 violin	🎻
```

You can also use with [echo-sd](https://github.com/fumiyas/home-commands/blob/master/echo-sd)


```
$ ./echo-sd "突然の$(./emoji sushi)"
＿人人人人人人＿
＞　突然の🍣　＜
￣Y^Y^Y^Y^Y^Y^￣
```

