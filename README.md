# Bilge Theme

```css
/* Written in November 2020 by David Blue for bilge.world.

Last updated `03162023-071333`

- I've finally just given this theme its own repository: https://github.com/extratone/bilge-theme

Sorry that took me so long!

---

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <https://unlicense.org>

*/

// As it stands, this theme will pull font assets from my "private" Adobe Typekit project - which is certainly fine with me for preview purposes, especially - but it's probably advisable you source your own solution.

@import url('https://use.typekit.net/kst2rrh.css');

body {
    font-family: adobe-caslon-pro, serif !important;
    font-weight: 400;
    font-style: normal;
    background-color: #FFF4E6;
}

/* old background-color: #f2f2f2 */

#blog-title a {
    font-family: proxima-nova-condensed, sans-serif;
    font-weight: 900;
    font-style: normal;
    /* font-style:bold !important; */
    color: #00006b;
}

header nav a {
    font-family: proxima-nova-condensed, sans-serif !important;
    font-weight: 900;
    font-size: 1.2em;
}

header p.description {
    /* font-style: italic; */
    font-family: proxima-nova-condensed, sans-serif !important;
    font-weight: 700;
    line-height: 200% !important;
    color: #00006b !important;
    font-size: 1em;
    margin-left: inherit;
    margin-right: inherit;
}

body#collection header {
    margin-bottom: 1em !important;
}


header nav a {
    color: #00006b;
    font-family: proxima-nova-condensed, sans-serif;
    font-weight: 900;
    /* margin-bottom: 1em; */
}

body,
article {
    font-family: adobe-caslon-pro, serif !important;
    font-weight: 400;
    line-height: 155%;
    font-size: 1.1em !important;
    color: #000001;
    padding-left: 0.5rem;
    padding-right: 0.5rem;
    /* margin-top:1rem !important; */
}


body,
article a:link {
    color: #00006b;
}

body,
article a:visited {
    color: #FF0000;
}

h1 {
    color: #00006b !important;
    font-family: proxima-nova-condensed, sans-serif;
    font-weight: 900;
    font-size: 2em !important;
}

h2 {
    color: #00006b !important;
    font-family: proxima-nova-condensed, sans-serif;
    font-weight: 700;
    font-size: 1.4em !important;
}

h3 {
    color: #4078f2 !important;
    font-family: proxima-nova-extra-condensed, sans-serif;
    font-weight: 600;
    font-size: 1.3em !important;
}

h4 {
    color: #f43f32 !important;
    font-family: proxima-nova-condensed, sans-serif;
    font-weight: 400;
    font-size: 1em !important;
}

h5 {
    color: #662545 !important;
    font-family: proxima-nova-condensed, sans-serif;
    font-weight: 400;
    font-size: 1em !important;
}

h6 {
    color: #80808C !important;
    font-family: proxima-nova-condensed, sans-serif;
    font-weight: 400;
    font-size: .85em !important;
}

li {
    color: #80808C !important;
    font-family: proxima-nova-condensed, sans-serif;
    font-weight: 400;
    font-size: .85em !important;
}

code {
    /* background-color:#f7ff85 !important; */
    /* border: 1px solid #da2573 !important;
    border-radius: 1px !important; */
    font-size: 0.85em !important;
    color: #1c0021 !important;
    font-family: proxima-nova-condensed, sans-serif;
    font-weight: 400;
    /* padding: 0px 0px 0px 0px !important; */
}

body #post pre, body#collection pre, body#post pre, body#subpage pre {
    background: #FFFdeb; !important;
    border: 1px solid #da2573 !important;
    border-radius: 1px !important;
    font-size: 0.85em !important;
    color: #1c0021 !important;
    font-family: proxima-nova-condensed, sans-serif;
    font-weight: 400;
    /* padding: 0px 0px 0px 0px !important; */
}

.post-title a:visited,
.post-title a:link {
    font-family: proxima-nova-condensed, sans-serif !important;
    font-weight: 900;
    color: #00006b !important;
    font-size: 1.7rem !important;
}

body#post article time.dt-published,
body#subpage article time.dt-published {
    font-family: proxima-nova-condensed, sans-serif !important;
    color: #00006b !important;
    font-size: 1rem !important;
}

body footer nav {
    font-family: proxima-nova-condensed, sans-serif !important;
    color: #00006b;
}

blockquote {
    font-family: proxima-nova-condensed, sans-serif;
    font-weight: 400;
    color: #333333 !important;
    border-left: 2.5px solid #00006b !important;
}

table {
    background-color: #FFFdeb !important;
    font-size: 0.8em !important;
    line-height: 1.2em;
    color: #1c0021 !important;
    font-family: proxima-nova-condensed, sans-serif;
    font-weight: 400;
    border: 1px solid #f43f32 !important;
    border-radius: 1px !important;
}

article table td, article table th {
    border: 1px solid !important;
    border-color: #da2573 !important;
}


.gist {
    font-family: proxima-nova-condensed, sans-serif !important;
    font-weight: 400 !important;
    font-size: 18px !important;
}

.gist .gist-meta {
    font-family: proxima-nova-extra-condensed, sans-serif !important;
    font-weight: 600 !important;
    color: #1c0021 !important;
}

.gist, .gist article, .gist article p {
    font-family: proxima-nova-condensed, sans-serif !important;
    font-weight: 400 !important;
}


.gist .gist-file .gist-data {
    background: #FFFdeb; !important;
    border: 1px solid #da2573 !important;
    border-radius: 1px !important;
    font-size: 0.85em !important;
    color: #1c0021 !important;
    font-family: proxima-nova-condensed, sans-serif !important;
    font-weight: 400;
}

.gist, .gist article, .gist article p {
    white-space: normal !important;
}

/* .gist .gist-hr {
    display: hide !important;
} */

hr {
    border: 2px solid red;
}


body footer a.home:link,
body footer a.home:visited {
    color: #00006b;
}

.action {
    font-family: proxima-nova-condensed, sans-serif;
}

nav#manage ul a {
    color: #00006b;
}

nav#paging a {
    color: #00006b !important;
    font-family: proxima-nova-condensed, sans-serif !important;
}


a.bt {
    background-color: #0d0d0d !important;
    color: #00006b !important;
}

a.hashtag {
    font-family: proxima-nova-condensed, sans-serif;
    font-weight: 700;
    color: #00006b !important;
}

body#collection #wrapper time,
body#subpage #wrapper time,
body#post article time.dt-published,
body#subpage article time.dt-published {
    font-family: proxima-nova-condensed, sans-serif;
    font-weight: 700;
    font-size: 0.95em;
    color: #00006b !important;
}


.custom-nav {
    text-align: center;
    font-size: 0.85em;
    text-transform: uppercase;
    font-family: proxima-nova-condensed, sans-serif;
    font-weight: 700;
    color: red;
}

.custom-nav a:link,
.custom-nav a:visited,
.custom-nav a:hover,
.custom-nav a:active {
    color: #00006b;
}

.custom-nav a:hover,
.custom-nav a:active {
    text-decoration: underline;
}

#subscribe-btn {
    border: 1px #FF0000;
    background: #00006b;
    font-family: proxima-nova-condensed, sans-serif;
    font-weight: 700;
    font-size: 1em;
    color: #FFF4E6;
}

#emailsub {
    font-family: proxima-nova-condensed, sans-serif !important;
    font-weight: 700;
}

sup {
    vertical-align: auto !important;
}

.footnote {
    font-family: proxima-nova-condensed, sans-serif !important;
    font-weight: 700;
    /*vertical-align: sub !important; */
    margin: -4px 0px 0 0 !important;
    color: #da2573 !important;
    font-size: 0.8em;
    line-height: 0.1em !important;
    text-decoration:underline #FF0000;
}

.footnote-ref {
    margin-left:15px;
    font-family: proxima-nova-condensed, sans-serif !important;
    font-weight: 700;
    /* margin-left:2.5px; */
    color: #da2573 !important;
    font-size: 1.15em;
    /* text-decoration:underline #FF0000; */
}

.footnote-ref-text {
    font-family: proxima-nova-condensed, sans-serif !important;
    font-weight: 400;
    color: #1c0021 !important;
    font-size: 1em;
    /* border-top: #00006b dotted 1px; */
}
```

```js
// "This code creates a new <p> element with the div "custom-nav" and it's content. The following code looks for a element with the wrapper id and adds the new <p> element. If the element with the wrapper id is not present, then the <p> element is added after the post-body element. There is then code which sets a hypothesis config which sets the sidebar to stay closed and sets custom colors. The last part of the code looks into the post-body element, finds any footnote reference and then changes them into a clickable link."

//topP.style.textAlign = "center";

var topP = document.createElement("p");
topP.innerHTML = `<hr><div class="custom-nav"><a rel="me" href="https://tiny.write.as/bilge/${location.pathname}">Tiny</a> ※ <a href="https://davidblue.wtf/sms">SMS</a> ※ <a rel="me" href="https://mastodon.social/@DavidBlue">Mastodon</a> ※ <a href="https://github.com/extratone/bilge">GitHub</a> ※ <a href="https://gist.github.com/extratone/140a11428b5dd1dda500b3928e0438b1">License</a></div>`;
var cont = document.getElementById("wrapper");
if (cont !== null) {
	// Add to blog index and tag pages
	cont.appendChild(topP);
} else {
	// Add to individual blog post page
	cont = document.getElementById("post-body");
	cont.insertAdjacentHTML("afterend", topP.outerHTML);
}

// src: https://platform.twitter.com/widgets.js

src: https://hypothes.is/embed.js

window.hypothesisConfig = function () {
  return {
    "openSidebar": true, 
    "theme": "clean",
    branding: {
      appBackgroundColor: '#e6f7ff',
      ctaBackgroundColor: '#da2573',
      ctaTextColor: '#00006b',
      selectionFontFamily: 'Georgia, serif'
    }
  };
};

// Footnote hyperlinks in the body.
var notePattern = /\[\^(\d+)\]/g;
var noteText = "<a name=\"fn$1\"></a><sup><a class=\"footnote\" href=\"#fnref$1\">$1</a></sup>";

// Footnote references at the bottom.
var refPattern = /\[(\d+)\](.*)/g;
var refText = "<a name=\"fnref$1\"></a><sup><a class=\"footnote-ref\" href=\"#fn$1\">$1</a></sup><span class=\"footnote-ref-text\">$2</span>";

var postContent = document.getElementById("post-body").innerHTML;
postContent = postContent.replace(notePattern, noteText);
postContent = postContent.replace(refPattern, refText);
document.getElementById("post-body").innerHTML = postContent;
```