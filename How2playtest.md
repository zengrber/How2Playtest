<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>How2playtest</title>
  <link rel="stylesheet" href="https://stackedit.io/style.css" />
</head>

<body class="stackedit">
  <div class="stackedit__html"><h1 id="如何测图（playtest）">如何测图（Playtest）</h1>
<h2 id="前言与约定">0 前言与约定</h2>
<p>我的世界赛履历匮乏。在应聘mwc之前仅不完整地参与了THMC4的测图工作。如此仍能成功入选MWC 2025，也许说明我拥有一定的测图理解。鉴于我已经23岁，不能保证长期具有稳定且足够高的水平，加之目前国内似乎没有专门研究playtest的人员，谱师或选手兼任的情况居多，故在此提出一些个人理解或观点，希望能够给民间各比赛有意向playtest的选手以及想要加入世界赛团队的选手一些参考。我技术有限，文化程度有限，措辞不当在所难免，恳请各位海涵。</p>
<p>本系列主要面向OSU!Mania 4k赛事的纯粹playtester，即写图经验基本可以忽略不计的玩家。又能写又能打的玩家同样欢迎收看，但无需真正参考本系列内容。都会写图了，还用得着看我一个不会写图的如何评价吗？其他游戏如Malody的测图工作也有共通之处，可以用作参考，但具体术语与涉及到的数值可能会有所出入，请根据实际情况调节。</p>
<p>本系列中提到的所有准确率（Acc）相关数值全部为Score V2下的数值，并且可能会反复提到“随便打”“打得动”“打不动”等字眼。为尽量消除歧义，约定</p>
<ul>
<li>“随便打”为99.70% 准确率以上，具体数值依照自身黄彩来确定。一般来说没有特训过黄彩的选手SS一张图大概就是99.7% 990k左右的成绩，所以以此为界</li>
<li>“打得动”为98%以上，具体数值依据自身情况（如耐力，保combo能力等）确定，对于通常图池来说，98% 900k意味着能够正攻绝大部分排列，在非大后期难度下基本不会开糊，故以此为界</li>
<li>以下均为“打不动”范畴，尽管打不动也可能能够提出一些有效的建议，但打不动就是打不动，效力和可信度应当是低于打得动的玩家的测试结果的。</li>
</ul>
<h2 id="以mwc-4k为基准的图池结构与术语介绍">1 以MWC 4K为基准的图池结构与术语介绍</h2>
<p><strong>1.1 常用术语释义</strong></p>
<ul>
<li><strong>Map</strong>：中文简称“图”，OSU!社区对谱面的称呼。</li>
<li><strong>Mappool</strong>：图池。一个赛事某一轮的可选取谱面构成的集合，动名词mapppooling意为制作图池。</li>
<li><strong>Note</strong>：音符，谱面由若干note排列构成。</li>
<li><strong>RC</strong>：Rice，米。指按一下就可以的note。在比赛中指代以米为绝对主体，主要考察选手打米能力的图。</li>
<li><strong>LN</strong>：Long Note，面。指需要按住和松手的长note。在比赛中指以面为绝对主体，主要考察选手吃面能力的图。</li>
<li><strong>HB</strong>：Hybrid。指米面比例接近，难度构成综合的图。同时考察选手的米面能力。</li>
<li><strong>SV</strong>：英文说法不一，待考证。指带有流速变化的图，需要专门的训练以及谱面理解。MWC2025据传已不再包含SV。</li>
<li><strong>TB</strong>：Tiebreaker。不允许主动选择，仅在双方都差一分获胜的情况下强制选取，用于决出最终的胜负。</li>
<li><strong>胜者组/败者组(Losers)</strong>：双败赛制下输掉一轮比赛会从胜者组进入败者组，败者组再输掉一轮比赛将会被淘汰。</li>
<li><strong>Qualifier</strong>： 资格赛。报名选手较多的比赛会采用资格赛的形式筛选指定数量的玩家/团队进入正赛。一般来说包含从赛事前期到中后期的谱面，取玩家/团队在规定时间/次数内打出的最好成绩（具体成绩计算规则由主办方确定）。</li>
<li><strong>Ro<span class="katex--inline"><span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>x</mi></mrow><annotation encoding="application/x-tex">x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 0.43056em; vertical-align: 0em;"></span><span class="mord mathnormal">x</span></span></span></span></span></strong>：Round of <span class="katex--inline"><span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>x</mi></mrow><annotation encoding="application/x-tex">x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 0.43056em; vertical-align: 0em;"></span><span class="mord mathnormal">x</span></span></span></span></span>，<span class="katex--inline"><span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>x</mi></mrow><annotation encoding="application/x-tex">x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 0.43056em; vertical-align: 0em;"></span><span class="mord mathnormal">x</span></span></span></span></span>为正整数，指代比赛轮次。如Ro32即Round of 32，指胜者组32进16的及对应的败者组比赛。</li>
<li><strong>QF</strong>：Quarterfinals，胜者组8进4以及对应的败者组比赛。</li>
<li><strong>SF</strong>：Semifinals，胜者组4进2以及对应的败者组比赛。</li>
<li><strong>F</strong>：Finals，胜者组决赛及对应的败者组比赛。</li>
<li><strong>GF</strong>：Grand Finals，总决赛。双败赛制下最后会剩下唯一的胜者组以及败者组选手/团队，二者将进行总决赛决定最后的冠军。</li>
<li><strong>Bo<span class="katex--inline"><span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>x</mi></mrow><annotation encoding="application/x-tex">x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 0.43056em; vertical-align: 0em;"></span><span class="mord mathnormal">x</span></span></span></span></span></strong>：Best of <span class="katex--inline"><span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>x</mi></mrow><annotation encoding="application/x-tex">x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 0.43056em; vertical-align: 0em;"></span><span class="mord mathnormal">x</span></span></span></span></span>，<span class="katex--inline"><span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>x</mi></mrow><annotation encoding="application/x-tex">x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 0.43056em; vertical-align: 0em;"></span><span class="mord mathnormal">x</span></span></span></span></span>为正整数，指代胜负规则。此规则下先达到<span class="katex--inline"><span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>+</mo><mn>1</mn><mo stretchy="false">)</mo><mi mathvariant="normal">/</mi><mn>2</mn></mrow><annotation encoding="application/x-tex">(x+1)/2</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 1em; vertical-align: -0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right: 0.222222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right: 0.222222em;"></span></span><span class="base"><span class="strut" style="height: 1em; vertical-align: -0.25em;"></span><span class="mord">1</span><span class="mclose">)</span><span class="mord">/2</span></span></span></span></span>分的选手/团队获胜，如Bo13代表抢7，谁先拿到7分谁赢。</li>
<li><strong>Bracket Reset</strong>：双败赛制下为奖励胜者组（如若不奖励，则胜者组决赛意义将减小）设立的规则。败者组选手/团队需连续战胜胜者组团队两次才能取得总冠军，而胜者组选手/团队只需要获胜一次即为总冠军。此规则下如果第一次比赛败者组获胜，则需要清空双方比分重来一回，此过程成为Bracket Reset。</li>
<li><strong>WBD</strong>：Win by Default，因轮空或对手弃权导致直接胜利。</li>
</ul>
<p><strong>1.2 图池结构概览</strong><br>
MWC赛制中，bo<span class="katex--inline"><span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>x</mi></mrow><annotation encoding="application/x-tex">x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 0.43056em; vertical-align: 0em;"></span><span class="mord mathnormal">x</span></span></span></span></span>的图池包含<span class="katex--inline"><span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>x</mi><mo>+</mo><mn>4</mn></mrow><annotation encoding="application/x-tex">x+4</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 0.66666em; vertical-align: -0.08333em;"></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right: 0.222222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right: 0.222222em;"></span></span><span class="base"><span class="strut" style="height: 0.64444em; vertical-align: 0em;"></span><span class="mord">4</span></span></span></span></span>张图。如bo13的图池由17张图构成。具体结构取决于赛事团队，如知名赛事JHC显然不会包含ln和hb，但通常而言一个综合性赛事的构成的基准结构如下：</p>
<ul>
<li>bo9：5rc+2hb+3ln+2sv+tb</li>
<li>bo11：6rc+3hb+3ln+2sv+tb</li>
<li>bo13：7rc+3hb+4ln+2sv+tb</li>
</ul>
<p>资格赛图池数量无明确约定。如果一个赛事没有sv，可能会额外添加一张rc、一张ln或hb。</p>
<p><strong>1.3 图池结构详解</strong><br>
以MWC的图池构成为准，具体细节由赛事主办方决定。</p>
<ul>
<li>RC1：一般为乱键。</li>
<li>RC2：一般为高速的js。</li>
<li>RC3：一般为bpm相对低但耐力要求高的js/hs（早期轮次可能RC2和3会合并为一张切图，此时后面的序号自动递补）</li>
<li>RC4：一般为叠键，但有别于段位中的叠键，赛图叠主要的难度体现在卡手以及在中间混合非叠键排列，而高非密度与纵连。</li>
<li>RC5及以后：tech，原则上序号越大的rc越难以抓彩。</li>
<li>HB1：一般体现为切叠之中掺杂一些面和盾，比较规整。</li>
<li>HB2：一般体现为盾和锁手，稍微难抓彩一些，手速要求较高。</li>
<li>HB3：一般体现为wildcard。谱师放飞自我，排列奇伟瑰怪极难抓彩。</li>
<li>LN1：前期体现为放手，后期体现为timing hell，考察玩家协调性。</li>
<li>LN2：一般为LN density。高密度LN，通常以切乱反键为主。</li>
<li>LN3及以后：一般体现为wildcard。谱师放飞自我，排列奇伟瑰怪极难抓彩。</li>
<li>SV1：一般为Reading。需要的记忆量相对小，主要依靠读谱能力和反应力的sv。</li>
<li>SV2：一般为Memory。需要的记忆量大，有些部分甚至不可读，只能背下谱面。</li>
<li>TB：什么都有，综合难度要显著高于图池中的其他图。</li>
</ul>
<h2 id="基本素质">2 基本素质</h2>
<p><strong>2.1 测图人员的基本修养</strong><br>
作为测图人员，主要需要有自知之明以及一定赛图游玩量。需要对自己的技术特点以及不同状态下的发挥有相对客观的认知。另外需要一定的赛图积累，便于在需要的时候能够找到参照或举例说明自己的论点。</p>
<p><strong>2.2 什么水平能够承担测图的任务呢？</strong><br>
依据比赛难度而定。推荐至少打得动一场赛事绝大部分资格赛赛图的玩家考虑参与该比赛的测图工作。通常比赛每一轮的难度递增，如果到某一轮基本没有图打得动了，建议停止测试或表明自己实力有限，结论与成绩仅供参考。这不是半途而废，而是对谱师和选手都负责的表现。如果自身水平有明显偏科，可以依据具体的情况灵活调整，比如米测到gf，面测到sf这样。</p>
<p><strong>2.3 测试团队里有炒鸡高手，感觉自己啥也不是怎么办？</strong><br>
高手也不一定有时间把所有图都过一遍。而且对高手而言可能对早期的图池感知会稍弱，此时更多的意见总不是坏事。相信自己的价值，与团队一起为选手们呈现最好的比赛内容即可。</p>
<h2 id="自我评估">3 自我评估</h2>
<p><strong>3.1 自我评估的目的</strong><br>
<strong>3.2 自我评估的内容</strong><br>
<strong>3.3 自我评估的方法</strong></p>
<h2 id="测试流程">4 测试流程</h2>
<p><strong>4.1 自我评估</strong><br>
<strong>4.2 打图</strong><br>
<strong>4.3 验证适配性</strong><br>
<strong>4.4 验证难度</strong><br>
<strong>4.5(可选) 探讨具体排列</strong><br>
<strong>4.6(可选) 宏观探讨</strong><br>
<strong>4.7 可信度声明</strong></p>
<h2 id="冲突处理">5 冲突处理</h2>
<p><strong>5.1 友好讨论原则</strong><br>
<strong>5.2 测试人员之间的意见冲突</strong><br>
<strong>5.3 测试人员与谱师的意见冲突</strong><br>
<strong>5.4 图池更新带来的冲突</strong><br>
<strong>5.5 自我否定</strong></p>
<h2 id="总结">6 总结</h2>
</div>
</body>

</html>
