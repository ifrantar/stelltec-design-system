---
layout: page
navigation : main
title : Modals
permalink: /modals/
---

<header class="main__header">
  <h1 class="main__header--header">Modals</h1>
  <p>Modals—or its other names such as alerts, prompts or dialogs—are meant to give the user contextual functionality based on actions the users might be performing on the page.</p>
</header>

<section class="main__block">
  <h2>About Modals</h2>
  <p>Modals are essentially a <a href="/panels">Panel component</a> wrapped into a Dialog component to give it the highest up layer unabling the user to do anything else until the action of the dialog window have taken place.</p>
  <section class="demos">
    <div class="demos__header">
      <h4>Test</h4><a class="code__action"><span class="icon icon__size--medium icon__color--action"><svg height="24px" viewbox="0 0 24 24" width="24px">
      <g fill="inherit">
        <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
      </g></svg></span></a>
    </div>
    <div class="demos__body">

        <div class="dialog" style="position: static; padding: 24px; background: white;">
          <div class="panel" style="position: static; transform: none; margin: auto;">
            <div class="panel__header">
              <h3>Create user</h3>
              <div class="panel__header--actions-right">
                <div class="panel__header--actions-item">
                  <a href="#"><i class="material-icons">close</i></a>
                </div>
              </div>
            </div>
            <div class="panel__body">
              <div class="banner banner--success banner--inline u__margin-bottom--medium">
                  <div class="banner__content">
                    <p>Please note that the user details are provided by the Google Authenticator.</p>
                  </div>
              </div>
              <ul class="u__margin-bottom--0">
                <li class="u__margin-bottom--medium">
                  <label>Enter user</label>
                  <input class="f__textfield f__textfield--size-m"  type="text" value="">
                </li>
                <li class="">
                  <label>Enter user email address</label>
                  <input class="f__textfield f__textfield--size-m" type="email" value="">
                </li>
              </ul>
            </div>
            <div class="panel__footer panel__footer--buttons">
              <div class="btn__group--right">
                <a class="btn btn__neutral btn__neutral--outline btn__size-m" href="application-preferences.html">Cancel</a><a class="btn btn__primary btn__primary btn__size-m" href="application-preferences.html">Save</a>
              </div>
            </div>
          </div>
        </div>

    </div>
    <div class="demos__code">
      <div class="code__samples">
        <pre><code class="html">
&lt;div class=&quot;dialog&quot;&gt;
  &lt;div class=&quot;panel&quot;&gt;
    &lt;div class=&quot;panel__header&quot;&gt;
      &lt;h3&gt;Create user&lt;/h3&gt;
      &lt;div class=&quot;panel__header--actions-right&quot;&gt;
        &lt;div class=&quot;panel__header--actions-item&quot;&gt;
          &lt;a href=&quot;#&quot;&gt;&lt;i class=&quot;material-icons&quot;&gt;close&lt;/i&gt;&lt;/a&gt;
        &lt;/div&gt;
      &lt;/div&gt;
    &lt;/div&gt;
    &lt;div class=&quot;panel__body&quot;&gt;
      &lt;div class=&quot;banner banner--success banner--inline u__margin-bottom--medium&quot;&gt;
          &lt;div class=&quot;banner__content&quot;&gt;
            &lt;p&gt;Please note that the user details are provided by the Google Authenticator.&lt;/p&gt;
          &lt;/div&gt;
      &lt;/div&gt;
      &lt;ul class=&quot;u__margin-bottom--0&quot;&gt;
        &lt;li class=&quot;u__margin-bottom--medium&quot;&gt;
          &lt;label&gt;Enter user&lt;/label&gt;
          &lt;input class=&quot;f__textfield f__textfield--size-m&quot;  type=&quot;text&quot; value=&quot;&quot;&gt;
        &lt;/li&gt;
        &lt;li class=&quot;&quot;&gt;
          &lt;label&gt;Enter user email address&lt;/label&gt;
          &lt;input class=&quot;f__textfield f__textfield--size-m&quot; type=&quot;email&quot; value=&quot;&quot;&gt;
        &lt;/li&gt;
      &lt;/ul&gt;
    &lt;/div&gt;
    &lt;div class=&quot;panel__footer panel__footer--buttons&quot;&gt;
      &lt;div class=&quot;btn__group--right&quot;&gt;
        &lt;a class=&quot;btn btn__neutral btn__neutral--outline btn__size-m&quot; href=&quot;application-preferences.html&quot;&gt;Cancel&lt;/a&gt;&lt;a class=&quot;btn btn__primary btn__primary btn__size-m&quot; href=&quot;application-preferences.html&quot;&gt;Save&lt;/a&gt;
      &lt;/div&gt;
    &lt;/div&gt;
  &lt;/div&gt;
&lt;/div&gt;
        </code></pre>
      </div>
    </div>
  </section>
  <p>The modal has a faint black overlay when opened. I removed it from the example for showing purposes.</p>
</section>
