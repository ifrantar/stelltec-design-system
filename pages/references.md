---
layout: page
navigation : main
title: References
permalink: /references/
---

<header class="main__header">
  <h1>References</h1>
  <p>Handy reusable settings when writing scss to keep as a reference when needed to.</p>
</header>

<section class="main__block">
  <h2>Important SASS variables</h2>
  <h3>Measurement variables</h3>
  <p><!-- react-text: 16 -->In order to maintain a flexible enough layout from the user perspective for our applications, we will be using <!-- /react-text --><code>rem</code><!-- react-text: 18 --> and <!-- /react-text --><code>em</code><!-- react-text: 20 --> as our measurement units. <!-- /react-text --><code>px</code><!-- react-text: 22 -->'s will be useful for things like borders, or for specific fixed-width objects.<!-- /react-text --></p>
  <pre><code class="scss code__samples code__samples--only hljs"><span class="hljs-variable">$space__xx-small</span>        : .<span class="hljs-number">25rem</span>;    <span class="hljs-comment">// 4px</span>
<span class="hljs-variable">$space__x-small</span>         : .<span class="hljs-number">5rem</span>;     <span class="hljs-comment">// 8px</span>
<span class="hljs-variable">$space__small</span>           : .<span class="hljs-number">75rem</span>;    <span class="hljs-comment">// 12px</span>
<span class="hljs-variable">$space__s-medium</span>        : <span class="hljs-number">1.05rem</span>;   <span class="hljs-comment">// 16px</span>
<span class="hljs-variable">$space__medium</span>          : <span class="hljs-number">1.5rem</span>;    <span class="hljs-comment">// 24px</span>
<span class="hljs-variable">$space__large</span>           : <span class="hljs-number">2rem</span>;      <span class="hljs-comment">// 32px</span>
<span class="hljs-variable">$space__x-large</span>         : <span class="hljs-number">2.6rem</span>;    <span class="hljs-comment">// 40px</span>
<span class="hljs-variable">$space__xx-large</span>        : <span class="hljs-number">3.2rem</span>;    <span class="hljs-comment">// 48px</span>
<span class="hljs-variable">$space__3x-large</span>        : <span class="hljs-number">3.4rem</span>;    <span class="hljs-comment">// 52px</span>
<span class="hljs-variable">$space__4x-large</span>        : <span class="hljs-number">3.9rem</span>;    <span class="hljs-comment">// 60px</span>
<span class="hljs-variable">$space__5x-large</span>        : <span class="hljs-number">4.4rem</span>;    <span class="hljs-comment">// 68px</span>
<span class="hljs-variable">$space__6x-large</span>        : <span class="hljs-number">4.93rem</span>;   <span class="hljs-comment">// 76px</span>
<span class="hljs-variable">$space__7x-large</span>        : <span class="hljs-number">5.43rem</span>;   <span class="hljs-comment">// 84px</span></code></pre>
  <h3>Typography variables</h3>
  <pre><code class="scss code__samples code__samples--only hljs"><span class="hljs-comment">// Base font</span>

<span class="hljs-variable">$base-font-size</span>:  <span class="hljs-number">96.5%</span> !default;
<span class="hljs-variable">$base-font-weight</span>: <span class="hljs-number">400</span> !default;

<span class="hljs-comment">// Font to try out on our applications</span>

<span class="hljs-variable">$font__family--primary</span>          : <span class="hljs-string">"Avenir Next"</span>;
<span class="hljs-variable">$font__family--secondary</span>        : <span class="hljs-string">"Museo"</span>;

<span class="hljs-comment">// Font sizes</span>

<span class="hljs-variable">$font__size--5x-large</span>           : <span class="hljs-number">4.913rem</span>;     <span class="hljs-comment">// 78</span>
<span class="hljs-variable">$font__size--4x-large</span>           : <span class="hljs-number">4.094rem</span>;     <span class="hljs-comment">// 65</span>
<span class="hljs-variable">$font__size--3x-large</span>           : <span class="hljs-number">3.412rem</span>;     <span class="hljs-comment">// 54</span>
<span class="hljs-variable">$font__size--xx-large</span>           : <span class="hljs-number">2.843rem</span>;     <span class="hljs-comment">// 45</span>
<span class="hljs-variable">$font__size--x-large</span>            : <span class="hljs-number">2.369rem</span>;     <span class="hljs-comment">// 37</span>
<span class="hljs-variable">$font__size--large</span>              : <span class="hljs-number">1.689rem</span>;     <span class="hljs-comment">// 27</span>
<span class="hljs-variable">$font__size--medium</span>             : <span class="hljs-number">1.2rem</span>;       <span class="hljs-comment">// 19</span>
<span class="hljs-variable">$font__size--base</span>               : <span class="hljs-number">1rem</span>;         <span class="hljs-comment">// 16</span>
<span class="hljs-variable">$font__size--small</span>              : <span class="hljs-number">0.833rem</span>;     <span class="hljs-comment">// 13</span>
<span class="hljs-variable">$font__size--tiny</span>               : <span class="hljs-number">0.694rem</span>;     <span class="hljs-comment">// 11</span>

<span class="hljs-comment">// Font weights</span>

<span class="hljs-variable">$font__weight--light</span>            : <span class="hljs-number">200</span> !default;
<span class="hljs-variable">$font__weight--normal</span>           : <span class="hljs-number">400</span> !default;
<span class="hljs-variable">$font__weight--medium</span>           : <span class="hljs-number">500</span> !default;
<span class="hljs-variable">$font__weight--demi-bold</span>        : <span class="hljs-number">600</span> !default;
<span class="hljs-variable">$font__weight--bold</span>             : <span class="hljs-number">700</span> !default;
<span class="hljs-variable">$font__weight--heavy</span>            : <span class="hljs-number">900</span> !default;

<span class="hljs-comment">// Line heights</span>

<span class="hljs-variable">$font__line-height--base</span>        : <span class="hljs-number">1</span>;
<span class="hljs-variable">$font__line-height--heading</span>     : <span class="hljs-number">1.42</span>;
<span class="hljs-variable">$font__line-height--body</span>        : <span class="hljs-number">1.7</span>;
<span class="hljs-variable">$font__line-height--navigation</span>  : <span class="hljs-number">2.4</span>;</code></pre>
  <h3>Z-index variables</h3>
  <pre><code class="scss code__samples code__samples--only hljs"><span class="hljs-variable">$z-index__modal</span>               : <span class="hljs-number">9000</span>;
<span class="hljs-variable">$z-index__overlay</span>             : <span class="hljs-number">8000</span>;
<span class="hljs-variable">$z-index__sticky-message</span>      : <span class="hljs-number">7000</span>;
<span class="hljs-variable">$z-index__dropdown</span>            : <span class="hljs-number">6000</span>;
<span class="hljs-variable">$z-index__header</span>              : <span class="hljs-number">5000</span>;
<span class="hljs-variable">$z-index__footer</span>              : <span class="hljs-number">4000</span>;
<span class="hljs-variable">$z-index__active</span>              : <span class="hljs-number">3000</span>;
<span class="hljs-variable">$z-index__hidden</span>              : -<span class="hljs-number">1</span>;
<span class="hljs-variable">$z-index__overflow--hidden</span>    : -<span class="hljs-number">1</span>;
<span class="hljs-variable">$z-index__overflow--options</span>   : <span class="hljs-number">1</span>;</code></pre>
</section>
