# Vocaloid-singer-name-in-VSQX
Vocaloid歌手信息的对应表。vocaloid singer's name in vsqx(vocaloid3、4)。

记录了常见的大部分歌手，也欢迎提交 Issue、Push补充。

## 一、歌手信息
用于根据 `vsqx` 读取歌手信息（名字）。

### 中文组 + 日文组

```
[
    {
        "洛天依": [
            "Luotianyi_CHN_Meng", 
            "Luotianyi_CHN_Ning", 
            "Tianyi_CHN"
        ]
    }, 
    {
        "言和": [
            "YANHE"
        ]
    }
    .........
]
```


## 二、歌手重复出现次数统计

```
{
    repeat_num: [
        {
            singer: 'YANHE',
            repeat_num: 102
        },
        {
            singer: 'YuezhenglingV3',
            repeat_num: 82
        },
        {
            singer: 'Luotianyi_CHN_Meng',
            repeat_num: 60
        }
        ..........
    ]
}
```



## 三、附录：如何查看伴奏信息
vsqx文件最后有个 `stTrack` 标签。

 <filePath><![CDATA[【洛天依】XXXXX.wav]]></filePath>

中括号里面的就是。
