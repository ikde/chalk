---
layout: post
title: "APlayer 测试"
description: "例子来自 http://aplayer.js.org/"
tags: [music, aplayer]
---

### APlayer 播放效果
<div markdown="0">
<div id="player1" class="aplayer"></div>
<script>
var ap1 = new APlayer({
    element: document.getElementById('player1'),
    narrow: false,
    autoplay: false,
    showlrc: false,
    mutex: true,
    theme: '#ad7a86',
    mode: 'random',
    music: [
        {
            title: 'あっちゅ～ま青春!',
            author: '七森中☆ごらく部',
            url: 'https://ikdenet.duapp.com/static/あっちゅ～ま青春!.mp3',
            pic: 'https://ikdenet.duapp.com/static/あっちゅ～ま青春!.jpg'
        },
        {
            title: 'secret base~君がくれたもの~',
            author: '茅野愛衣',
            url: 'https://ikdenet.duapp.com/static/secret base~.mp3',
            pic: 'https://ikdenet.duapp.com/static/secret base~.jpg'
        },
        {
            title: '回レ！雪月花',
            author: '小倉唯',
            url: 'https://ikdenet.duapp.com/static/回レ！雪月花.mp3',
            pic: 'https://ikdenet.duapp.com/static/回レ！雪月花.jpg'
        }
    ]
});
</script>
</div>
<p></p><p></p>
### html 代码
{% highlight html %}
<div id="player1" class="aplayer"></div>
{% endhighlight %}

### javascript 代码
{% highlight javascript %}
var ap1 = new APlayer({
    element: document.getElementById('player1'),
    narrow: false,
    autoplay: false,
    showlrc: false,
    mutex: true,
    theme: '#ad7a86',
    mode: 'random',
    music: [
        {
            title: 'あっちゅ～ま青春!',
            author: '七森中☆ごらく部',
            url: 'https://ikdenet.duapp.com/static/あっちゅ～ま青春!.mp3',
            pic: 'https://ikdenet.duapp.com/static/あっちゅ～ま青春!.jpg'
        },
        {
            title: 'secret base~君がくれたもの~',
            author: '茅野愛衣',
            url: 'https://ikdenet.duapp.com/static/secret base~.mp3',
            pic: 'https://ikdenet.duapp.com/static/secret base~.jpg'
        },
        {
            title: '回レ！雪月花',
            author: '小倉唯',
            url: 'https://ikdenet.duapp.com/static/回レ！雪月花.mp3',
            pic: 'https://ikdenet.duapp.com/static/回レ！雪月花.jpg'
        }
    ]
});
{% endhighlight %}
