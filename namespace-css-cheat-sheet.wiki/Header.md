Namespace Header
--

Ini adalah document untuk cheat sheet namespace style header. 

Header tag default. 
<pre>
    &lt;header id="ro-header"&gt;
        &lt;!--tag html in here--&gt;
    &lt;/header&gt;
</pre>

Main menu in header

<pre>
    &lt;header id="ro-header"&gt;
        &lt;!--main menu--&gt;
        &lt;ul class="ro-nav ro-nav__primary"&gt;
            &lt;li&gt;&lt;a href="#" class="ro-nav__item ro-active"&gt;Menu 1&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href="#" class="ro-nav__item"&gt;Menu 2&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href="#" class="ro-nav__item"&gt;Menu 3&lt;/a&gt;&lt;/li&gt;
            &lt;li class="ro-nav__dropdown ro-open"&gt;
                &lt;ul&gt;
                    &lt;li"&gt;&lt;li&gt;&lt;a class="ro-active" href="#"&gt;Sub menu 1&lt;/a&gt;&lt;/li&gt;
                    &lt;li"&gt;&lt;li&gt;&lt;a href="#"&gt;Sub menu 2&lt;/a&gt;&lt;/li&gt;
                    &lt;li"&gt;&lt;li&gt;&lt;a href="#"&gt;Sub menu 3&lt;/a&gt;&lt;/li&gt;
                &lt;/ul&gt;
            &lt;li&gt;
        &lt;/ul&gt;
    &lt;/header&gt;
</pre>