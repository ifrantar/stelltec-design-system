---
layout: page
navigation : main
title: Sliders
permalink: /sliders/
---

<section class="main__header">
  <h1 class="main__header--header">Sliders</h1>
  <p>Sliders represent a component that users will find very useful for our applications and save them time when selecting from a range of values that otherwise would need to by typed manually.</p>
</section>
<section class="main__block">
  <h2>Default sliders</h2>
  <p>The default presentation of the sliders.</p>
  <section class="demos">
    <div class="demos__header">
      <h4>Example</h4><a class="code__action"><span class="icon icon__size--medium icon__color--action"><svg height="24px" viewbox="0 0 24 24" width="24px">
      <g fill="inherit">
        <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
      </g></svg></span></a>
    </div>
    <div class="demos__body">
      <div>
        <div class="slider__container u__margin-bottom--medium">
          <div class="slider__tracker">
            <div class="slider__trail slider__trail--left" style="width: 200px;">
              <div class="slider__handle"></div>
            </div>
          </div>
        </div>
        <div class="slider__container u__margin-bottom--medium">
          <div class="slider__tracker slider__tracker">
            <div class="slider__trail slider__trail--left" style="width: 200px;">
              <div class="slider__handle"></div>
            </div>
            <div class="slider__trail slider__trail--right" style="width: 200px;">
              <div class="slider__handle"></div>
            </div>
          </div>
        </div>
        <div class="slider__container">
          <div class="slider__tracker slider__tracker--range">
            <div class="slider__trail slider__trail--left" style="width: 200px;">
              <div class="slider__handle"></div>
            </div>
            <div class="slider__trail slider__trail--right" style="width: 200px;">
              <div class="slider__handle"></div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="demos__code">
      <div class="code__samples">
        <pre><code class="html hljs xml"></code></pre>
        <div>
          <code class="html hljs xml"><span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__container"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__tracker"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--left"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:400px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__container"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__tracker slider__tracker"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--left"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:600px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--right"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:500px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__container"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__tracker slider__tracker--range"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--left"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:350px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--right"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:550px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span></code>
        </div>
        <pre></pre>
      </div>
    </div>
  </section>
  <p>Here sliders are presented in 3 ways:</p>
  <ol class="list__ol">
    <li>Simple slider</li>
    <li>Dual slider</li>
    <li>Range slider</li>
  </ol>
  <p><!-- react-text: 49 -->One thing to notice here is that I have <!-- /react-text --><code>style</code><!-- react-text: 51 --> atribute in the HTML. The reason this attribute is in the markup is because that's the element that the scripts will need to update once the user start interacting with the sliders.<!-- /react-text --></p>
</section>
<section class="main__block">
  <h2>Sliders with textfields</h2>
  <p>Here we'll cover scenarios where you need to specify value through inputs or update those values with the sliders.</p>
  <section class="demos">
    <div class="demos__header">
      <h4>Example</h4><a class="code__action"><span class="icon icon__size--medium icon__color--action"><svg height="24px" viewbox="0 0 24 24" width="24px">
      <g fill="inherit">
        <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
      </g></svg></span></a>
    </div>
    <div class="demos__body">
      <div>
        <div class="slider__wrapper slider__wrapper--with-textfields" style="margin-bottom: 42px;">
          <div class="slider__value-field">
            <input class="f__textfield f__textfield--size-s" type="text" value="">
          </div>
          <div class="slider__container">
            <div class="slider__tracker">
              <div class="slider__trail slider__trail--left" style="width: 200px;">
                <div class="slider__handle"></div>
              </div>
            </div>
          </div>
        </div>
        <div class="slider__wrapper slider__wrapper--with-textfields" style="margin-bottom: 42px;">
          <div class="slider__container">
            <div class="slider__tracker">
              <div class="slider__trail slider__trail--left" style="width: 200px;">
                <div class="slider__handle"></div>
              </div>
            </div>
          </div>
          <div class="slider__value-field">
            <input class="f__textfield f__textfield--size-s" type="text" value="">
          </div>
        </div>
        <div class="slider__wrapper slider__wrapper--with-textfields" style="margin-bottom: 47px;">
          <div class="slider__value-field">
            <input class="f__textfield f__textfield--size-s" type="text" value="">
          </div>
          <div class="slider__container">
            <div class="slider__tracker">
              <div class="slider__trail slider__trail--left" style="width: 200px;">
                <div class="slider__handle"></div>
              </div>
              <div class="slider__trail slider__trail--right" style="width: 200px;">
                <div class="slider__handle"></div>
              </div>
            </div>
          </div>
          <div class="slider__value-field">
            <input class="f__textfield f__textfield--size-s" type="text" value="">
          </div>
        </div>
        <div class="slider__wrapper slider__wrapper--with-textfields slider__wrapper--no-flex" style="margin-bottom: -10px;">
          <div class="slider__container">
            <div class="slider__tracker">
              <div class="slider__trail slider__trail--left" style="width: 200px;">
                <div class="slider__handle"></div>
              </div>
              <div class="slider__trail slider__trail--right" style="width: 200px;">
                <div class="slider__handle"></div>
              </div>
            </div>
          </div>
          <div class="slider__value-field slider__value-field--left">
            <input class="f__textfield f__textfield--size-s" type="text" value="">
          </div>
          <div class="slider__value-field slider__value-field--right">
            <input class="f__textfield f__textfield--size-s" type="text" value="">
          </div>
        </div>
        <div class="slider__wrapper slider__wrapper--with-textfields slider__wrapper--no-flex" style="margin-bottom: 52px;">
          <div class="slider__value-field slider__value-field--left">
            <input class="f__textfield f__textfield--size-s" type="text" value="">
          </div>
          <div class="slider__value-field slider__value-field--right">
            <input class="f__textfield f__textfield--size-s" type="text" value="">
          </div>
          <div class="slider__container">
            <div class="slider__tracker">
              <div class="slider__trail slider__trail--left" style="width: 200px;">
                <div class="slider__handle"></div>
              </div>
              <div class="slider__trail slider__trail--right" style="width: 200px;">
                <div class="slider__handle"></div>
              </div>
            </div>
          </div>
        </div>
        <div class="slider__wrapper slider__wrapper--with-textfields slider__wrapper--no-flex" style="margin-bottom: 50px;">
          <div class="slider__container">
            <div class="slider__tracker">
              <div class="slider__trail slider__trail--left" style="width: 200px;">
                <div class="slider__handle">
                  <div class="slider__value-field slider__value-field--left">
                    <input class="f__textfield f__textfield--size-s" type="text" value="">
                  </div>
                </div>
              </div>
              <div class="slider__trail slider__trail--right" style="width: 200px;">
                <div class="slider__handle">
                  <div class="slider__value-field slider__value-field--right">
                    <input class="f__textfield f__textfield--size-s" type="text" value="">
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="slider__wrapper slider__wrapper--with-textfields slider__wrapper--no-flex" style="margin-bottom: 40px;">
          <div class="slider__container">
            <div class="slider__tracker slider__tracker--range">
              <div class="slider__trail slider__trail--left" style="width: 200px;">
                <div class="slider__handle">
                  <div class="slider__value-field slider__value-field--left">
                    <input class="f__textfield f__textfield--size-s" type="text" value="">
                  </div>
                </div>
              </div>
              <div class="slider__trail slider__trail--right" style="width: 200px;">
                <div class="slider__handle">
                  <div class="slider__value-field slider__value-field--right">
                    <input class="f__textfield f__textfield--size-s" type="text" value="">
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="demos__code">
      <div class="code__samples">
        <pre><code class="html hljs xml"></code></pre>
        <div>
          <code class="html hljs xml"><span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__wrapper slider__wrapper--with-textfields"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__value-field"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">input</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"f__textfield f__textfield--size-s"</span> <span class="hljs-attr">type</span>=<span class="hljs-string">"text"</span> <span class="hljs-attr">value</span>=<span class="hljs-string">""</span> /&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__container"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__tracker"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--left"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:200px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-comment">&lt;!-- Slider with input right --&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__wrapper slider__wrapper--with-textfields"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__container"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__tracker"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--left"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:600px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__value-field"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">input</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"f__textfield f__textfield--size-s"</span> <span class="hljs-attr">type</span>=<span class="hljs-string">"text"</span> <span class="hljs-attr">value</span>=<span class="hljs-string">""</span> /&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">br</span> /&gt;</span> <span class="hljs-comment">&lt;!-- Slider with input left &amp; right --&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__wrapper slider__wrapper--with-textfields"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__value-field"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">input</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"f__textfield f__textfield--size-s"</span> <span class="hljs-attr">type</span>=<span class="hljs-string">"text"</span> <span class="hljs-attr">value</span>=<span class="hljs-string">""</span> /&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__container"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__tracker"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--left"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:600px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--right"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:600px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__value-field"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">input</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"f__textfield f__textfield--size-s"</span> <span class="hljs-attr">type</span>=<span class="hljs-string">"text"</span> <span class="hljs-attr">value</span>=<span class="hljs-string">""</span> /&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-comment">&lt;!-- Slider with input left &amp; right no flexbox --&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__wrapper slider__wrapper--with-textfields slider__wrapper--no-flex"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__container"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__tracker"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--left"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:600px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--right"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:600px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__value-field slider__value-field--left"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">input</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"f__textfield f__textfield--size-s"</span> <span class="hljs-attr">type</span>=<span class="hljs-string">"text"</span> <span class="hljs-attr">value</span>=<span class="hljs-string">""</span> /&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__value-field slider__value-field--right"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">input</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"f__textfield f__textfield--size-s"</span> <span class="hljs-attr">type</span>=<span class="hljs-string">"text"</span> <span class="hljs-attr">value</span>=<span class="hljs-string">""</span> /&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__wrapper slider__wrapper--with-textfields slider__wrapper--no-flex"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__value-field slider__value-field--left"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">input</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"f__textfield f__textfield--size-s"</span> <span class="hljs-attr">type</span>=<span class="hljs-string">"text"</span> <span class="hljs-attr">value</span>=<span class="hljs-string">""</span> /&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__value-field slider__value-field--right"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">input</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"f__textfield f__textfield--size-s"</span> <span class="hljs-attr">type</span>=<span class="hljs-string">"text"</span> <span class="hljs-attr">value</span>=<span class="hljs-string">""</span> /&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__container"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__tracker"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--left"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:600px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--right"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:600px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-comment">&lt;!-- Slider with input left &amp; right attached to handle --&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__wrapper slider__wrapper--with-textfields slider__wrapper--no-flex"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__container"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__tracker"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--left"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:600px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__value-field slider__value-field--left"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">input</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"f__textfield f__textfield--size-s"</span> <span class="hljs-attr">type</span>=<span class="hljs-string">"text"</span> <span class="hljs-attr">value</span>=<span class="hljs-string">""</span> /&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--right"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:600px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__value-field slider__value-field--right"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">input</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"f__textfield f__textfield--size-s"</span> <span class="hljs-attr">type</span>=<span class="hljs-string">"text"</span> <span class="hljs-attr">value</span>=<span class="hljs-string">""</span> /&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__wrapper slider__wrapper--with-textfields slider__wrapper--no-flex"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__container"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__tracker slider__tracker--range"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--left"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:350px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__value-field slider__value-field--left"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">input</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"f__textfield f__textfield--size-s"</span> <span class="hljs-attr">type</span>=<span class="hljs-string">"text"</span> <span class="hljs-attr">value</span>=<span class="hljs-string">""</span> /&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--right"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:550px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__value-field slider__value-field--right"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">input</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"f__textfield f__textfield--size-s"</span> <span class="hljs-attr">type</span>=<span class="hljs-string">"text"</span> <span class="hljs-attr">value</span>=<span class="hljs-string">""</span> /&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span></code>
        </div>
        <pre></pre>
      </div>
    </div>
  </section>
</section>
<section class="main__block">
  <h2>Sliders with Labels</h2>
  <p>These are very similar to the slider with input fields, but instead they use text label for the updated values.</p>
  <section class="demos">
    <div class="demos__header">
      <h4>Example</h4><a class="code__action"><span class="icon icon__size--medium icon__color--action"><svg height="24px" viewbox="0 0 24 24" width="24px">
      <g fill="inherit">
        <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
      </g></svg></span></a>
    </div>
    <div class="demos__body">
      <div>
        <div class="slider__wrapper slider__wrapper--with-textfields" style="margin-bottom: 28px;">
          <div class="slider__value-label">
            <label>100</label>
          </div>
          <div class="slider__container">
            <div class="slider__tracker">
              <div class="slider__trail slider__trail--left" style="width: 200px;">
                <div class="slider__handle"></div>
              </div>
            </div>
          </div>
        </div>
        <div class="slider__wrapper slider__wrapper--with-textfields" style="margin-bottom: 28px;">
          <div class="slider__container">
            <div class="slider__tracker">
              <div class="slider__trail slider__trail--left" style="width: 200px;">
                <div class="slider__handle"></div>
              </div>
            </div>
          </div>
          <div class="slider__value-label">
            <label>100</label>
          </div>
        </div>
        <div class="slider__wrapper slider__wrapper--with-textfields" style="margin-bottom: 35px;">
          <div class="slider__value-label">
            <label>100</label>
          </div>
          <div class="slider__container">
            <div class="slider__tracker">
              <div class="slider__trail slider__trail--left" style="width: 200px;">
                <div class="slider__handle"></div>
              </div>
              <div class="slider__trail slider__trail--right" style="width: 200px;">
                <div class="slider__handle"></div>
              </div>
            </div>
          </div>
          <div class="slider__value-label">
            <label>100</label>
          </div>
        </div>
        <div class="slider__wrapper slider__wrapper--with-textfields slider__wrapper--no-flex" style="margin-bottom: -12px;">
          <div class="slider__container">
            <div class="slider__tracker">
              <div class="slider__trail slider__trail--left" style="width: 200px;">
                <div class="slider__handle"></div>
              </div>
              <div class="slider__trail slider__trail--right" style="width: 200px;">
                <div class="slider__handle"></div>
              </div>
            </div>
          </div>
          <div class="slider__value-label slider__value-label--left">
            <label>100</label>
          </div>
          <div class="slider__value-label slider__value-label--right">
            <label>100</label>
          </div>
        </div>
        <div class="slider__wrapper slider__wrapper--with-textfields slider__wrapper--no-flex" style="margin-bottom: 40px;">
          <div class="slider__value-label slider__value-label--left">
            <label>100</label>
          </div>
          <div class="slider__value-label slider__value-label--right">
            <label>100</label>
          </div>
          <div class="slider__container">
            <div class="slider__tracker">
              <div class="slider__trail slider__trail--left" style="width: 200px;">
                <div class="slider__handle"></div>
              </div>
              <div class="slider__trail slider__trail--right" style="width: 200px;">
                <div class="slider__handle"></div>
              </div>
            </div>
          </div>
        </div>
        <div class="slider__wrapper slider__wrapper--with-textfields slider__wrapper--no-flex" style="margin-bottom: 40px;">
          <div class="slider__container">
            <div class="slider__tracker">
              <div class="slider__trail slider__trail--left" style="width: 200px;">
                <div class="slider__handle">
                  <div class="slider__value-label slider__value-label--left">
                    <label>100</label>
                  </div>
                </div>
              </div>
              <div class="slider__trail slider__trail--right" style="width: 200px;">
                <div class="slider__handle">
                  <div class="slider__value-label slider__value-label--right">
                    <label>100</label>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="slider__wrapper slider__wrapper--with-textfields slider__wrapper--no-flex" style="margin-bottom: 40px;">
          <div class="slider__container">
            <div class="slider__tracker slider__tracker--range">
              <div class="slider__trail slider__trail--left" style="width: 200px;">
                <div class="slider__handle">
                  <div class="slider__value-label slider__value-label--left">
                    <label>100</label>
                  </div>
                </div>
              </div>
              <div class="slider__trail slider__trail--right" style="width: 200px;">
                <div class="slider__handle">
                  <div class="slider__value-label slider__value-label--right">
                    <label>100</label>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="demos__code">
      <div class="code__samples">
        <pre><code class="html hljs xml"></code></pre>
        <div>
          <code class="html hljs xml"><span class="hljs-comment">&lt;!-- Slider label left --&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__wrapper slider__wrapper--with-textfields"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__value-label"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">label</span>&gt;</span>100<span class="hljs-tag">&lt;/<span class="hljs-name">label</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__container"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__tracker"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--left"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:600px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-comment">&lt;!-- Slider label right --&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__wrapper slider__wrapper--with-textfields"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__container"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__tracker"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--left"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:600px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__value-label"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">label</span>&gt;</span>100<span class="hljs-tag">&lt;/<span class="hljs-name">label</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-comment">&lt;!-- Dual slider with left and right labels --&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__wrapper slider__wrapper--with-textfields"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__value-label"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">label</span>&gt;</span>100<span class="hljs-tag">&lt;/<span class="hljs-name">label</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__container"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__tracker"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--left"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:600px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--right"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:600px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__value-label"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">label</span>&gt;</span>100<span class="hljs-tag">&lt;/<span class="hljs-name">label</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-comment">&lt;!-- Dual slider with left and right labels below tracker --&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__wrapper slider__wrapper--with-textfields slider__wrapper--no-flex"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__container"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__tracker"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--left"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:600px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--right"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:600px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__value-label slider__value-label--left"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">label</span>&gt;</span>100<span class="hljs-tag">&lt;/<span class="hljs-name">label</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__value-label slider__value-label--right"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">label</span>&gt;</span>100<span class="hljs-tag">&lt;/<span class="hljs-name">label</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-comment">&lt;!-- Dual slider with left and right labels above tracker --&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__wrapper slider__wrapper--with-textfields slider__wrapper--no-flex"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__value-label slider__value-label--left"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">label</span>&gt;</span>100<span class="hljs-tag">&lt;/<span class="hljs-name">label</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__value-label slider__value-label--right"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">label</span>&gt;</span>100<span class="hljs-tag">&lt;/<span class="hljs-name">label</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__container"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__tracker"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--left"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:600px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--right"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:600px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-comment">&lt;!-- Dual slider with label left &amp; right attached to handle --&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__wrapper slider__wrapper--with-textfields slider__wrapper--no-flex"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__container"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__tracker"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--left"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:600px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__value-label slider__value-label--left"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">label</span>&gt;</span>100<span class="hljs-tag">&lt;/<span class="hljs-name">label</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--right"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:600px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__value-label slider__value-label--right"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">label</span>&gt;</span>100<span class="hljs-tag">&lt;/<span class="hljs-name">label</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-comment">&lt;!-- Range slider with label left &amp; right attached to handle --&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__wrapper slider__wrapper--with-textfields slider__wrapper--no-flex"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__container"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__tracker slider__tracker--range"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--left"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:350px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__value-label slider__value-label--left"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">label</span>&gt;</span>100<span class="hljs-tag">&lt;/<span class="hljs-name">label</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--right"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:550px;"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__value-label slider__value-label--right"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">label</span>&gt;</span>100<span class="hljs-tag">&lt;/<span class="hljs-name">label</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span></code>
        </div>
        <pre></pre>
      </div>
    </div>
  </section>
</section>
<section class="main__block">
  <h2>Sliders with dynamic pin marker</h2>
  <p>Best use case for this would be to indicate percentages.</p>
  <section class="demos">
    <div class="demos__header">
      <h4>Example</h4><a class="code__action"><span class="icon icon__size--medium icon__color--action"><svg height="24px" viewbox="0 0 24 24" width="24px">
      <g fill="inherit">
        <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
      </g></svg></span></a>
    </div>
    <div class="demos__body">
      <div>
        <div class="slider__wrapper" style="margin-bottom: 40px; margin-top: 24px;">
          <div class="slider__container">
            <div class="slider__tracker">
              <div class="slider__trail slider__trail--left" style="width: 200px;">
                <div class="slider__handle">
                  <div class="slider__pin">
                    <span class="slider__text">100</span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="slider__wrapper" style="margin-bottom: 40px;">
          <div class="slider__container">
            <div class="slider__tracker">
              <div class="slider__trail slider__trail--right" style="width: 200px;">
                <div class="slider__handle">
                  <div class="slider__pin">
                    <span class="slider__text">100</span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="slider__wrapper" style="margin-bottom: 40px;">
          <div class="slider__container">
            <div class="slider__tracker">
              <div class="slider__trail slider__trail--left" style="width: 200px;">
                <div class="slider__handle">
                  <div class="slider__pin">
                    <span class="slider__text">100</span>
                  </div>
                </div>
              </div>
              <div class="slider__trail slider__trail--right" style="width: 200px;">
                <div class="slider__handle">
                  <div class="slider__pin">
                    <span class="slider__text">100</span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="slider__wrapper">
          <div class="slider__container">
            <div class="slider__tracker slider__tracker--range">
              <div class="slider__trail slider__trail--left" style="width: 200px;">
                <div class="slider__handle">
                  <div class="slider__pin">
                    <span class="slider__text">100</span>
                  </div>
                </div>
              </div>
              <div class="slider__trail slider__trail--right" style="width: 200px;">
                <div class="slider__handle">
                  <div class="slider__pin">
                    <span class="slider__text">100</span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="demos__code">
      <div class="code__samples">
        <pre><code class="html hljs xml"></code></pre>
        <div>
          <code class="html hljs xml"><span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__wrapper"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__container"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__tracker"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--left"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:200px"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__pin"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">span</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__text"</span>&gt;</span>100<span class="hljs-tag">&lt;/<span class="hljs-name">span</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__wrapper"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__container"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__tracker"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--right"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:200px"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__pin"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">span</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__text"</span>&gt;</span>100<span class="hljs-tag">&lt;/<span class="hljs-name">span</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__wrapper"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__container"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__tracker"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--left"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:200px"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__pin"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">span</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__text"</span>&gt;</span>100<span class="hljs-tag">&lt;/<span class="hljs-name">span</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--right"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:200px"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__pin"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">span</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__text"</span>&gt;</span>100<span class="hljs-tag">&lt;/<span class="hljs-name">span</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__wrapper"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__container"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__tracker slider__tracker--range"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--left"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:200px"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__pin"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">span</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__text"</span>&gt;</span>100<span class="hljs-tag">&lt;/<span class="hljs-name">span</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__trail slider__trail--right"</span> <span class="hljs-attr">style</span>=<span class="hljs-string">"width:200px"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__handle"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__pin"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">span</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"slider__text"</span>&gt;</span>100<span class="hljs-tag">&lt;/<span class="hljs-name">span</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span></code>
        </div>
        <pre></pre>
      </div>
    </div>
  </section>
</section>
