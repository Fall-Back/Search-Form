Search-Form
===========

Simple pattern for an expanding search form.

[Demo](http://lab.gridlight-design.co.uk/fallback/search-form.html)


Basic Example
-------------

~~~~~
&lt;form action="#search" id="searchform" class="search-form" method="GET"&gt;
    &lt;input type="search" class="search-form__field" id="search" placeholder="Search" name="s" value="" aria-label="Search" /&gt;
    &lt;button class="search-form__submit" type="submit"&gt;
        &lt;span&gt;
            &lt;svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="20" height="20" viewBox="0 0 20 20"&gt;
                &lt;path fill="#333333" d="M12.917 11.667h-0.662l-0.229-0.229c0.817-0.946 1.308-2.175 1.308-3.521 0-2.992-2.425-5.417-5.417-5.417s-5.417 2.425-5.417 5.417 2.425 5.417 5.417 5.417c1.346 0 2.575-0.492 3.521-1.304l0.229 0.229v0.658l4.167 4.158 1.242-1.242-4.158-4.167zM7.917 11.667c-2.071 0-3.75-1.679-3.75-3.75s1.679-3.75 3.75-3.75 3.75 1.679 3.75 3.75-1.679 3.75-3.75 3.75z"&gt;&lt;/path&gt;
                &lt;text y="-1"&gt;Search&lt;/text&gt;
            &lt;/svg&gt;
        &lt;/span&gt;
    &lt;/button&gt;
&lt;/form&gt;
~~~~~