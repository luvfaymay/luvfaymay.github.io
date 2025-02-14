---
layout: landing
title: FayMay Profiles
description: ""
image: assets/images/banner10.jpeg
nav-menu: true
---

<div id="main">
    <section id="one">
        <div class="inner">
            <header class="major">
                <h2>{% t profile.header %}</h2>
            </header>
            <p>{% t profile.translation_status %}</p>
            <p>{% t profile.welcome_message %}</p>
            <ol>
                {% for request in site.translations[site.lang].profile.fan_requests %}
                    <li>{{ request }}</li>
                {% endfor %}
            </ol>
        </div>
    </section>
    <section id="two">
		<div class="image">
            <img src="{{ 'assets/images/fmprofileimg.jpeg' | relative_url }}" alt="FayMay Profile" data-position="top center">
        </div>
	</section>
    <section id="three" class="spotlights">
        <section>
            <div class="image">
                <img src="{{ 'assets/images/fayofficial.jpeg' | relative_url }}" alt="Fay" data-position="top center">
            </div>
            <div class="content">
                <div class="inner">
                    <header class="major">
                        <h2 style="color: #87CEFA;">{% t global.fay_name %}</h2>
                    </header>
                    <p>
                        {% for item in site.translations[site.lang].profile.fay %}
                            <strong>{{ item[0] | capitalize | replace: "_", " " }}:</strong> {{ item[1] }}<br>
                        {% endfor %}
                    </p>
                </div>
            </div>
        </section>
        <section>
            <div class="image">
                <img src="{{ 'assets/images/mayofficial.jpeg' | relative_url }}" alt="May" data-position="top center">
            </div>
            <div class="content">
                <div class="inner">
                    <header class="major">
                        <h2 style="color: #FF1493;">{% t global.may_name %}</h2>
                    </header>
                    <p>
                        {% for item in site.translations[site.lang].profile.may %}
                            <strong>{{ item[0] | capitalize | replace: "_", " " }}:</strong> {{ item[1] }}<br>
                        {% endfor %}
                    </p>
                </div>
            </div>
        </section>
        <section>
            <div class="image">
                <img src="{{ 'assets/images/allmagazine.jpeg' | relative_url }}" alt="Fay" data-position="top center">
            </div>
            <div class="content">
                <div class="inner">
                    <header class="major">
                        <h3>{{ site.translations[site.lang].profile.allmag }}</h3>
                    </header>
                    <p>{{ site.translations[site.lang].profile.allmag_description }}</p>
                    <div class="twitter-embed">
                        <blockquote class="twitter-tweet" data-theme="dark"><p lang="en" dir="ltr">“While Fay and I seem different, we share some similarities. When Fay is around close friends, she talks a lot, just like I do. We’re both pretty laid-back and tend to talk endlessly”.<br><br>May&#39;s whole interview is here! 🥕<a href="https://twitter.com/hashtag/FayMay?src=hash&amp;ref_src=twsrc%5Etfw">#FayMay</a> <a href="https://twitter.com/hashtag/maywyda?src=hash&amp;ref_src=twsrc%5Etfw">#maywyda</a> <a href="https://t.co/nHeplYR1Wi">pic.twitter.com/nHeplYR1Wi</a></p>&mdash; FAYMAY Interfan Squad (@faymayIFS) <a href="https://twitter.com/faymayIFS/status/1876321958134210881?ref_src=twsrc%5Etfw">January 6, 2025</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
                    </div>
                    <div class="twitter-embed">
                        <blockquote class="twitter-tweet" data-theme="dark"><p lang="en" dir="ltr">“I met May on the very first day, and we’ve been paired for auditions all the way through to the final round. I was impressed by how deeply she could express emotions through her eyes. I never thought we’d become this close.”<br><br>Fay&#39;s whole interview is here! 🧙‍♂️<a href="https://twitter.com/hashtag/FayMay?src=hash&amp;ref_src=twsrc%5Etfw">#FayMay</a> <a href="https://twitter.com/hashtag/fay_riezz?src=hash&amp;ref_src=twsrc%5Etfw">#fay_riezz</a> <a href="https://t.co/IBl57EQsG1">pic.twitter.com/IBl57EQsG1</a></p>&mdash; FAYMAY Interfan Squad (@faymayIFS) <a href="https://twitter.com/faymayIFS/status/1876291127353172093?ref_src=twsrc%5Etfw">January 6, 2025</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
                    </div>
                </div>
            </div>
        </section>
        <section>
            <div class="image">
                <img src="{{ 'assets/images/trend.jpeg' | relative_url }}" alt="Fay" data-position="top center">
            </div>
            <div class="content">
                <div class="inner">
                    <header class="major">
                        <h3>{{ site.translations[site.lang].profile.trend }}</h3>
                    </header>
                    <p>{{ site.translations[site.lang].profile.trend_description }}</p>
                    <div class="twitter-embed">
                        <blockquote class="twitter-tweet" data-theme="dark"><p lang="en" dir="ltr">We are minutes away from our trend and we would like to remind everyone how we should do it! 💞<a href="https://twitter.com/hashtag/%E0%B9%80%E0%B8%9F%E0%B9%80%E0%B8%A1%E0%B8%A9%E0%B9%8C?src=hash&amp;ref_src=twsrc%5Etfw">#เฟเมษ์</a> <a href="https://twitter.com/hashtag/FayMay?src=hash&amp;ref_src=twsrc%5Etfw">#FayMay</a><a href="https://t.co/dBzSGgDxS9">pic.twitter.com/dBzSGgDxS9</a></p>&mdash; FAYMAY Interfan Squad (@faymayIFS) <a href="https://twitter.com/faymayIFS/status/1854477600133169250?ref_src=twsrc%5Etfw">November 7, 2024</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
                    </div>
                </div>
            </div>
        </section>
        <section>
            <div class="image">
                <img src="{{ 'assets/images/youtube.jpeg' | relative_url }}" alt="Fay" data-position="top center">
            </div>
            <div class="content">
                <div class="inner">
                    <header class="major">
                        <h3>{{ site.translations[site.lang].profile.youtube }}</h3>
                    </header>
                    <p>{{ site.translations[site.lang].profile.youtube_description }}</p>
                    <div class="twitter-embed">
                        <blockquote class="twitter-tweet" data-theme="dark"><p lang="en" dir="ltr">Alright, guys! This info is Fay-tally important (get it? 😉) Here’s the tea on how YouTube views work, so grab a cuppa and get ready to boost those numbers sky-high! 🚀This here is the secret weapon for the &quot;Somewhere Somehow&quot; pilot and every video after! 🎬🗻<a href="https://twitter.com/hashtag/SWSHGL?src=hash&amp;ref_src=twsrc%5Etfw">#SWSHGL</a> <a href="https://twitter.com/hashtag/FayMay?src=hash&amp;ref_src=twsrc%5Etfw">#FayMay</a> <a href="https://t.co/o0TykonDrg">pic.twitter.com/o0TykonDrg</a></p>&mdash; FAYMAY Interfan Squad (@faymayIFS) <a href="https://twitter.com/faymayIFS/status/1882784676299071978?ref_src=twsrc%5Etfw">January 24, 2025</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
                    </div>
                    <div class="twitter-embed">
                        <blockquote class="twitter-tweet" data-conversation="none" data-theme="dark"><p lang="en" dir="ltr">We’ll need to do two things:<br>1. Follow YouTube guidelines to avoid being flagged as invalid views.<br><br>2. Shift focus from view count to audience reach (recommendations). Our goal should be to get the pilot recommended to as many people as possible, which will drive organic views.…</p>&mdash; wint (@wintwho) <a href="https://twitter.com/wintwho/status/1881836529515143605?ref_src=twsrc%5Etfw">January 21, 2025</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
                    </div>
                    <div class="twitter-embed">
                        <blockquote class="twitter-tweet" data-conversation="none" data-theme="dark"><p lang="en" dir="ltr">1. Follow YouTube guidelines to avoid being flagged as invalid views. <a href="https://t.co/l4mfMmszRb">pic.twitter.com/l4mfMmszRb</a></p>&mdash; wint (@wintwho) <a href="https://twitter.com/wintwho/status/1881836532954513755?ref_src=twsrc%5Etfw">January 21, 2025</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
                    </div>
                    <div class="twitter-embed">
                        <blockquote class="twitter-tweet" data-conversation="none" data-theme="dark"><p lang="en" dir="ltr">2. Focus on getting the video recommended. <a href="https://t.co/eFYpHEJ4xd">pic.twitter.com/eFYpHEJ4xd</a></p>&mdash; wint (@wintwho) <a href="https://twitter.com/wintwho/status/1881836537039696292?ref_src=twsrc%5Etfw">January 21, 2025</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
                    </div>
                    <div class="twitter-embed">
                        <blockquote class="twitter-tweet" data-theme="dark"><p lang="th" dir="ltr">สวัสดีทุกคน! <br>นี่คือข้อมูลสำคัญเกี่ยวกับวิธีที่ YouTube นับยอดการรับชม การเข้าใจเรื่องนี้จะช่วยให้คุณสนับสนุนตอนนำร่อง &quot;Somewhere Somehow&quot; และวิดีโอทุกชิ้นในอนาคตได้อย่างมีประสิทธิภาพ มาร่วมมือกันเพื่อเพิ่มยอดการรับชมให้ได้ผลดี! 🗻🚀<a href="https://twitter.com/hashtag/%E0%B8%A3%E0%B8%B1%E0%B8%81%E0%B8%9B%E0%B8%B2%E0%B8%81%E0%B9%81%E0%B8%82%E0%B9%87%E0%B8%87?src=hash&amp;ref_src=twsrc%5Etfw">#รักปากแข็ง</a> <a href="https://twitter.com/hashtag/SWSHGL?src=hash&amp;ref_src=twsrc%5Etfw">#SWSHGL</a><a href="https://twitter.com/hashtag/FayMay?src=hash&amp;ref_src=twsrc%5Etfw">#FayMay</a> <a href="https://twitter.com/FayMayOfficial?ref_src=twsrc%5Etfw">@FayMayOfficial</a> <a href="https://t.co/36Evd0biYZ">pic.twitter.com/36Evd0biYZ</a></p>&mdash; FAYMAY Interfan Squad (@faymayIFS) <a href="https://twitter.com/faymayIFS/status/1883379340693651942?ref_src=twsrc%5Etfw">January 26, 2025</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
                    </div>
                    <div class="twitter-embed">
                        <blockquote class="twitter-tweet" data-conversation="none" data-theme="dark"><p lang="th" dir="ltr">Thai language Translation: <br>ข้อเท็จจริงที่ยืนยันแล้ว (ตรวจสอบโดยเอกสารทางการของ YouTube)<br>1. อะไรที่นับเป็นการรับชม (View)?<br>• การรับชมจะนับเมื่อผู้ใช้เริ่มเล่นวิดีโอโดยตั้งใจ<br>• YouTube ไม่เปิดเผยระยะเวลาที่แน่นอนสำหรับการนับการรับชม<br>•…</p>&mdash; wint (@wintwho) <a href="https://twitter.com/wintwho/status/1882345882773082539?ref_src=twsrc%5Etfw">January 23, 2025</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
                    </div>
                    <div class="twitter-embed">
                        <blockquote class="twitter-tweet" data-theme="dark"><p lang="zh" dir="ltr">大家好！<br>这里有关于YouTube观看次数是如何计算的重要信息。了解这些能够帮助你支持《Somewhere Somehow》的试播集以及之后的所有视频🗻<br>让我们一起努力有效提升这些数字吧！🚀<a href="https://twitter.com/hashtag/SWSHGL?src=hash&amp;ref_src=twsrc%5Etfw">#SWSHGL</a> <a href="https://twitter.com/hashtag/FayMay?src=hash&amp;ref_src=twsrc%5Etfw">#FayMay</a> <a href="https://twitter.com/FayMay_CN_Honey?ref_src=twsrc%5Etfw">@FayMay_CN_Honey</a> <a href="https://t.co/NCWM2pEq4l">pic.twitter.com/NCWM2pEq4l</a></p>&mdash; FAYMAY Interfan Squad (@faymayIFS) <a href="https://twitter.com/faymayIFS/status/1883364242776277203?ref_src=twsrc%5Etfw">January 26, 2025</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
                    </div>
                    <div class="twitter-embed">
                        <blockquote class="twitter-tweet" data-conversation="none" data-theme="dark"><p lang="zh" dir="ltr">Chinese Language Translation: <br>已确认的事实（经 YouTube 官方文档验证）<br>1.什么算作观看次数？<br>o当用户主动播放视频时，即计为一次观看。<br>oYouTube 未公开要求的具体观看时长。<br>o在高流量期间，观看次数可能会暂时被冻结以进行验证。<br><br>2.观众保留率的质量<br>o观看时长和观众保留率直接影响视频表现。…</p>&mdash; wint (@wintwho) <a href="https://twitter.com/wintwho/status/1882347499173920910?ref_src=twsrc%5Etfw">January 23, 2025</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
                    </div>
                    <div class="twitter-embed">
                        <blockquote class="twitter-tweet" data-theme="dark"><p lang="ja" dir="ltr">みなさん、こんにちは！<br>YouTubeの再生回数がどうカウントされるのか、気になるよね？知っておくと「Somewhere Somehow」のパイロット版も、これからの動画ももっとバッチリ応援できるよ！🗻<br>みんなで一緒に再生回数をどんどん伸ばしていこう！🚀<a href="https://twitter.com/hashtag/SWSHGL?src=hash&amp;ref_src=twsrc%5Etfw">#SWSHGL</a> <a href="https://twitter.com/hashtag/FayMay?src=hash&amp;ref_src=twsrc%5Etfw">#FayMay</a> <a href="https://twitter.com/FayMayJapan?ref_src=twsrc%5Etfw">@FayMayJapan</a> <a href="https://t.co/7xv1ALTs2F">pic.twitter.com/7xv1ALTs2F</a></p>&mdash; FAYMAY Interfan Squad (@faymayIFS) <a href="https://twitter.com/faymayIFS/status/1883349147518144789?ref_src=twsrc%5Etfw">January 26, 2025</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
                    </div>
                    <div class="twitter-embed">
                        <blockquote class="twitter-tweet" data-conversation="none" data-theme="dark"><p lang="ja" dir="ltr">Japanese Language Translation: <br>確認済みの事実（YouTube公式ドキュメントによる検証済み）<br>1.再生回数にカウントされる条件<br>oユーザーが意図的に動画を再生した場合、再生回数としてカウントされる。<br>oYouTubeは、必要な正確な再生時間を公開していない。…</p>&mdash; wint (@wintwho) <a href="https://twitter.com/wintwho/status/1882348533946450399?ref_src=twsrc%5Etfw">January 23, 2025</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
                    </div>
                </div>
            </div>
        </section>
    </section>
</div>