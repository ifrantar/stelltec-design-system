---
layout: page
navigation : main
title: Grid
permalink: /grid/
---

<header class="main__header">
	<h1 class="main__header--header">Grid</h1>
</header>
<section class="main__block">
	<h2>Initial grid setup</h2>
	<p>We are using very basic setup of the grid. We are not indicating the columns specifically. Thanks for flexbox we are putting container into <!-- /react-text --><code>grid__item</code><!-- react-text: 16 --> and they align horizontally.<!-- /react-text --></p>
	<p>You could go on adding <code>grid_item</code>'s but the optimal and sufficient amount should be 6.</p>
	<section class="demos">
    <div class="demos__header">
      <h4>Example</h4>
      <a class="code__action">
        <span class="icon icon__size--medium icon__color--action">
          <svg width="24px" height="24px" viewBox="0 0 24 24">
            <g fill="inherit">
                <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
            </g>
          </svg>
        </span>
      </a>
    </div>
		<div class="demos__body">
			<div>
				<div class="grid grid__gutter">
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 1</div>
					</div>
				</div>
				<div class="grid grid__gutter">
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 2</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 2</div>
					</div>
				</div>
				<div class="grid grid__gutter">
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 3</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 3</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 3</div>
					</div>
				</div>
				<div class="grid grid__gutter">
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 4</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 4</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 4</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 4</div>
					</div>
				</div>
				<div class="grid grid__gutter">
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 5</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 5</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 5</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 5</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 5</div>
					</div>
				</div>
				<div class="grid grid__gutter">
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 6</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 6</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 6</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 6</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 6</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 6</div>
					</div>
				</div>
			</div>
		</div>
		<div class="demos__code">
			<div class="code__samples">
				<pre><code class="html hljs xml">
&#x3C;div class=&#x22;grid grid__gutter&#x22;&#x3E;
  &#x3C;div class=&#x22;grid__item&#x22;&#x3E;
    &#x3C;div class=&#x22;demo-grid&#x22;&#x3E;grid 1 / 1&#x3C;/div&#x3E;
  &#x3C;/div&#x3E;
&#x3C;/div&#x3E;
&#x3C;div class=&#x22;grid grid__gutter&#x22;&#x3E;
  &#x3C;div class=&#x22;grid__item&#x22;&#x3E;
    &#x3C;div class=&#x22;demo-grid&#x22;&#x3E;grid 1 / 2&#x3C;/div&#x3E;
  &#x3C;/div&#x3E;
  &#x3C;div class=&#x22;grid__item&#x22;&#x3E;
    &#x3C;div class=&#x22;demo-grid&#x22;&#x3E;grid 1 / 2&#x3C;/div&#x3E;
  &#x3C;/div&#x3E;
&#x3C;/div&#x3E;
&#x3C;div class=&#x22;grid grid__gutter&#x22;&#x3E;
  &#x3C;div class=&#x22;grid__item&#x22;&#x3E;
    &#x3C;div class=&#x22;demo-grid&#x22;&#x3E;grid 1 / 3&#x3C;/div&#x3E;
  &#x3C;/div&#x3E;
  &#x3C;div class=&#x22;grid__item&#x22;&#x3E;
    &#x3C;div class=&#x22;demo-grid&#x22;&#x3E;grid 1 / 3&#x3C;/div&#x3E;
  &#x3C;/div&#x3E;
  &#x3C;div class=&#x22;grid__item&#x22;&#x3E;
    &#x3C;div class=&#x22;demo-grid&#x22;&#x3E;grid 1 / 3&#x3C;/div&#x3E;
  &#x3C;/div&#x3E;
&#x3C;/div&#x3E;
&#x3C;div class=&#x22;grid grid__gutter&#x22;&#x3E;
  &#x3C;div class=&#x22;grid__item&#x22;&#x3E;
    &#x3C;div class=&#x22;demo-grid&#x22;&#x3E;grid 1 / 4&#x3C;/div&#x3E;
  &#x3C;/div&#x3E;
  &#x3C;div class=&#x22;grid__item&#x22;&#x3E;
    &#x3C;div class=&#x22;demo-grid&#x22;&#x3E;grid 1 / 4&#x3C;/div&#x3E;
  &#x3C;/div&#x3E;
  &#x3C;div class=&#x22;grid__item&#x22;&#x3E;
    &#x3C;div class=&#x22;demo-grid&#x22;&#x3E;grid 1 / 4&#x3C;/div&#x3E;
  &#x3C;/div&#x3E;
  &#x3C;div class=&#x22;grid__item&#x22;&#x3E;
    &#x3C;div class=&#x22;demo-grid&#x22;&#x3E;grid 1 / 4&#x3C;/div&#x3E;
  &#x3C;/div&#x3E;
&#x3C;/div&#x3E;
&#x3C;div class=&#x22;grid grid__gutter&#x22;&#x3E;
  &#x3C;div class=&#x22;grid__item&#x22;&#x3E;
    &#x3C;div class=&#x22;demo-grid&#x22;&#x3E;grid 1 / 5&#x3C;/div&#x3E;
  &#x3C;/div&#x3E;
  &#x3C;div class=&#x22;grid__item&#x22;&#x3E;
    &#x3C;div class=&#x22;demo-grid&#x22;&#x3E;grid 1 / 5&#x3C;/div&#x3E;
  &#x3C;/div&#x3E;
  &#x3C;div class=&#x22;grid__item&#x22;&#x3E;
    &#x3C;div class=&#x22;demo-grid&#x22;&#x3E;grid 1 / 5&#x3C;/div&#x3E;
  &#x3C;/div&#x3E;
  &#x3C;div class=&#x22;grid__item&#x22;&#x3E;
    &#x3C;div class=&#x22;demo-grid&#x22;&#x3E;grid 1 / 5&#x3C;/div&#x3E;
  &#x3C;/div&#x3E;
  &#x3C;div class=&#x22;grid__item&#x22;&#x3E;
    &#x3C;div class=&#x22;demo-grid&#x22;&#x3E;grid 1 / 5&#x3C;/div&#x3E;
  &#x3C;/div&#x3E;
&#x3C;/div&#x3E;
&#x3C;div class=&#x22;grid grid__gutter&#x22;&#x3E;
  &#x3C;div class=&#x22;grid__item&#x22;&#x3E;
    &#x3C;div class=&#x22;demo-grid&#x22;&#x3E;grid 1 / 6&#x3C;/div&#x3E;
  &#x3C;/div&#x3E;
  &#x3C;div class=&#x22;grid__item&#x22;&#x3E;
    &#x3C;div class=&#x22;demo-grid&#x22;&#x3E;grid 1 / 6&#x3C;/div&#x3E;
  &#x3C;/div&#x3E;
  &#x3C;div class=&#x22;grid__item&#x22;&#x3E;
    &#x3C;div class=&#x22;demo-grid&#x22;&#x3E;grid 1 / 6&#x3C;/div&#x3E;
  &#x3C;/div&#x3E;
  &#x3C;div class=&#x22;grid__item&#x22;&#x3E;
    &#x3C;div class=&#x22;demo-grid&#x22;&#x3E;grid 1 / 6&#x3C;/div&#x3E;
  &#x3C;/div&#x3E;
  &#x3C;div class=&#x22;grid__item&#x22;&#x3E;
    &#x3C;div class=&#x22;demo-grid&#x22;&#x3E;grid 1 / 6&#x3C;/div&#x3E;
  &#x3C;/div&#x3E;
  &#x3C;div class=&#x22;grid__item&#x22;&#x3E;
    &#x3C;div class=&#x22;demo-grid&#x22;&#x3E;grid 1 / 6&#x3C;/div&#x3E;
  &#x3C;/div&#x3E;
&#x3C;/div&#x3E;
        </code></pre>
			</div>
		</div>
	</section>
</section>
<section class="main__block">
	<h2>Maintaining equivalent heights</h2>
	<p><!-- react-text: 84 -->Make sure you use <!-- /react-text --><code>grid__flex</code><!-- react-text: 86 --> on the grid container element.<!-- /react-text --></p>
	<section class="demos">
    <div class="demos__header">
      <h4>Example</h4>
      <a class="code__action">
        <span class="icon icon__size--medium icon__color--action">
          <svg width="24px" height="24px" viewBox="0 0 24 24">
            <g fill="inherit">
                <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
            </g>
          </svg>
        </span>
      </a>
    </div>
		<div class="demos__body">

				<div class="grid grid__gutter grid__flex">
					<div class="grid__item">
						<div class="demo-grid">Full-height, even when my content doesn't fill the space.</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum mollis velit non gravida venenatis. Praesent consequat lectus purus, ut scelerisque velit condimentum eu. Maecenas sagittis ante ut turpis varius interdum. Quisque tellus ipsum, eleifend non ipsum id, suscipit ultricies neque.</div>
					</div>
				</div>

		</div>
		<div class="demos__code">
			<div class="code__samples">
				<pre><code class="html">
&lt;div class=&quot;grid grid__gutter grid__flex&quot;&gt;
  &lt;div class=&quot;grid__item&quot;&gt;
    &lt;div class=&quot;demo-grid&quot;&gt;Full-height, even when my content doesn&apos;t fill the space.&lt;/div&gt;
  &lt;/div&gt;
  &lt;div class=&quot;grid__item&quot;&gt;
    &lt;div class=&quot;demo-grid&quot;&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum...&lt;/div&gt;
  &lt;/div&gt;
&lt;/div&gt;
        </code></pre>
			</div>
		</div>
	</section>
</section>
<section class="main__block">
	<h2>Using individual sized items</h2>
	<p><!-- react-text: 107 -->You'd need to use the specific <!-- /react-text --><code>grid__item</code><!-- react-text: 109 --> width to indicate the fixed width you want to maintain. And leave the rest of the <!-- /react-text --><code>grid__item</code><!-- react-text: 111 --> elements unspecified.<!-- /react-text --></p>
	<section class="demos">
    <div class="demos__header">
      <h4>Example</h4>
      <a class="code__action">
        <span class="icon icon__size--medium icon__color--action">
          <svg width="24px" height="24px" viewBox="0 0 24 24">
            <g fill="inherit">
                <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
            </g>
          </svg>
        </span>
      </a>
    </div>
		<div class="demos__body">

				<div class="grid grid__gutter">
					<div class="grid__item grid__item--1-6">
						<div class="demo-grid">grid 1 / 6</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">Auto</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">Auto</div>
					</div>
				</div>
				<div class="grid grid__gutter">
					<div class="grid__item">
						<div class="demo-grid">Auto</div>
					</div>
					<div class="grid__item grid__item--1-6">
						<div class="demo-grid">grid 1 / 6</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">Auto</div>
					</div>
					<div class="grid__item grid__item--1-3">
						<div class="demo-grid">grid 1 / 3</div>
					</div>
				</div>

		</div>
		<div class="demos__code">
			<div class="code__samples">
				<pre><code class="html">
&lt;div class=&quot;grid grid__gutter&quot;&gt;
  &lt;div class=&quot;grid__item grid__item--1-6&quot;&gt;
    &lt;div class=&quot;demo-grid&quot;&gt;grid 1 / 6&lt;/div&gt;
  &lt;/div&gt;
  &lt;div class=&quot;grid__item&quot;&gt;
    &lt;div class=&quot;demo-grid&quot;&gt;Auto&lt;/div&gt;
  &lt;/div&gt;
  &lt;div class=&quot;grid__item&quot;&gt;
    &lt;div class=&quot;demo-grid&quot;&gt;Auto&lt;/div&gt;
  &lt;/div&gt;
&lt;/div&gt;
&lt;div class=&quot;grid grid__gutter&quot;&gt;
  &lt;div class=&quot;grid__item&quot;&gt;
    &lt;div class=&quot;demo-grid&quot;&gt;Auto&lt;/div&gt;
  &lt;/div&gt;
  &lt;div class=&quot;grid__item grid__item--1-6&quot;&gt;
    &lt;div class=&quot;demo-grid&quot;&gt;grid 1 / 6&lt;/div&gt;
  &lt;/div&gt;
  &lt;div class=&quot;grid__item&quot;&gt;
    &lt;div class=&quot;demo-grid&quot;&gt;Auto&lt;/div&gt;
  &lt;/div&gt;
  &lt;div class=&quot;grid__item grid__item--1-3&quot;&gt;
    &lt;div class=&quot;demo-grid&quot;&gt;grid 1 / 3&lt;/div&gt;
  &lt;/div&gt;
&lt;/div&gt;
        </code></pre>
			</div>
		</div>
	</section>
</section>
<section class="main__block">
	<h2>Nesting blocks</h2>
	<section class="demos">
    <div class="demos__header">
      <h4>Example</h4>
      <a class="code__action">
        <span class="icon icon__size--medium icon__color--action">
          <svg width="24px" height="24px" viewBox="0 0 24 24">
            <g fill="inherit">
                <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
            </g>
          </svg>
        </span>
      </a>
    </div>
		<div class="demos__body">

				<div class="grid grid__gutter grid__flex">
					<div class="grid__item">
						<div class="demo-grid">
							<div class="grid grid__gutter">
								<div class="grid__item grid__item--1-3">
									<div class="demo-grid">grid 1/3</div>
								</div>
								<div class="grid__item">
									<div class="demo-grid">
										<div class="grid grid__gutter">
											<div class="grid__item">
												<div class="demo-grid">1/2</div>
											</div>
											<div class="grid__item">
												<div class="demo-grid">1/2</div>
											</div>
										</div>
									</div>
								</div>
							</div>
						</div>
					</div>
					<div class="grid__item grid__item--1-3">
						<div class="demo-grid">1/3</div>
					</div>
				</div>

		</div>
		<div class="demos__code">
			<div class="code__samples">
				<pre><code class="html">
&lt;div class=&quot;grid grid__gutter grid__flex&quot;&gt;
  &lt;div class=&quot;grid__item&quot;&gt;
  	&lt;div class=&quot;demo-grid&quot;&gt;
  		&lt;div class=&quot;grid grid__gutter&quot;&gt;
  			&lt;div class=&quot;grid__item grid__item--1-3&quot;&gt;
  				&lt;div class=&quot;demo-grid&quot;&gt;grid 1/3&lt;/div&gt;
  			&lt;/div&gt;
  			&lt;div class=&quot;grid__item&quot;&gt;
  				&lt;div class=&quot;demo-grid&quot;&gt;
  					&lt;div class=&quot;grid grid__gutter&quot;&gt;
  						&lt;div class=&quot;grid__item&quot;&gt;
  							&lt;div class=&quot;demo-grid&quot;&gt;1/2&lt;/div&gt;
  						&lt;/div&gt;
  						&lt;div class=&quot;grid__item&quot;&gt;
  							&lt;div class=&quot;demo-grid&quot;&gt;1/2&lt;/div&gt;
  						&lt;/div&gt;
  					&lt;/div&gt;
  				&lt;/div&gt;
  			&lt;/div&gt;
  		&lt;/div&gt;
  	&lt;/div&gt;
  &lt;/div&gt;
  &lt;div class=&quot;grid__item grid__item--1-3&quot;&gt;
  	&lt;div class=&quot;demo-grid&quot;&gt;1/3&lt;/div&gt;
  &lt;/div&gt;
&lt;/div&gt;
        </code></pre>
			</div>
		</div>
	</section>
</section>
<section class="main__block">
	<h2>Alignment Features</h2>
	<h3>Vertical centering of grid items</h3>
	<section class="demos">
    <div class="demos__header">
      <h4>Example</h4>
      <a class="code__action">
        <span class="icon icon__size--medium icon__color--action">
          <svg width="24px" height="24px" viewBox="0 0 24 24">
            <g fill="inherit">
                <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
            </g>
          </svg>
        </span>
      </a>
    </div>
		<div class="demos__body">

				<div class="grid grid__gutter grid__align--center">
					<div class="grid__item">
						<div class="demo-grid">Grid item vertically centered</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum mollis velit non gravida venenatis. Praesent consequat lectus purus, ut scelerisque velit condimentum eu. Maecenas sagittis ante ut turpis varius interdum. Quisque tellus ipsum, eleifend non ipsum id, suscipit ultricies neque.</div>
					</div>
				</div>

		</div>
		<div class="demos__code">
			<div class="code__samples">
				<pre><code class="html">
  &lt;div class=&quot;grid grid__gutter grid__align--center&quot;&gt;
  	&lt;div class=&quot;grid__item&quot;&gt;
  		&lt;div class=&quot;demo-grid&quot;&gt;Grid item vertically centered&lt;/div&gt;
  	&lt;/div&gt;
  	&lt;div class=&quot;grid__item&quot;&gt;
  	&lt;div class=&quot;demo-grid&quot;&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit...&lt;/div&gt;
  	&lt;/div&gt;
  &lt;/div&gt;
        </code></pre>
			</div>
		</div>
	</section>
	<h3>Top alignment of grid items</h3>
	<section class="demos">
    <div class="demos__header">
      <h4>Example</h4>
      <a class="code__action">
        <span class="icon icon__size--medium icon__color--action">
          <svg width="24px" height="24px" viewBox="0 0 24 24">
            <g fill="inherit">
                <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
            </g>
          </svg>
        </span>
      </a>
    </div>
		<div class="demos__body">

				<div class="grid grid__gutter grid__align--top">
					<div class="grid__item">
						<div class="demo-grid">Top aligned grid item</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum mollis velit non gravida venenatis. Praesent consequat lectus purus, ut scelerisque velit condimentum eu. Maecenas sagittis ante ut turpis varius interdum. Quisque tellus ipsum, eleifend non ipsum id, suscipit ultricies neque.</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">Top aligned grid item</div>
					</div>
				</div>

		</div>
		<div class="demos__code">
			<div class="code__samples">
				<pre><code class="html">
&lt;div class=&quot;grid grid__gutter grid__align--top&quot;&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;Top aligned grid item&lt;/div&gt;
	&lt;/div&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit...&lt;/div&gt;
	&lt;/div&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;Top aligned grid item&lt;/div&gt;
	&lt;/div&gt;
&lt;/div&gt;
        </code></pre>
			</div>
		</div>
	</section>
	<h3>Bottom alignment of grid items</h3>
	<section class="demos">
    <div class="demos__header">
      <h4>Example</h4>
      <a class="code__action">
        <span class="icon icon__size--medium icon__color--action">
          <svg width="24px" height="24px" viewBox="0 0 24 24">
            <g fill="inherit">
                <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
            </g>
          </svg>
        </span>
      </a>
    </div>
		<div class="demos__body">

				<div class="grid grid__gutter grid__align--bottom">
					<div class="grid__item">
						<div class="demo-grid">Bottom aligned grid item</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum mollis velit non gravida venenatis. Praesent consequat lectus purus, ut scelerisque velit condimentum eu. Maecenas sagittis ante ut turpis varius interdum. Quisque tellus ipsum, eleifend non ipsum id, suscipit ultricies neque.</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">Bottom aligned grid item</div>
					</div>
				</div>

		</div>
		<div class="demos__code">
			<div class="code__samples">
				<pre><code class="html">
&lt;div class=&quot;grid grid__gutter grid__align--bottom&quot;&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;Bottom aligned grid item&lt;/div&gt;
	&lt;/div&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum mollis velit non gravida venenatis. Praesent consequat lectus purus, ut scelerisque velit condimentum eu. Maecenas sagittis ante ut turpis varius interdum. Quisque tellus ipsum, eleifend non ipsum id, suscipit ultricies neque.&lt;/div&gt;
	&lt;/div&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;Bottom aligned grid item&lt;/div&gt;
	&lt;/div&gt;
&lt;/div&gt;
        </code></pre>
			</div>
		</div>
	</section>
	<h3>Mixed vertical alignment</h3>
	<section class="demos">
    <div class="demos__header">
      <h4>Example</h4>
      <a class="code__action">
        <span class="icon icon__size--medium icon__color--action">
          <svg width="24px" height="24px" viewBox="0 0 24 24">
            <g fill="inherit">
                <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
            </g>
          </svg>
        </span>
      </a>
    </div>
		<div class="demos__body">

				<div class="grid grid__gutter grid__align--bottom">
					<div class="grid__item grid__item--top">
						<div class="demo-grid">Top aligned grid item</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum mollis velit non gravida venenatis. Praesent consequat lectus purus, ut scelerisque velit condimentum eu. Maecenas sagittis ante ut turpis varius interdum. Quisque tellus ipsum, eleifend non ipsum id, suscipit ultricies neque.</div>
					</div>
					<div class="grid__item grid__item--center">
						<div class="demo-grid">Bottom aligned grid item</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum mollis velit non gravida venenatis.</div>
					</div>
				</div>

		</div>
		<div class="demos__code">
			<div class="code__samples">
				<pre><code class="html">
&lt;div class=&quot;grid grid__gutter grid__align--bottom&quot;&gt;
	&lt;div class=&quot;grid__item grid__item--top&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;Top aligned grid item&lt;/div&gt;
	&lt;/div&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum mollis velit non gravida venenatis. Praesent consequat lectus purus, ut scelerisque velit condimentum eu. Maecenas sagittis ante ut turpis varius interdum. Quisque tellus ipsum, eleifend non ipsum id, suscipit ultricies neque.&lt;/div&gt;
	&lt;/div&gt;
	&lt;div class=&quot;grid__item grid__item--center&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;Bottom aligned grid item&lt;/div&gt;
	&lt;/div&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum mollis velit non gravida venenatis.&lt;/div&gt;
	&lt;/div&gt;
&lt;/div&gt;
        </code></pre>
			</div>
		</div>
	</section>
	<h3>Justify content center</h3>
	<section class="demos">
    <div class="demos__header">
      <h4>Example</h4>
      <a class="code__action">
        <span class="icon icon__size--medium icon__color--action">
          <svg width="24px" height="24px" viewBox="0 0 24 24">
            <g fill="inherit">
                <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
            </g>
          </svg>
        </span>
      </a>
    </div>
		<div class="demos__body">

				<div class="grid grid__gutter grid__align--justify-center">
					<div class="grid__item grid__item--1-6">
						<div class="demo-grid">Grid 1/6</div>
					</div>
					<div class="grid__item grid__item--1-6">
						<div class="demo-grid">Grid 1/6</div>
					</div>
					<div class="grid__item grid__item--1-6">
						<div class="demo-grid">Grid 1/6</div>
					</div>
				</div>

		</div>
		<div class="demos__code">
			<div class="code__samples">
				<pre><code class="html">
&lt;div class=&quot;grid grid__gutter grid__align--justify-center&quot;&gt;
	&lt;div class=&quot;grid__item grid__item--1-6&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;Grid 1/6&lt;/div&gt;
	&lt;/div&gt;
	&lt;div class=&quot;grid__item grid__item--1-6&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;Grid 1/6&lt;/div&gt;
	&lt;/div&gt;
	&lt;div class=&quot;grid__item grid__item--1-6&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;Grid 1/6&lt;/div&gt;
	&lt;/div&gt;
&lt;/div&gt;
        </code></pre>
			</div>
		</div>
	</section>
	<h3>Justify content right</h3>
	<section class="demos">
    <div class="demos__header">
      <h4>Example</h4>
      <a class="code__action">
        <span class="icon icon__size--medium icon__color--action">
          <svg width="24px" height="24px" viewBox="0 0 24 24">
            <g fill="inherit">
                <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
            </g>
          </svg>
        </span>
      </a>
    </div>
		<div class="demos__body">

				<div class="grid grid__gutter grid__align--justify-right">
					<div class="grid__item grid__item--1-6">
						<div class="demo-grid">Grid 1/6</div>
					</div>
					<div class="grid__item grid__item--1-6">
						<div class="demo-grid">Grid 1/6</div>
					</div>
					<div class="grid__item grid__item--1-6">
						<div class="demo-grid">Grid 1/6</div>
					</div>
				</div>

		</div>
		<div class="demos__code">
			<div class="code__samples">
				<pre><code class="html">
&lt;div class=&quot;grid grid__gutter grid__align--justify-right&quot;&gt;
	&lt;div class=&quot;grid__item grid__item--1-6&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;Grid 1/6&lt;/div&gt;
	&lt;/div&gt;
	&lt;div class=&quot;grid__item grid__item--1-6&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;Grid 1/6&lt;/div&gt;
	&lt;/div&gt;
	&lt;div class=&quot;grid__item grid__item--1-6&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;Grid 1/6&lt;/div&gt;
	&lt;/div&gt;
&lt;/div&gt;
        </code></pre>
			</div>
		</div>
	</section>
</section>
<section class="main__block">
	<h2>Responsiveness</h2>
	<section class="demos">
    <div class="demos__header">
      <h4>Example</h4>
      <a class="code__action">
        <span class="icon icon__size--medium icon__color--action">
          <svg width="24px" height="24px" viewBox="0 0 24 24">
            <g fill="inherit">
                <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
            </g>
          </svg>
        </span>
      </a>
    </div>
		<div class="demos__body">

				<div class="grid grid__gutter">
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 1</div>
					</div>
				</div>
				<div class="grid grid__gutter grid__1-2">
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 2</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 2</div>
					</div>
				</div>
				<div class="grid grid__gutter grid__1-3">
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 3</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 3</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 3</div>
					</div>
				</div>
				<div class="grid grid__gutter grid__1-4">
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 4</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 4</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 4</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 4</div>
					</div>
				</div>
				<div class="grid grid__gutter grid__1-5">
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 5</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 5</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 5</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 5</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 5</div>
					</div>
				</div>
				<div class="grid grid__gutter grid__1-6">
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 6</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 6</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 6</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 6</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 6</div>
					</div>
					<div class="grid__item">
						<div class="demo-grid">grid 1 / 6</div>
					</div>
				</div>

		</div>
		<div class="demos__code">
			<div class="code__samples">
				<pre><code class="html">
&lt;div class=&quot;grid grid__gutter&quot;&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;grid 1 / 1&lt;/div&gt;
	&lt;/div&gt;
&lt;/div&gt;
&lt;div class=&quot;grid grid__gutter grid__1-2&quot;&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;grid 1 / 2&lt;/div&gt;
	&lt;/div&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;grid 1 / 2&lt;/div&gt;
	&lt;/div&gt;
&lt;/div&gt;
&lt;div class=&quot;grid grid__gutter grid__1-3&quot;&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;grid 1 / 3&lt;/div&gt;
	&lt;/div&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;grid 1 / 3&lt;/div&gt;
	&lt;/div&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;grid 1 / 3&lt;/div&gt;
	&lt;/div&gt;
&lt;/div&gt;
&lt;div class=&quot;grid grid__gutter grid__1-4&quot;&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;grid 1 / 4&lt;/div&gt;
	&lt;/div&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;grid 1 / 4&lt;/div&gt;
	&lt;/div&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;grid 1 / 4&lt;/div&gt;
	&lt;/div&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;grid 1 / 4&lt;/div&gt;
	&lt;/div&gt;
&lt;/div&gt;
&lt;div class=&quot;grid grid__gutter grid__1-5&quot;&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;grid 1 / 5&lt;/div&gt;
	&lt;/div&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;grid 1 / 5&lt;/div&gt;
	&lt;/div&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;grid 1 / 5&lt;/div&gt;
	&lt;/div&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;grid 1 / 5&lt;/div&gt;
	&lt;/div&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;grid 1 / 5&lt;/div&gt;
	&lt;/div&gt;
&lt;/div&gt;
&lt;div class=&quot;grid grid__gutter grid__1-6&quot;&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;grid 1 / 6&lt;/div&gt;
	&lt;/div&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;grid 1 / 6&lt;/div&gt;
	&lt;/div&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;grid 1 / 6&lt;/div&gt;
	&lt;/div&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;grid 1 / 6&lt;/div&gt;
	&lt;/div&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;grid 1 / 6&lt;/div&gt;
	&lt;/div&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;grid 1 / 6&lt;/div&gt;
	&lt;/div&gt;
&lt;/div&gt;
        </code></pre>
			</div>
		</div>
	</section>
	<h3>Nestable sample responsive</h3>
	<section class="demos">
    <div class="demos__header">
      <h4>Example</h4>
      <a class="code__action">
        <span class="icon icon__size--medium icon__color--action">
          <svg width="24px" height="24px" viewBox="0 0 24 24">
            <g fill="inherit">
                <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
            </g>
          </svg>
        </span>
      </a>
    </div>
		<div class="demos__body">

				<div class="grid grid__gutter">
					<div class="grid__item">
						<div class="demo-grid">
							<div class="grid grid__gutter grid__1-2">
								<div class="grid__item">
									<div class="demo-grid">1/2</div>
								</div>
								<div class="grid__item">
									<div class="demo-grid">1/2</div>
								</div>
							</div>
						</div>
					</div>
				</div>

		</div>
		<div class="demos__code">
			<div class="code__samples">
				<pre><code class="html">
&lt;div class=&quot;grid grid__gutter&quot;&gt;
	&lt;div class=&quot;grid__item&quot;&gt;
		&lt;div class=&quot;demo-grid&quot;&gt;
			&lt;div class=&quot;grid grid__gutter grid__1-2&quot;&gt;
				&lt;div class=&quot;grid__item&quot;&gt;
					&lt;div class=&quot;demo-grid&quot;&gt;1/2&lt;/div&gt;
				&lt;/div&gt;
				&lt;div class=&quot;grid__item&quot;&gt;
					&lt;div class=&quot;demo-grid&quot;&gt;1/2&lt;/div&gt;
				&lt;/div&gt;
			&lt;/div&gt;
		&lt;/div&gt;
	&lt;/div&gt;
&lt;/div&gt;
        </code></pre>
			</div>
		</div>
	</section>
</section>
<section class="main__block">
	<h2>Full reference properties</h2>
	<section>
		<h3>Alignment items</h3>
		<div class="table__rounded-corners table__bordered">
			<table class="table table__easy">
				<thead>
					<tr>
						<th class="table__cell--width-33">className name</th>
						<th>Description</th>
					</tr>
				</thead>
				<tbody>
					<tr>
						<td><code>.grid__item--top</code></td>
						<td>This className aligns content to the top</td>
					</tr>
					<tr>
						<td><code>.grid__item--bottom</code></td>
						<td>This className aligns content to the bottom</td>
					</tr>
					<tr>
						<td><code>.grid__item--center</code></td>
						<td>This className aligns content to the center</td>
					</tr>
					<tr>
						<td><code>.grid__item--auto-size</code></td>
						<td>This className aligns content to the fullest available space</td>
					</tr>
				</tbody>
			</table>
		</div>
	</section>
	<section>
		<h3>Gutter</h3>
		<div class="table__rounded-corners table__bordered">
			<table class="table table__easy">
				<thead>
					<tr>
						<th class="table__cell--width-33">className name</th>
						<th>Description</th>
					</tr>
				</thead>
				<tbody>
					<tr>
						<td><code>.grid__gutter</code></td>
						<td><!-- react-text: 414 -->Sets up the default gutter space which is <!-- /react-text --><code>.75rem</code></td>
					</tr>
					<tr>
						<td><code>.grid__gutter--large</code></td>
						<td><!-- react-text: 420 -->Sets up the gutter space at <!-- /react-text --><code>1.5rem</code></td>
					</tr>
					<tr>
						<td><code>.grid__gutter--x-large</code></td>
						<td><!-- react-text: 426 -->Sets up the gutter space at <!-- /react-text --><code>2.6rem</code></td>
					</tr>
				</tbody>
			</table>
		</div>
	</section>
	<section>
		<h3>Alignment grid</h3>
		<div class="table__rounded-corners table__bordered">
			<table class="table table__easy">
				<thead>
					<tr>
						<th class="table__cell--width-33">className name</th>
						<th>Description</th>
					</tr>
				</thead>
				<tbody>
					<tr>
						<td><code>.grid__align--top</code></td>
						<td><!-- react-text: 441 -->Aligns all <!-- /react-text --><code>grid__item</code><!-- react-text: 443 -->'s to the top<!-- /react-text --></td>
					</tr>
					<tr>
						<td><code>.grid__align--bottom</code></td>
						<td><!-- react-text: 448 -->Aligns all <!-- /react-text --><code>grid__item</code><!-- react-text: 450 -->'s to the bottom<!-- /react-text --></td>
					</tr>
					<tr>
						<td><code>.grid__align--center</code></td>
						<td><!-- react-text: 455 -->Aligns all <!-- /react-text --><code>grid__item</code><!-- react-text: 457 -->'s to the center<!-- /react-text --></td>
					</tr>
					<tr>
						<td><code>.grid__align--justify-center</code></td>
						<td><!-- react-text: 462 -->Aligns all <!-- /react-text --><code>grid__item</code><!-- react-text: 464 -->'s distributed in the center<!-- /react-text --></td>
					</tr>
					<tr>
						<td><code>.grid__align--justify-right</code></td>
						<td><!-- react-text: 469 -->Aligns all <!-- /react-text --><code>grid__item</code><!-- react-text: 471 -->'s to the right<!-- /react-text --></td>
					</tr>
				</tbody>
			</table>
		</div>
	</section>
	<section>
		<h3>Make it flex</h3>
		<div class="table__rounded-corners table__bordered">
			<table class="table table__easy">
				<thead>
					<tr>
						<th class="table__cell--width-33">className name</th>
						<th>Description</th>
					</tr>
				</thead>
				<tbody>
					<tr>
						<td><code>.grid__flex</code></td>
						<td>Makes all the elements maintain equal heights even if of the elements is longer than the other.</td>
					</tr>
				</tbody>
			</table>
		</div>
	</section>
</section>
