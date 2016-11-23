{"template":"component.html","title":"Tabs","demo":"<h4>Basic</h4>\n\n<!-- START: FIRSTDEMO -->\n\n<style>\n\t.tabs { overflow: hidden; }\n</style>\n\n<div class=\"demo_container\">\n\t<div class=\"demo_example\">\n\t\t<div role=\"tablist\">\n\t\t\t<nav class=\"tabs\">\n\t\t\t\t<a href=\"#tab-1-1\" class=\"tab js-tabs\" data-tabs-group=\"tab-1\">One</a>\n\t\t\t\t<a href=\"#tab-1-2\" class=\"tab js-tabs\" data-tabs-group=\"tab-1\" data-tabs-active=\"true\">Two</a>\n\t\t\t\t<a href=\"#tab-1-3\" class=\"tab js-tabs\" data-tabs-group=\"tab-1\">Three</a>\n\t\t\t</nav>\n\t\t\t<div class=\"tab_content\" id=\"tab-1-1\">\n\t\t\t\t<p>Praesent commodo cursus magna, vel scelerisque nisl consectetur et. Donec ullamcorper nulla non metus auctor fringilla. Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum.</p>\n\t\t\t</div>\n\t\t\t<div class=\"tab_content\" id=\"tab-1-2\">\n\t\t\t\t<p>Nullam quis risus eget urna mollis ornare vel eu leo. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent commodo cursus magna, vel scelerisque nisl consectetur et. Praesent commodo cursus magna, vel scelerisque nisl consectetur et.</p>\n\t\t\t</div>\n\t\t\t<div class=\"tab_content\" id=\"tab-1-3\">\n\t\t\t\t<p>Donec id elit non mi porta gravida at eget metus. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Morbi leo risus, porta ac consectetur ac, vestibulum at eros.</p>\n\t\t\t</div>\n\t\t</div>\n\t</div>\n\t<div class=\"demo_code\">\n\t\t<pre><code class=\"language-html\">&lt;nav class=&quot;tabs_container&quot;&gt;\n&Tab;&lt;a href=&quot;#tab-1&quot; class=&quot;tabs&quot; data-tabs-group=&quot;tab_group&quot; data-tabs-active=&quot;true&quot;&gt;One&lt;/a&gt;\n&Tab;&lt;a href=&quot;#tab-2&quot; class=&quot;tabs&quot; data-tabs-group=&quot;tab_group&quot;&gt;Two&lt;/a&gt;\n&Tab;&lt;a href=&quot;#tab-3&quot; class=&quot;tabs&quot; data-tabs-group=&quot;tab_group&quot;&gt;Three&lt;/a&gt;\n&lt;/nav&gt;\n&lt;div class=&quot;tab_content&quot; id=&quot;tab-1&quot;&gt;\n&Tab;...\n&lt;/div&gt;\n&lt;div class=&quot;tab_content&quot; id=&quot;tab-1&quot;&gt;\n&Tab;...\n&lt;/div&gt;\n&lt;div class=&quot;tab_content&quot; id=&quot;tab-1&quot;&gt;\n&Tab;...\n&lt;/div&gt;</code></pre>\n\t\t<pre><code class=\"language-javascript\">$(\".tabs\").tabs();</code></pre>\n\t</div>\n</div>\n\n<!-- END: FIRSTDEMO -->\n\n<h4>Mobile Max Width</h4>\n<div class=\"demo_container\">\n\t<div class=\"demo_example\">\n\t\t<div role=\"tablist\">\n\t\t\t<nav class=\"tabs\">\n\t\t\t\t<a href=\"#tab-2-1\" class=\"tab js-tabs\" data-tabs-group=\"tab-2\" data-tabs-options='{\"mobileMaxWidth\":\"500px\"}'>One</a>\n\t\t\t\t<a href=\"#tab-2-2\" class=\"tab js-tabs\" data-tabs-group=\"tab-2\" data-tabs-options='{\"mobileMaxWidth\":\"500px\"}'>Two</a>\n\t\t\t\t<a href=\"#tab-2-3\" class=\"tab js-tabs\" data-tabs-group=\"tab-2\" data-tabs-options='{\"mobileMaxWidth\":\"500px\"}'>Three</a>\n\t\t\t</nav>\n\t\t\t<div class=\"tab_content\" id=\"tab-2-1\">\n\t\t\t\t<p>Praesent commodo cursus magna, vel scelerisque nisl consectetur et. Donec ullamcorper nulla non metus auctor fringilla. Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum.</p>\n\t\t\t</div>\n\t\t\t<div class=\"tab_content\" id=\"tab-2-2\">\n\t\t\t\t<p>Nullam quis risus eget urna mollis ornare vel eu leo. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent commodo cursus magna, vel scelerisque nisl consectetur et. Praesent commodo cursus magna, vel scelerisque nisl consectetur et.</p>\n\t\t\t</div>\n\t\t\t<div class=\"tab_content\" id=\"tab-2-3\">\n\t\t\t\t<p>Donec id elit non mi porta gravida at eget metus. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Morbi leo risus, porta ac consectetur ac, vestibulum at eros.</p>\n\t\t\t</div>\n\t\t</div>\n\t</div>\n\t<div class=\"demo_code\">\n\t\t<pre><code class=\"language-html\">&lt;nav class=&quot;tabs_container&quot;&gt;\n&Tab;&lt;a href=&quot;#tab-1&quot; class=&quot;tabs&quot; data-tabs-group=&quot;tab_group&quot; data-tabs-active=&quot;true&quot;&gt;One&lt;/a&gt;\n&Tab;&lt;a href=&quot;#tab-2&quot; class=&quot;tabs&quot; data-tabs-group=&quot;tab_group&quot;&gt;Two&lt;/a&gt;\n&Tab;&lt;a href=&quot;#tab-3&quot; class=&quot;tabs&quot; data-tabs-group=&quot;tab_group&quot;&gt;Three&lt;/a&gt;\n&lt;/nav&gt;\n&lt;div class=&quot;tab_content&quot; id=&quot;tab-1&quot;&gt;\n&Tab;...\n&lt;/div&gt;\n&lt;div class=&quot;tab_content&quot; id=&quot;tab-1&quot;&gt;\n&Tab;...\n&lt;/div&gt;\n&lt;div class=&quot;tab_content&quot; id=&quot;tab-1&quot;&gt;\n&Tab;...\n&lt;/div&gt;</code></pre>\n\t\t<pre><code class=\"language-javascript\">$(\".tabs\").tabs({\n\tmobileMaxWidth: 500\n});</code></pre>\n\t</div>\n</div>\n\n<h4>No Theme</h4>\n<div class=\"demo_container\">\n\t<div class=\"demo_example\">\n\t\t<div role=\"tablist\">\n\t\t\t<nav class=\"tabs\">\n\t\t\t\t<a href=\"#tab-3-1\" class=\"tab js-tabs\" data-tabs-group=\"tab-3\" data-tabs-options='{\"theme\":\"\"}'>One</a>\n\t\t\t\t<a href=\"#tab-3-2\" class=\"tab js-tabs\" data-tabs-group=\"tab-3\" data-tabs-options='{\"theme\":\"\"}'>Two</a>\n\t\t\t\t<a href=\"#tab-3-3\" class=\"tab js-tabs\" data-tabs-group=\"tab-3\" data-tabs-options='{\"theme\":\"\"}'>Three</a>\n\t\t\t</nav>\n\t\t\t<div class=\"tab_content\" id=\"tab-3-1\">\n\t\t\t\t<p>Praesent commodo cursus magna, vel scelerisque nisl consectetur et. Donec ullamcorper nulla non metus auctor fringilla. Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum.</p>\n\t\t\t</div>\n\t\t\t<div class=\"tab_content\" id=\"tab-3-2\">\n\t\t\t\t<p>Nullam quis risus eget urna mollis ornare vel eu leo. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent commodo cursus magna, vel scelerisque nisl consectetur et. Praesent commodo cursus magna, vel scelerisque nisl consectetur et.</p>\n\t\t\t</div>\n\t\t\t<div class=\"tab_content\" id=\"tab-3-3\">\n\t\t\t\t<p>Donec id elit non mi porta gravida at eget metus. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Morbi leo risus, porta ac consectetur ac, vestibulum at eros.</p>\n\t\t\t</div>\n\t\t</div>\n\t</div>\n\t<div class=\"demo_code\">\n\t\t<pre><code class=\"language-html\">&lt;nav class=&quot;tabs_container&quot;&gt;\n&Tab;&lt;a href=&quot;#tab-1&quot; class=&quot;tabs&quot; data-tabs-group=&quot;tab_group&quot; data-tabs-active=&quot;true&quot;&gt;One&lt;/a&gt;\n&Tab;&lt;a href=&quot;#tab-2&quot; class=&quot;tabs&quot; data-tabs-group=&quot;tab_group&quot;&gt;Two&lt;/a&gt;\n&Tab;&lt;a href=&quot;#tab-3&quot; class=&quot;tabs&quot; data-tabs-group=&quot;tab_group&quot;&gt;Three&lt;/a&gt;\n&lt;/nav&gt;\n&lt;div class=&quot;tab_content&quot; id=&quot;tab-1&quot;&gt;\n&Tab;...\n&lt;/div&gt;\n&lt;div class=&quot;tab_content&quot; id=&quot;tab-1&quot;&gt;\n&Tab;...\n&lt;/div&gt;\n&lt;div class=&quot;tab_content&quot; id=&quot;tab-1&quot;&gt;\n&Tab;...\n&lt;/div&gt;</code></pre>\n\t\t<pre><code class=\"language-javascript\">$(\".tabs\").tabs({\n\ttheme: \"\"\n});</code></pre>\n\t</div>\n</div>\n","asset_root":"../","year":2016}

 #Tabs Demo
<p class="back_link"><a href="https://formstone.it/components/tabs">View Documentation</a></p>