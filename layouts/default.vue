<template>
  <div>
    <nuxt />
  </div>
</template>

<style>
/* html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
} */
/*! sanitize.css v3.3.0 | CC0 1.0 Public Domain | github.com/10up/sanitize.css */
/*
 * Normalization
 */
abbr[title] {
  text-decoration: underline;
  text-decoration: underline dotted;
}

audio:not([controls]) {
  display: none;
}

b,
strong {
  font-weight: bolder;
}

button {
  -webkit-appearance: button;
  overflow: visible;
}

button::-moz-focus-inner,
input::-moz-focus-inner {
  border: 0;
  padding: 0;
}

button:-moz-focusring,
input:-moz-focusring {
  outline: 1px dotted ButtonText;
}

button,
select {
  text-transform: none;
}

details {
  display: block;
}

hr {
  overflow: visible;
}

html {
  -ms-overflow-style: -ms-autohiding-scrollbar;
  overflow-y: scroll;
  -webkit-text-size-adjust: 100%;
}

input {
  -webkit-border-radius: 0;
}
input[type="button"],
input[type="reset"],
input[type="submit"] {
  -webkit-appearance: button;
}
input[type="number"] {
  width: auto;
}
input[type="search"] {
  -webkit-appearance: textfield;
}
input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}

main {
  display: block;
}

pre {
  overflow: auto;
}

progress {
  display: inline-block;
}

summary {
  display: block;
}

svg:not(:root) {
  overflow: hidden;
}

template {
  display: none;
}

textarea {
  overflow: auto;
}

[hidden] {
  display: none;
}

/*
 * Universal inheritance
 */
*,
::before,
::after {
  box-sizing: inherit;
}

* {
  font-size: inherit;
  line-height: inherit;
}

::before,
::after {
  text-decoration: inherit;
  vertical-align: inherit;
}

button,
input,
select,
textarea {
  font-family: inherit;
  font-style: inherit;
  font-weight: inherit;
}

/*
 * Opinionated defaults
 */
* {
  margin: 0;
  padding: 0;
}

*,
::before,
::after {
  border-style: solid;
  border-width: 0;
}

a,
area,
button,
input,
label,
select,
textarea,
[tabindex] {
  -ms-touch-action: manipulation;
  touch-action: manipulation;
}

select {
  -moz-appearance: none;
  -webkit-appearance: none;
}
select::-ms-expand {
  display: none;
}
select::-ms-value {
  color: currentColor;
}

svg {
  fill: currentColor;
}

[aria-busy="true"] {
  cursor: progress;
}

[aria-controls] {
  cursor: pointer;
}

[aria-disabled] {
  cursor: default;
}

[hidden][aria-hidden="false"] {
  clip: rect(0 0 0 0);
  display: inherit;
  position: absolute;
}
[hidden][aria-hidden="false"]:focus {
  clip: auto;
}

/*
 * Configurable defaults
 */
* {
  background-repeat: no-repeat;
}

:root {
  background-color: #ffffff;
  box-sizing: border-box;
  color: #000000;
  cursor: default;
  font: 100% / 1.5 sans-serif;
}

a {
  text-decoration: none;
}

audio,
canvas,
iframe,
img,
svg,
video {
  vertical-align: middle;
}

button,
input,
select,
textarea {
  background-color: transparent;
  color: inherit;
}

button,
[type="button"],
[type="date"],
[type="datetime"],
[type="datetime-local"],
[type="email"],
[type="month"],
[type="number"],
[type="password"],
[type="reset"],
[type="search"],
[type="submit"],
[type="tel"],
[type="text"],
[type="time"],
[type="url"],
[type="week"],
select,
textarea {
  min-height: 1.5em;
}

code,
kbd,
pre,
samp {
  font-family: monospace, monospace;
}

nav ol,
nav ul {
  list-style: none;
}

small {
  font-size: 75%;
}

table {
  border-collapse: collapse;
  border-spacing: 0;
}

textarea {
  resize: vertical;
}

::-moz-selection {
  background-color: #b3d4fc;
  color: #ffffff;
  text-shadow: none;
}

::selection {
  background-color: #b3d4fc;
  color: #ffffff;
  text-shadow: none;
}

main,
header,
footer,
article,
section,
aside,
details,
summary {
  margin: 0 auto;
  width: 100%;
}

main {
  display: block;
  margin: 0 auto;
  max-width: 768px;
  padding: 0 16px 16px;
}

footer {
  border-top: 1px solid rgba(0, 0, 0, 0.12);
  clear: both;
  display: inline-block;
  float: left;
  max-width: 100%;
  padding: 16px 0;
  text-align: center;
}

hr {
  border-top: 1px solid rgba(0, 0, 0, 0.12);
  display: block;
  margin-bottom: 16px;
  width: 100%;
}

img {
  height: auto;
  max-width: 100%;
  vertical-align: baseline;
}

@media screen and (max-width: 400px) {
  article,
  section,
  aside {
    clear: both;
    display: block;
    max-width: 100%;
  }
  img {
    margin-right: 16px;
  }
}

body {
  color: rgba(0, 0, 0, 0.8);
  font-family: "Helvetica Neue", Helvetica, "Lucida Grande", sans-serif;
  font-size: 16px;
  line-height: 1.4;
}

p {
  margin: 0;
  margin-bottom: 16px;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  color: inherit;
  font-family: inherit;
  line-height: inherit;
}

h1 {
  border-bottom: 1px solid rgba(0, 0, 0, 0.12);
  font-size: 36px;
  font-weight: 500;
  margin: 20px 0 16px;
}

h2 {
  font-size: 30px;
  font-weight: 500;
  margin: 20px 0 16px;
}

h3 {
  font-size: 24px;
  font-weight: 500;
  margin: 16px 0 4px;
}

h4 {
  font-size: 18px;
  font-weight: 600;
  margin: 16px 0 4px;
}

h5 {
  font-size: 16px;
  font-weight: 600;
  margin: 16px 0 4px;
}

h6 {
  color: rgba(0, 0, 0, 0.54);
  font-size: 14px;
  font-weight: 600;
  margin: 16px 0 4px;
}

small {
  color: rgba(0, 0, 0, 0.54);
  vertical-align: bottom;
}

pre {
  background: #efefef;
  color: rgba(0, 0, 0, 0.8);
  display: block;
  font-family: Menlo, Monaco, Consolas, "Courier New", monospace;
  font-size: 16px;
  margin: 16px 0;
  padding: 16px;
  white-space: pre-wrap;
}

code {
  color: rgba(0, 0, 0, 0.8);
  font-family: Menlo, Monaco, Consolas, "Courier New", monospace;
  font-size: 16px;
  line-height: inherit;
  margin: 0;
  padding: 0;
  vertical-align: baseline;
  word-break: break-all;
  word-wrap: break-word;
}

a {
  color: #2196f3;
}
a:hover,
a:focus {
  color: #2196f3;
  text-decoration: underline;
}

dl {
  margin-bottom: 16px;
}

dd {
  margin-left: 40px;
}

ul,
ol {
  margin-bottom: 8px;
  padding-left: 40px;
  vertical-align: baseline;
}

blockquote {
  border-left: 2px solid #2196f3;
  font-family: Georgia, Times, "Times New Roman", serif;
  font-style: italic;
  margin: 16px 0;
  padding-left: 16px;
}

figcaption {
  font-family: Georgia, Times, "Times New Roman", serif;
}

u {
  text-decoration: underline;
}

s {
  text-decoration: line-through;
}

sup {
  font-size: 14px;
  vertical-align: super;
}

sub {
  font-size: 14px;
  vertical-align: sub;
}

mark {
  background: #ffeb3b;
}

input[type="text"],
input[type="password"],
input[type="email"],
input[type="url"],
input[type="date"],
input[type="month"],
input[type="time"],
input[type="datetime"],
input[type="datetime-local"],
input[type="week"],
input[type="number"],
input[type="search"],
input[type="tel"],
select {
  background: #fff;
  border: 1px solid rgba(0, 0, 0, 0.12);
  border-radius: 4px;
  color: rgba(0, 0, 0, 0.8);
  display: inline-block;
  padding: 4px;
  vertical-align: middle;
}

input[type="color"] {
  background: #fff;
  border: 1px solid rgba(0, 0, 0, 0.12);
  border-radius: 4px;
  display: inline-block;
  vertical-align: middle;
}

input:not([type]) {
  -webkit-appearance: none;
  background-clip: padding-box;
  border: 1px solid rgba(0, 0, 0, 0.12);
  border-radius: 4px;
  display: inline-block;
  padding: 8px;
  text-align: left;
}

input[type="text"]:focus,
input[type="password"]:focus,
input[type="email"]:focus,
input[type="url"]:focus,
input[type="date"]:focus,
input[type="month"]:focus,
input[type="time"]:focus,
input[type="datetime"]:focus,
input[type="datetime-local"]:focus,
input[type="week"]:focus,
input[type="number"]:focus,
input[type="search"]:focus,
input[type="tel"]:focus,
input[type="color"]:focus,
select:focus,
textarea:focus {
  border-color: #2196f3;
}

input:not([type]):focus {
  border-color: #2196f3;
}

input[type="file"]:focus,
input[type="radio"]:focus,
input[type="checkbox"]:focus {
  outline: 1px thin rgba(0, 0, 0, 0.12);
}

input[type="text"][disabled],
input[type="password"][disabled],
input[type="email"][disabled],
input[type="url"][disabled],
input[type="date"][disabled],
input[type="month"][disabled],
input[type="time"][disabled],
input[type="datetime"][disabled],
input[type="datetime-local"][disabled],
input[type="week"][disabled],
input[type="number"][disabled],
input[type="search"][disabled],
input[type="tel"][disabled],
input[type="color"][disabled],
select[disabled],
textarea[disabled] {
  background-color: rgba(0, 0, 0, 0.12);
  color: rgba(0, 0, 0, 0.54);
  cursor: not-allowed;
}

input:not([type])[disabled] {
  background-color: rgba(0, 0, 0, 0.12);
  color: rgba(0, 0, 0, 0.54);
  cursor: not-allowed;
}

input[readonly],
select[readonly],
textarea[readonly] {
  border-color: rgba(0, 0, 0, 0.12);
  color: rgba(0, 0, 0, 0.54);
}

input:focus:invalid,
textarea:focus:invalid,
select:focus:invalid {
  border-color: #ea1c0d;
  color: #f44336;
}

input[type="file"]:focus:invalid:focus,
input[type="radio"]:focus:invalid:focus,
input[type="checkbox"]:focus:invalid:focus {
  outline-color: #f44336;
}

select {
  -webkit-appearance: menulist-button;
  border: 1px solid rgba(0, 0, 0, 0.12);
  vertical-align: sub;
}

select[multiple] {
  height: auto;
}

label {
  line-height: 2;
}

fieldset {
  border: 0;
  margin: 0;
  padding: 8px 0;
}

legend {
  border-bottom: 1px solid rgba(0, 0, 0, 0.12);
  color: rgba(0, 0, 0, 0.8);
  display: block;
  margin-bottom: 8px;
  padding: 8px 0;
  width: 100%;
}

textarea {
  background: #fff;
  border: 1px solid rgba(0, 0, 0, 0.12);
  border-radius: 4px;
  display: block;
  margin-bottom: 8px;
  max-width: 100%;
  padding: 8px;
  vertical-align: middle;
}

input[type="submit"],
input[type="reset"],
button {
  background: #2196f3;
  border: 1px solid rgba(0, 0, 0, 0.12);
  border-radius: 4px;
  color: #fff;
  cursor: pointer;
  display: inline-block;
  margin: 0;
  padding: 8px 16px;
  text-align: center;
  vertical-align: middle;
  white-space: nowrap;
}

input[type="submit"]::-moz-focus-inner,
input[type="reset"]::-moz-focus-inner,
button::-moz-focus-inner {
  padding: 0;
}

input[type="submit"]:hover,
input[type="reset"]:hover,
button:hover {
  background: #0c7cd5;
  border-color: 1px solid rgba(0, 0, 0, 0.54);
}

input[type="submit"]:active,
input[type="reset"]:active,
button:active {
  background: #0c7cd5;
  border-color: 1px solid rgba(0, 0, 0, 0.54);
  box-shadow: inset 0 0 4px 0 rgba(0, 0, 0, 0.2);
  outline-offset: -2px;
}

input[type="submit"]:focus,
input[type="reset"]:focus,
button:focus {
  background: #0c7cd5;
  border-color: 1px solid rgba(0, 0, 0, 0.54);
  box-shadow: inset 0 0 4px 0 rgba(0, 0, 0, 0.2);
  outline: 0;
}

input[type="submit"]:disabled,
button:disabled {
  background: rgba(0, 0, 0, 0.12);
  color: rgba(0, 0, 0, 0.38);
  cursor: not-allowed;
}

table {
  border-top: 1px solid rgba(0, 0, 0, 0.12);
  margin-bottom: 16px;
}

caption {
  padding: 8px 0;
}

thead th {
  border: 0;
  border-bottom: 2px solid rgba(0, 0, 0, 0.12);
  text-align: left;
}

tr {
  margin-bottom: 8px;
}

th,
td {
  border-bottom: 1px solid rgba(0, 0, 0, 0.12);
  padding: 16px;
  vertical-align: inherit;
}

tfoot tr {
  text-align: left;
}

tfoot td {
  color: rgba(0, 0, 0, 0.54);
  font-size: 8px;
  font-style: italic;
  padding: 16px 4px;
}
</style>
