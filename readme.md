## 生日快乐

> <b>修改config.js的配置就可以为您心爱的人做一个超具创意的网页生日快乐呀,喜欢的话fork or star一下呗~</b>

<img src="https://github.com/AJLoveChina/loveBalloon/blob/master/static/github-star.png" />

## TODO
* [x] 每行祝福文字可以配一张图片
* [ ] 配图支持旋转

### config.js 说明
> 温馨提示: 每句话丶每个图片地址丶每个按钮文字的那一行，最后都要以**英文逗号**结尾哦！
```text
var config = {
    // 句子的长度可以任意， 你可以写十句话， 二十句话都可以
    // 每句话尽量不要超过15个字,不然展示效果可能不太好
    texts: [
       
    ],
    /**
     * imgs 可以不填, 但是如果要填写的话必须遵循下面的格式
     * "对应上面的文字, 要完全一样" : "图片地址, 可以把图片放在imgs文件夹中"
     * 例如
     * "心爱的小可爱": "./imgs/xiaokeai.jpg"
     *
     * 如果不要图片的话, 直接在每行开头写两个斜杠注释即可, 例如下面的 "今天是你的生日" 的图片就不会展示了:)
     * Tip: 图片最好用正方形or接近正方形, 看起来效果更好
     */
    imgs: {
       
    },
    // 按钮文字描述, 以下是默认的按钮文字，英文的，您可以改成你喜欢的文字
    desc: {
        turn_on: "start",
        play: "music",
        bannar_coming: "bannar?",
        balloons_flying: "balloons?",
        cake_fadein: "cake?",
        light_candle: "candle?",
        wish_message: "生日快乐",
        }
