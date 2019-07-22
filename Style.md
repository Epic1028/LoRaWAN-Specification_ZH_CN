

## 文档格式

文档格式主要参考 [中文文案排版指北](https://github.com/sparanoid/chinese-copywriting-guidelines)。

- 中文中混杂英文词语和数字时，需要补充空格。
  // 这点没严格执行，有章节更新的话，会逐步完善这一块。
  > "本文档描述了 LoRaWAN 网络协议" // 前后都有汉字时在前后补充空格。
  > "LoRaWAN 网络通常采用星型拓扑结构" // 句首已经有明显分割，可以不补充空格。
  > “终端设备又称为 motes。” // 句末已经有明显分割，可以不补充空格。
  > “使用速率自适应(ADR)机制” // 分隔符号出现的周围，已经有明显分割，可以不补充空格。
  
- 非协议内容的个人注解插入，使用代码块样式进行引用，和普通文本做区别。

```
twowinter注： 
发射占空比定义：发射时长占总时长的比例。按照无线电规定，每个设备不能持续占用信道，通过最大发射占空比来限制终端占用信道的时间。
例如某终端发送某数据时的发射时长为 1s，当地无线电规定中的最大发射占空比为1%，则该终端需要等候 99s 才能进行下一次的发射。
```

- 

## 术语翻译约定

maximum transmit duty cycle | 最大发射占空比
dwell time | 空中停留时间