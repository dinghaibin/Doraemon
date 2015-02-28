<article class="markdown-body entry-content" itemprop="mainContentOfPage"><h1>
<a id="user-content-bootstrap" class="anchor" href="#bootstrap" aria-hidden="true"><span class="octicon octicon-link"></span></a><a href="http://getbootstrap.com">Bootstrap</a>
</h1>

<p><a href="https://camo.githubusercontent.com/a36d7a196c01d24e67b1425423e041b7d613ad8f/68747470733a2f2f696d672e736869656c64732e696f2f626f7765722f762f626f6f7473747261702e7376673f7374796c653d666c6174" target="_blank"><img src="https://camo.githubusercontent.com/a36d7a196c01d24e67b1425423e041b7d613ad8f/68747470733a2f2f696d672e736869656c64732e696f2f626f7765722f762f626f6f7473747261702e7376673f7374796c653d666c6174" alt="Bower version" data-canonical-src="https://img.shields.io/bower/v/bootstrap.svg?style=flat" style="max-width:100%;"></a>
<a href="https://www.npmjs.com/package/bootstrap"><img src="https://camo.githubusercontent.com/36d01b06be22f14204a45ccd0c55698937bf20de/68747470733a2f2f696d672e736869656c64732e696f2f6e706d2f762f626f6f7473747261702e7376673f7374796c653d666c6174" alt="npm version" data-canonical-src="https://img.shields.io/npm/v/bootstrap.svg?style=flat" style="max-width:100%;"></a>
<a href="https://travis-ci.org/twbs/bootstrap"><img src="https://camo.githubusercontent.com/ca6e77a459a8daf05a8567313d723301a6535cab/68747470733a2f2f696d672e736869656c64732e696f2f7472617669732f747762732f626f6f7473747261702f6d61737465722e7376673f7374796c653d666c6174" alt="Build Status" data-canonical-src="https://img.shields.io/travis/twbs/bootstrap/master.svg?style=flat" style="max-width:100%;"></a>
<a href="https://david-dm.org/twbs/bootstrap#info=devDependencies"><img src="https://camo.githubusercontent.com/4f56942b1a82afb54c714281ccb3b8574a548fae/68747470733a2f2f696d672e736869656c64732e696f2f64617669642f6465762f747762732f626f6f7473747261702e7376673f7374796c653d666c6174" alt="devDependency Status" data-canonical-src="https://img.shields.io/david/dev/twbs/bootstrap.svg?style=flat" style="max-width:100%;"></a>
<a href="https://saucelabs.com/u/bootstrap"><img src="https://camo.githubusercontent.com/3e0aa93ee06f55b9d19d2209bd12bec39cc40cec/68747470733a2f2f73617563656c6162732e636f6d2f62726f777365722d6d61747269782f626f6f7473747261702e737667" alt="Selenium Test Status" data-canonical-src="https://saucelabs.com/browser-matrix/bootstrap.svg" style="max-width:100%;"></a></p>

<p>Bootstrap is a sleek, intuitive, and powerful front-end framework for faster and easier web development, created by <a href="https://twitter.com/mdo">Mark Otto</a> and <a href="https://twitter.com/fat">Jacob Thornton</a>, and maintained by the <a href="https://github.com/orgs/twbs/people">core team</a> with the massive support and involvement of the community.</p>

<p>To get started, check out <a href="http://getbootstrap.com">http://getbootstrap.com</a>!</p>

<h2>
<a id="user-content-table-of-contents" class="anchor" href="#table-of-contents" aria-hidden="true"><span class="octicon octicon-link"></span></a>Table of contents</h2>

<ul class="task-list">
<li><a href="#quick-start">Quick start</a></li>
<li><a href="#bugs-and-feature-requests">Bugs and feature requests</a></li>
<li><a href="#documentation">Documentation</a></li>
<li><a href="#contributing">Contributing</a></li>
<li><a href="#community">Community</a></li>
<li><a href="#versioning">Versioning</a></li>
<li><a href="#creators">Creators</a></li>
<li><a href="#copyright-and-license">Copyright and license</a></li>
</ul>

<h2>
<a id="user-content-quick-start" class="anchor" href="#quick-start" aria-hidden="true"><span class="octicon octicon-link"></span></a>Quick start</h2>

<p>Four quick start options are available:</p>

<ul class="task-list">
<li>
<a href="https://github.com/twbs/bootstrap/archive/v3.3.2.zip">Download the latest release</a>.</li>
<li>Clone the repo: <code>git clone https://github.com/twbs/bootstrap.git</code>.</li>
<li>Install with <a href="http://bower.io">Bower</a>: <code>bower install bootstrap</code>.</li>
<li>Install with <a href="https://www.npmjs.com">npm</a>: <code>npm install bootstrap</code>.</li>
<li>Install with <a href="https://www.meteor.com/">Meteor</a>: <code>meteor add twbs:bootstrap</code>.</li>
</ul>

<p>Read the <a href="http://getbootstrap.com/getting-started/">Getting started page</a> for information on the framework contents, templates and examples, and more.</p>

<h3>
<a id="user-content-whats-included" class="anchor" href="#whats-included" aria-hidden="true"><span class="octicon octicon-link"></span></a>What's included</h3>

<p>Within the download you'll find the following directories and files, logically grouping common assets and providing both compiled and minified variations. You'll see something like this:</p>

<pre><code>bootstrap/
├── css/
│   ├── bootstrap.css
│   ├── bootstrap.css.map
│   ├── bootstrap.min.css
│   ├── bootstrap-theme.css
│   ├── bootstrap-theme.css.map
│   └── bootstrap-theme.min.css
├── js/
│   ├── bootstrap.js
│   └── bootstrap.min.js
└── fonts/
    ├── glyphicons-halflings-regular.eot
    ├── glyphicons-halflings-regular.svg
    ├── glyphicons-halflings-regular.ttf
    ├── glyphicons-halflings-regular.woff
    └── glyphicons-halflings-regular.woff2
</code></pre>

<p>We provide compiled CSS and JS (<code>bootstrap.*</code>), as well as compiled and minified CSS and JS (<code>bootstrap.min.*</code>). CSS <a href="https://developers.google.com/chrome-developer-tools/docs/css-preprocessors">source maps</a> (<code>bootstrap.*.map</code>) are available for use with certain browsers' developer tools. Fonts from Glyphicons are included, as is the optional Bootstrap theme.</p>

<h2>
<a id="user-content-bugs-and-feature-requests" class="anchor" href="#bugs-and-feature-requests" aria-hidden="true"><span class="octicon octicon-link"></span></a>Bugs and feature requests</h2>

<p>Have a bug or a feature request? Please first read the <a href="https://github.com/twbs/bootstrap/blob/master/CONTRIBUTING.md#using-the-issue-tracker">issue guidelines</a> and search for existing and closed issues. If your problem or idea is not addressed yet, <a href="https://github.com/twbs/bootstrap/issues/new">please open a new issue</a>.</p>

<h2>
<a id="user-content-documentation" class="anchor" href="#documentation" aria-hidden="true"><span class="octicon octicon-link"></span></a>Documentation</h2>

<p>Bootstrap's documentation, included in this repo in the root directory, is built with <a href="http://jekyllrb.com">Jekyll</a> and publicly hosted on GitHub Pages at <a href="http://getbootstrap.com">http://getbootstrap.com</a>. The docs may also be run locally.</p>

<h3>
<a id="user-content-running-documentation-locally" class="anchor" href="#running-documentation-locally" aria-hidden="true"><span class="octicon octicon-link"></span></a>Running documentation locally</h3>

<ol class="task-list">
<li>If necessary, <a href="http://jekyllrb.com/docs/installation">install Jekyll</a> (requires v2.5.x).

<ul class="task-list">
<li>
<strong>Windows users:</strong> Read <a href="http://jekyll-windows.juthilo.com/">this unofficial guide</a> to get Jekyll up and running without problems.</li>
</ul>
</li>
<li>Install the Ruby-based syntax highlighter, <a href="https://github.com/jneen/rouge">Rouge</a>, with <code>gem install rouge</code>.</li>
<li>From the root <code>/bootstrap</code> directory, run <code>jekyll serve</code> in the command line.</li>
<li>Open <a href="http://localhost:9001">http://localhost:9001</a> in your browser, and voilà.</li>
</ol>

<p>Learn more about using Jekyll by reading its <a href="http://jekyllrb.com/docs/home/">documentation</a>.</p>

<h3>
<a id="user-content-documentation-for-previous-releases" class="anchor" href="#documentation-for-previous-releases" aria-hidden="true"><span class="octicon octicon-link"></span></a>Documentation for previous releases</h3>

<p>Documentation for v2.3.2 has been made available for the time being at <a href="http://getbootstrap.com/2.3.2/">http://getbootstrap.com/2.3.2/</a> while folks transition to Bootstrap 3.</p>

<p><a href="https://github.com/twbs/bootstrap/releases">Previous releases</a> and their documentation are also available for download.</p>

<h2>
<a id="user-content-contributing" class="anchor" href="#contributing" aria-hidden="true"><span class="octicon octicon-link"></span></a>Contributing</h2>

<p>Please read through our <a href="https://github.com/twbs/bootstrap/blob/master/CONTRIBUTING.md">contributing guidelines</a>. Included are directions for opening issues, coding standards, and notes on development.</p>

<p>Moreover, if your pull request contains JavaScript patches or features, you must include relevant unit tests. All HTML and CSS should conform to the <a href="https://github.com/mdo/code-guide">Code Guide</a>, maintained by <a href="https://github.com/mdo">Mark Otto</a>.</p>

<p>Editor preferences are available in the <a href="https://github.com/twbs/bootstrap/blob/master/.editorconfig">editor config</a> for easy use in common text editors. Read more and download plugins at <a href="http://editorconfig.org">http://editorconfig.org</a>.</p>

<h2>
<a id="user-content-community" class="anchor" href="#community" aria-hidden="true"><span class="octicon octicon-link"></span></a>Community</h2>

<p>Keep track of development and community news.</p>

<ul class="task-list">
<li>Follow <a href="https://twitter.com/getbootstrap">@getbootstrap on Twitter</a>.</li>
<li>Read and subscribe to <a href="http://blog.getbootstrap.com">The Official Bootstrap Blog</a>.</li>
<li>Chat with fellow Bootstrappers in IRC. On the <code>irc.freenode.net</code> server, in the <code>##bootstrap</code> channel.</li>
<li>Implementation help may be found at Stack Overflow (tagged <a href="http://stackoverflow.com/questions/tagged/twitter-bootstrap-3"><code>twitter-bootstrap-3</code></a>).</li>
<li>Developers should use the keyword <code>bootstrap</code> on packages which modify or add to the functionality of Bootstrap when distributing through <a href="https://www.npmjs.com/browse/keyword/twbs-bootstrap">npm</a> or similar delivery mechanisms for maximum discoverability.</li>
</ul>

<h2>
<a id="user-content-versioning" class="anchor" href="#versioning" aria-hidden="true"><span class="octicon octicon-link"></span></a>Versioning</h2>

<p>For transparency into our release cycle and in striving to maintain backward compatibility, Bootstrap is maintained under <a href="http://semver.org/">the Semantic Versioning guidelines</a>. Sometimes we screw up, but we'll adhere to those rules whenever possible.</p>

<h2>
<a id="user-content-creators" class="anchor" href="#creators" aria-hidden="true"><span class="octicon octicon-link"></span></a>Creators</h2>

<p><strong>Mark Otto</strong></p>

<ul class="task-list">
<li><a href="https://twitter.com/mdo">https://twitter.com/mdo</a></li>
<li><a href="https://github.com/mdo">https://github.com/mdo</a></li>
</ul>

<p><strong>Jacob Thornton</strong></p>

<ul class="task-list">
<li><a href="https://twitter.com/fat">https://twitter.com/fat</a></li>
<li><a href="https://github.com/fat">https://github.com/fat</a></li>
</ul>

<h2>
<a id="user-content-copyright-and-license" class="anchor" href="#copyright-and-license" aria-hidden="true"><span class="octicon octicon-link"></span></a>Copyright and license</h2>

<p>Code and documentation copyright 2011-2015 Twitter, Inc. Code released under <a href="https://github.com/twbs/bootstrap/blob/master/LICENSE">the MIT license</a>. Docs released under <a href="https://github.com/twbs/bootstrap/blob/master/docs/LICENSE">Creative Commons</a>.</p>
</article>
