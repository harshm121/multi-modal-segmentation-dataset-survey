# multi-modal-segmentation-dataset-survet
A survey of Multi-Modal Semantic Segmentation datasets

Notion page link [here](https://harshm121.notion.site/6c54edf1ee8748f89e44b92e72c44f75?v=6eab49ace59840ea8bbd1263aaee826d)

<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>Survey of Multimodal semantic segmentation datasets</title><style>
/* cspell:disable-file */
/* webkit printing magic: print all background colors */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}

body {
	line-height: 1.5;
	white-space: pre-wrap;
}

a,
a.visited {
	color: inherit;
	text-decoration: underline;
}

.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}

h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
	margin-bottom: 0;
}

.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}

h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}

h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}

h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}

.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}

.callout {
	border-radius: 3px;
	padding: 1rem;
}

figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}

figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}

mark {
	background-color: transparent;
}

.indented {
	padding-left: 1.5em;
}

hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
	max-width: 100%;
}

@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}
}

@page {
	margin: 1in;
}

.collection-content {
	font-size: 0.875rem;
}

.column-list {
	display: flex;
	justify-content: space-between;
}

.column {
	padding: 0 1em;
}

.column:first-child {
	padding-left: 0;
}

.column:last-child {
	padding-right: 0;
}

.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}

.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
	margin-left: 3rem;
}

.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}

.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}

table {
	border-left: none;
	border-right: none;
}

th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}

th {
	color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}

ul > li {
	list-style: disc;
}

ul.to-do-list {
	text-indent: -1.7em;
}

ul.to-do-list > li {
	list-style: none;
}

.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

ul.toggle > li {
	list-style: none;
}

ul {
	padding-inline-start: 1.7em;
}

ul > li {
	padding-left: 0.1em;
}

ol {
	padding-inline-start: 1.6em;
}

ol > li {
	padding-left: 0.2em;
}

.mono ol {
	padding-inline-start: 2em;
}

.mono ol > li {
	text-indent: -0.4em;
}

.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}

/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}

.toggle > li > details > summary {
	margin-left: -1.1em;
}

.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}

.collection-title {
	display: inline-block;
	margin-right: 1em;
}

.simple-table {
	margin-top: 1em;
	font-size: 0.875rem;
}

.simple-table-header {
	background: rgb(247, 246, 243);
	color: black;
	font-weight: 500;
}

time {
	opacity: 0.5;
}

.icon {
	display: inline-block;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
}

.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}

.user-icon-inner {
	font-size: 0.8em;
}

.text-icon {
	border: 1px solid #000;
	text-align: center;
}

.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	max-height: 30vh;
}

.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}

.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}

.page-header-icon img {
	border-radius: 3px;
}

.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}

p > .user {
	opacity: 0.5;
}

td > .user,
td > time {
	white-space: nowrap;
}

input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}

p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}

.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}

.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}

code {
	color: #eb5757;
}

.code {
	padding: 1.5em 1em;
}

.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}

.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}

blockquote {
	font-size: 1.25em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}

.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}

.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}

.bookmark-text {
	display: flex;
	flex-direction: column;
}

.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}

.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}

.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.highlight-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.highlight-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.highlight-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.highlight-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.highlight-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.highlight-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.highlight-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.highlight-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.highlight-gray_background {
	background: rgba(241, 241, 239, 1);
}
.highlight-brown_background {
	background: rgba(244, 238, 238, 1);
}
.highlight-orange_background {
	background: rgba(251, 236, 221, 1);
}
.highlight-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.highlight-teal_background {
	background: rgba(237, 243, 236, 1);
}
.highlight-blue_background {
	background: rgba(231, 243, 248, 1);
}
.highlight-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.highlight-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.highlight-red_background {
	background: rgba(253, 235, 236, 1);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.block-color-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.block-color-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.block-color-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.block-color-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.block-color-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.block-color-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.block-color-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.block-color-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.block-color-gray_background {
	background: rgba(241, 241, 239, 1);
}
.block-color-brown_background {
	background: rgba(244, 238, 238, 1);
}
.block-color-orange_background {
	background: rgba(251, 236, 221, 1);
}
.block-color-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.block-color-teal_background {
	background: rgba(237, 243, 236, 1);
}
.block-color-blue_background {
	background: rgba(231, 243, 248, 1);
}
.block-color-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.block-color-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.block-color-red_background {
	background: rgba(253, 235, 236, 1);
}
.select-value-color-pink { background-color: rgba(245, 224, 233, 1); }
.select-value-color-purple { background-color: rgba(232, 222, 238, 1); }
.select-value-color-green { background-color: rgba(219, 237, 219, 1); }
.select-value-color-gray { background-color: rgba(227, 226, 224, 1); }
.select-value-color-opaquegray { background-color: rgba(255, 255, 255, 0.0375); }
.select-value-color-orange { background-color: rgba(250, 222, 201, 1); }
.select-value-color-brown { background-color: rgba(238, 224, 218, 1); }
.select-value-color-red { background-color: rgba(255, 226, 221, 1); }
.select-value-color-yellow { background-color: rgba(253, 236, 200, 1); }
.select-value-color-blue { background-color: rgba(211, 229, 239, 1); }

.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}

.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
	
</style></head><body><article id="6c54edf1-ee87-48f8-9e44-b92e72c44f75" class="page sans"><header><h1 class="page-title">Survey of Multimodal semantic segmentation datasets</h1></header><div class="page-body"><table class="collection-content"><thead><tr><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesTitle"><path d="M7.73943662,8.6971831 C7.77640845,8.7834507 7.81338028,8.8943662 7.81338028,9.00528169 C7.81338028,9.49823944 7.40669014,9.89260563 6.91373239,9.89260563 C6.53169014,9.89260563 6.19894366,9.64612676 6.08802817,9.30105634 L5.75528169,8.33978873 L2.05809859,8.33978873 L1.72535211,9.30105634 C1.61443662,9.64612676 1.2693662,9.89260563 0.887323944,9.89260563 C0.394366197,9.89260563 0,9.49823944 0,9.00528169 C0,8.8943662 0.0246478873,8.7834507 0.0616197183,8.6971831 L2.46478873,2.48591549 C2.68661972,1.90669014 3.24119718,1.5 3.90669014,1.5 C4.55985915,1.5 5.12676056,1.90669014 5.34859155,2.48591549 L7.73943662,8.6971831 Z M2.60035211,6.82394366 L5.21302817,6.82394366 L3.90669014,3.10211268 L2.60035211,6.82394366 Z M11.3996479,3.70598592 C12.7552817,3.70598592 14,4.24823944 14,5.96126761 L14,9.07922535 C14,9.52288732 13.6549296,9.89260563 13.2112676,9.89260563 C12.8169014,9.89260563 12.471831,9.59683099 12.4225352,9.19014085 C12.028169,9.6584507 11.3257042,9.95422535 10.5492958,9.95422535 C9.60035211,9.95422535 8.47887324,9.31338028 8.47887324,7.98239437 C8.47887324,6.58978873 9.60035211,6.08450704 10.5492958,6.08450704 C11.3380282,6.08450704 12.040493,6.33098592 12.4348592,6.81161972 L12.4348592,5.98591549 C12.4348592,5.38204225 11.9172535,4.98767606 11.1285211,4.98767606 C10.6602113,4.98767606 10.2411972,5.11091549 9.80985915,5.38204225 C9.72359155,5.43133803 9.61267606,5.46830986 9.50176056,5.46830986 C9.18133803,5.46830986 8.91021127,5.1971831 8.91021127,4.86443662 C8.91021127,4.64260563 9.0334507,4.44542254 9.19366197,4.34683099 C9.87147887,3.90316901 10.6232394,3.70598592 11.3996479,3.70598592 Z M11.1778169,8.8943662 C11.6830986,8.8943662 12.1760563,8.72183099 12.4348592,8.37676056 L12.4348592,7.63732394 C12.1760563,7.29225352 11.6830986,7.11971831 11.1778169,7.11971831 C10.5616197,7.11971831 10.056338,7.45246479 10.056338,8.0193662 C10.056338,8.57394366 10.5616197,8.8943662 11.1778169,8.8943662 Z M0.65625,11.125 L13.34375,11.125 C13.7061869,11.125 14,11.4188131 14,11.78125 C14,12.1436869 13.7061869,12.4375 13.34375,12.4375 L0.65625,12.4375 C0.293813133,12.4375 4.43857149e-17,12.1436869 0,11.78125 C-4.43857149e-17,11.4188131 0.293813133,11.125 0.65625,11.125 Z"></path></svg></span>Name</th><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesMultipleSelect"><path d="M4,3 C4,2.447715 4.447715,2 5,2 L12,2 C12.5523,2 13,2.447716 13,3 C13,3.55228 12.5523,4 12,4 L5,4 C4.447715,4 4,3.55228 4,3 Z M4,7 C4,6.447715 4.447715,6 5,6 L12,6 C12.5523,6 13,6.447716 13,7 C13,7.55228 12.5523,8 12,8 L5,8 C4.447715,8 4,7.55228 4,7 Z M4,11 C4,10.447715 4.447715,10 5,10 L12,10 C12.5523,10 13,10.447716 13,11 C13,11.55228 12.5523,12 12,12 L5,12 C4.447715,12 4,11.55228 4,11 Z M2,4 C1.44771525,4 1,3.55228475 1,3 C1,2.44771525 1.44771525,2 2,2 C2.55228475,2 3,2.44771525 3,3 C3,3.55228475 2.55228475,4 2,4 Z M2,8 C1.44771525,8 1,7.55228475 1,7 C1,6.44771525 1.44771525,6 2,6 C2.55228475,6 3,6.44771525 3,7 C3,7.55228475 2.55228475,8 2,8 Z M2,12 C1.44771525,12 1,11.5522847 1,11 C1,10.4477153 1.44771525,10 2,10 C2.55228475,10 3,10.4477153 3,11 C3,11.5522847 2.55228475,12 2,12 Z"></path></svg></span>Modalities</th><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesNumber"><path d="M4.46191,0 C3.8667,0 3.38428,0.482422 3.38428,1.07751 L3.38428,3.38425 L1.07764,3.38425 C0.482422,3.38425 0,3.86667 0,4.46179 C0,5.05688 0.482422,5.53931 1.07764,5.53931 L3.38428,5.53931 L3.38428,8.46063 L1.07764,8.46063 C0.482422,8.46063 0,8.94308 0,9.53818 C0,10.1333 0.482422,10.6157 1.07764,10.6157 L3.38428,10.6157 L3.38428,12.9224 C3.38428,13.5175 3.8667,13.9999 4.46191,13.9999 C5.05664,13.9999 5.53906,13.5175 5.53906,12.9224 L5.53906,10.6157 L8.46045,10.6157 L8.46045,12.9224 C8.46045,13.5175 8.94287,13.9999 9.53809,13.9999 C10.1333,13.9999 10.6157,13.5175 10.6157,12.9224 L10.6157,10.6157 L12.9224,10.6157 C13.5176,10.6157 14,10.1333 14,9.53818 C14,8.94308 13.5176,8.46063 12.9224,8.46063 L10.6157,8.46063 L10.6157,5.53931 L12.9224,5.53931 C13.5176,5.53931 14,5.05688 14,4.46179 C14,3.86667 13.5176,3.38425 12.9224,3.38425 L10.6157,3.38425 L10.6157,1.07751 C10.6157,0.482422 10.1333,0 9.53809,0 C8.94287,0 8.46045,0.482422 8.46045,1.07751 L8.46045,3.38425 L5.53906,3.38425 L5.53906,1.07751 C5.53906,0.482422 5.05664,0 4.46191,0 Z M5.53906,8.46063 L5.53906,5.53931 L8.46045,5.53931 L8.46045,8.46063 L5.53906,8.46063 Z"></path></svg></span>Year Released</th><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesText"><path d="M7,4.56818 C7,4.29204 6.77614,4.06818 6.5,4.06818 L0.5,4.06818 C0.223858,4.06818 0,4.29204 0,4.56818 L0,5.61364 C0,5.88978 0.223858,6.11364 0.5,6.11364 L6.5,6.11364 C6.77614,6.11364 7,5.88978 7,5.61364 L7,4.56818 Z M0.5,1 C0.223858,1 0,1.223858 0,1.5 L0,2.54545 C0,2.8216 0.223858,3.04545 0.5,3.04545 L12.5,3.04545 C12.7761,3.04545 13,2.8216 13,2.54545 L13,1.5 C13,1.223858 12.7761,1 12.5,1 L0.5,1 Z M0,8.68182 C0,8.95796 0.223858,9.18182 0.5,9.18182 L11.5,9.18182 C11.7761,9.18182 12,8.95796 12,8.68182 L12,7.63636 C12,7.36022 11.7761,7.13636 11.5,7.13636 L0.5,7.13636 C0.223858,7.13636 0,7.36022 0,7.63636 L0,8.68182 Z M0,11.75 C0,12.0261 0.223858,12.25 0.5,12.25 L9.5,12.25 C9.77614,12.25 10,12.0261 10,11.75 L10,10.70455 C10,10.4284 9.77614,10.20455 9.5,10.20455 L0.5,10.20455 C0.223858,10.20455 0,10.4284 0,10.70455 L0,11.75 Z"></path></svg></span>Total points</th><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesText"><path d="M7,4.56818 C7,4.29204 6.77614,4.06818 6.5,4.06818 L0.5,4.06818 C0.223858,4.06818 0,4.29204 0,4.56818 L0,5.61364 C0,5.88978 0.223858,6.11364 0.5,6.11364 L6.5,6.11364 C6.77614,6.11364 7,5.88978 7,5.61364 L7,4.56818 Z M0.5,1 C0.223858,1 0,1.223858 0,1.5 L0,2.54545 C0,2.8216 0.223858,3.04545 0.5,3.04545 L12.5,3.04545 C12.7761,3.04545 13,2.8216 13,2.54545 L13,1.5 C13,1.223858 12.7761,1 12.5,1 L0.5,1 Z M0,8.68182 C0,8.95796 0.223858,9.18182 0.5,9.18182 L11.5,9.18182 C11.7761,9.18182 12,8.95796 12,8.68182 L12,7.63636 C12,7.36022 11.7761,7.13636 11.5,7.13636 L0.5,7.13636 C0.223858,7.13636 0,7.36022 0,7.63636 L0,8.68182 Z M0,11.75 C0,12.0261 0.223858,12.25 0.5,12.25 L9.5,12.25 C9.77614,12.25 10,12.0261 10,11.75 L10,10.70455 C10,10.4284 9.77614,10.20455 9.5,10.20455 L0.5,10.20455 C0.223858,10.20455 0,10.4284 0,10.70455 L0,11.75 Z"></path></svg></span>Unlabeled points</th><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesText"><path d="M7,4.56818 C7,4.29204 6.77614,4.06818 6.5,4.06818 L0.5,4.06818 C0.223858,4.06818 0,4.29204 0,4.56818 L0,5.61364 C0,5.88978 0.223858,6.11364 0.5,6.11364 L6.5,6.11364 C6.77614,6.11364 7,5.88978 7,5.61364 L7,4.56818 Z M0.5,1 C0.223858,1 0,1.223858 0,1.5 L0,2.54545 C0,2.8216 0.223858,3.04545 0.5,3.04545 L12.5,3.04545 C12.7761,3.04545 13,2.8216 13,2.54545 L13,1.5 C13,1.223858 12.7761,1 12.5,1 L0.5,1 Z M0,8.68182 C0,8.95796 0.223858,9.18182 0.5,9.18182 L11.5,9.18182 C11.7761,9.18182 12,8.95796 12,8.68182 L12,7.63636 C12,7.36022 11.7761,7.13636 11.5,7.13636 L0.5,7.13636 C0.223858,7.13636 0,7.36022 0,7.63636 L0,8.68182 Z M0,11.75 C0,12.0261 0.223858,12.25 0.5,12.25 L9.5,12.25 C9.77614,12.25 10,12.0261 10,11.75 L10,10.70455 C10,10.4284 9.77614,10.20455 9.5,10.20455 L0.5,10.20455 C0.223858,10.20455 0,10.4284 0,10.70455 L0,11.75 Z"></path></svg></span>Training points</th><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesText"><path d="M7,4.56818 C7,4.29204 6.77614,4.06818 6.5,4.06818 L0.5,4.06818 C0.223858,4.06818 0,4.29204 0,4.56818 L0,5.61364 C0,5.88978 0.223858,6.11364 0.5,6.11364 L6.5,6.11364 C6.77614,6.11364 7,5.88978 7,5.61364 L7,4.56818 Z M0.5,1 C0.223858,1 0,1.223858 0,1.5 L0,2.54545 C0,2.8216 0.223858,3.04545 0.5,3.04545 L12.5,3.04545 C12.7761,3.04545 13,2.8216 13,2.54545 L13,1.5 C13,1.223858 12.7761,1 12.5,1 L0.5,1 Z M0,8.68182 C0,8.95796 0.223858,9.18182 0.5,9.18182 L11.5,9.18182 C11.7761,9.18182 12,8.95796 12,8.68182 L12,7.63636 C12,7.36022 11.7761,7.13636 11.5,7.13636 L0.5,7.13636 C0.223858,7.13636 0,7.36022 0,7.63636 L0,8.68182 Z M0,11.75 C0,12.0261 0.223858,12.25 0.5,12.25 L9.5,12.25 C9.77614,12.25 10,12.0261 10,11.75 L10,10.70455 C10,10.4284 9.77614,10.20455 9.5,10.20455 L0.5,10.20455 C0.223858,10.20455 0,10.4284 0,10.70455 L0,11.75 Z"></path></svg></span>Test points</th><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesText"><path d="M7,4.56818 C7,4.29204 6.77614,4.06818 6.5,4.06818 L0.5,4.06818 C0.223858,4.06818 0,4.29204 0,4.56818 L0,5.61364 C0,5.88978 0.223858,6.11364 0.5,6.11364 L6.5,6.11364 C6.77614,6.11364 7,5.88978 7,5.61364 L7,4.56818 Z M0.5,1 C0.223858,1 0,1.223858 0,1.5 L0,2.54545 C0,2.8216 0.223858,3.04545 0.5,3.04545 L12.5,3.04545 C12.7761,3.04545 13,2.8216 13,2.54545 L13,1.5 C13,1.223858 12.7761,1 12.5,1 L0.5,1 Z M0,8.68182 C0,8.95796 0.223858,9.18182 0.5,9.18182 L11.5,9.18182 C11.7761,9.18182 12,8.95796 12,8.68182 L12,7.63636 C12,7.36022 11.7761,7.13636 11.5,7.13636 L0.5,7.13636 C0.223858,7.13636 0,7.36022 0,7.63636 L0,8.68182 Z M0,11.75 C0,12.0261 0.223858,12.25 0.5,12.25 L9.5,12.25 C9.77614,12.25 10,12.0261 10,11.75 L10,10.70455 C10,10.4284 9.77614,10.20455 9.5,10.20455 L0.5,10.20455 C0.223858,10.20455 0,10.4284 0,10.70455 L0,11.75 Z"></path></svg></span>Val points</th><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesText"><path d="M7,4.56818 C7,4.29204 6.77614,4.06818 6.5,4.06818 L0.5,4.06818 C0.223858,4.06818 0,4.29204 0,4.56818 L0,5.61364 C0,5.88978 0.223858,6.11364 0.5,6.11364 L6.5,6.11364 C6.77614,6.11364 7,5.88978 7,5.61364 L7,4.56818 Z M0.5,1 C0.223858,1 0,1.223858 0,1.5 L0,2.54545 C0,2.8216 0.223858,3.04545 0.5,3.04545 L12.5,3.04545 C12.7761,3.04545 13,2.8216 13,2.54545 L13,1.5 C13,1.223858 12.7761,1 12.5,1 L0.5,1 Z M0,8.68182 C0,8.95796 0.223858,9.18182 0.5,9.18182 L11.5,9.18182 C11.7761,9.18182 12,8.95796 12,8.68182 L12,7.63636 C12,7.36022 11.7761,7.13636 11.5,7.13636 L0.5,7.13636 C0.223858,7.13636 0,7.36022 0,7.63636 L0,8.68182 Z M0,11.75 C0,12.0261 0.223858,12.25 0.5,12.25 L9.5,12.25 C9.77614,12.25 10,12.0261 10,11.75 L10,10.70455 C10,10.4284 9.77614,10.20455 9.5,10.20455 L0.5,10.20455 C0.223858,10.20455 0,10.4284 0,10.70455 L0,11.75 Z"></path></svg></span>Classes</th><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesText"><path d="M7,4.56818 C7,4.29204 6.77614,4.06818 6.5,4.06818 L0.5,4.06818 C0.223858,4.06818 0,4.29204 0,4.56818 L0,5.61364 C0,5.88978 0.223858,6.11364 0.5,6.11364 L6.5,6.11364 C6.77614,6.11364 7,5.88978 7,5.61364 L7,4.56818 Z M0.5,1 C0.223858,1 0,1.223858 0,1.5 L0,2.54545 C0,2.8216 0.223858,3.04545 0.5,3.04545 L12.5,3.04545 C12.7761,3.04545 13,2.8216 13,2.54545 L13,1.5 C13,1.223858 12.7761,1 12.5,1 L0.5,1 Z M0,8.68182 C0,8.95796 0.223858,9.18182 0.5,9.18182 L11.5,9.18182 C11.7761,9.18182 12,8.95796 12,8.68182 L12,7.63636 C12,7.36022 11.7761,7.13636 11.5,7.13636 L0.5,7.13636 C0.223858,7.13636 0,7.36022 0,7.63636 L0,8.68182 Z M0,11.75 C0,12.0261 0.223858,12.25 0.5,12.25 L9.5,12.25 C9.77614,12.25 10,12.0261 10,11.75 L10,10.70455 C10,10.4284 9.77614,10.20455 9.5,10.20455 L0.5,10.20455 C0.223858,10.20455 0,10.4284 0,10.70455 L0,11.75 Z"></path></svg></span>Used In</th><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesSelect"><path d="M7,13 C10.31348,13 13,10.31371 13,7 C13,3.68629 10.31348,1 7,1 C3.68652,1 1,3.68629 1,7 C1,10.31371 3.68652,13 7,13 Z M3.75098,5.32278 C3.64893,5.19142 3.74268,5 3.90869,5 L10.09131,5 C10.25732,5 10.35107,5.19142 10.24902,5.32278 L7.15771,9.29703 C7.07764,9.39998 6.92236,9.39998 6.84229,9.29703 L3.75098,5.32278 Z"></path></svg></span>Real/Synthetic</th><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesMultipleSelect"><path d="M4,3 C4,2.447715 4.447715,2 5,2 L12,2 C12.5523,2 13,2.447716 13,3 C13,3.55228 12.5523,4 12,4 L5,4 C4.447715,4 4,3.55228 4,3 Z M4,7 C4,6.447715 4.447715,6 5,6 L12,6 C12.5523,6 13,6.447716 13,7 C13,7.55228 12.5523,8 12,8 L5,8 C4.447715,8 4,7.55228 4,7 Z M4,11 C4,10.447715 4.447715,10 5,10 L12,10 C12.5523,10 13,10.447716 13,11 C13,11.55228 12.5523,12 12,12 L5,12 C4.447715,12 4,11.55228 4,11 Z M2,4 C1.44771525,4 1,3.55228475 1,3 C1,2.44771525 1.44771525,2 2,2 C2.55228475,2 3,2.44771525 3,3 C3,3.55228475 2.55228475,4 2,4 Z M2,8 C1.44771525,8 1,7.55228475 1,7 C1,6.44771525 1.44771525,6 2,6 C2.55228475,6 3,6.44771525 3,7 C3,7.55228475 2.55228475,8 2,8 Z M2,12 C1.44771525,12 1,11.5522847 1,11 C1,10.4477153 1.44771525,10 2,10 C2.55228475,10 3,10.4477153 3,11 C3,11.5522847 2.55228475,12 2,12 Z"></path></svg></span>Scenes</th><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesMultipleSelect"><path d="M4,3 C4,2.447715 4.447715,2 5,2 L12,2 C12.5523,2 13,2.447716 13,3 C13,3.55228 12.5523,4 12,4 L5,4 C4.447715,4 4,3.55228 4,3 Z M4,7 C4,6.447715 4.447715,6 5,6 L12,6 C12.5523,6 13,6.447716 13,7 C13,7.55228 12.5523,8 12,8 L5,8 C4.447715,8 4,7.55228 4,7 Z M4,11 C4,10.447715 4.447715,10 5,10 L12,10 C12.5523,10 13,10.447716 13,11 C13,11.55228 12.5523,12 12,12 L5,12 C4.447715,12 4,11.55228 4,11 Z M2,4 C1.44771525,4 1,3.55228475 1,3 C1,2.44771525 1.44771525,2 2,2 C2.55228475,2 3,2.44771525 3,3 C3,3.55228475 2.55228475,4 2,4 Z M2,8 C1.44771525,8 1,7.55228475 1,7 C1,6.44771525 1.44771525,6 2,6 C2.55228475,6 3,6.44771525 3,7 C3,7.55228475 2.55228475,8 2,8 Z M2,12 C1.44771525,12 1,11.5522847 1,11 C1,10.4477153 1.44771525,10 2,10 C2.55228475,10 3,10.4477153 3,11 C3,11.5522847 2.55228475,12 2,12 Z"></path></svg></span>Annotations</th><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesUrl"><path d="M3.73333,3.86667 L7.46667,3.86667 C8.49613,3.86667 9.33333,4.70387 9.33333,5.73333 C9.33333,6.7628 8.49613,7.6 7.46667,7.6 L6.53333,7.6 C6.01813,7.6 5.6,8.0186 5.6,8.53333 C5.6,9.04807 6.01813,9.46667 6.53333,9.46667 L7.46667,9.46667 C9.5284,9.46667 11.2,7.79507 11.2,5.73333 C11.2,3.6716 9.5284,2 7.46667,2 L3.73333,2 C1.6716,2 0,3.6716 0,5.73333 C0,7.124 0.762067,8.33453 1.88953,8.97713 C1.87553,8.83107 1.86667,8.6836 1.86667,8.53333 C1.86667,7.92013 1.98753,7.33447 2.2036,6.7978 C1.99267,6.4954 1.86667,6.12953 1.86667,5.73333 C1.86667,4.70387 2.70387,3.86667 3.73333,3.86667 Z M12.1095,5.28907 C12.1231,5.4356 12.1333,5.58307 12.1333,5.73333 C12.1333,6.34607 12.0101,6.9294 11.7931,7.46513 C12.0059,7.768 12.1333,8.13573 12.1333,8.53333 C12.1333,9.5628 11.2961,10.4 10.2667,10.4 L6.53333,10.4 C5.50387,10.4 4.66667,9.5628 4.66667,8.53333 C4.66667,7.50387 5.50387,6.66667 6.53333,6.66667 L7.46667,6.66667 C7.98187,6.66667 8.4,6.24807 8.4,5.73333 C8.4,5.2186 7.98187,4.8 7.46667,4.8 L6.53333,4.8 C4.4716,4.8 2.8,6.4716 2.8,8.53333 C2.8,10.59507 4.4716,12.2667 6.53333,12.2667 L10.2667,12.2667 C12.3284,12.2667 14,10.59507 14,8.53333 C14,7.14267 13.2375,5.93167 12.1095,5.28907 Z"></path></svg></span>Papers with code</th><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesText"><path d="M7,4.56818 C7,4.29204 6.77614,4.06818 6.5,4.06818 L0.5,4.06818 C0.223858,4.06818 0,4.29204 0,4.56818 L0,5.61364 C0,5.88978 0.223858,6.11364 0.5,6.11364 L6.5,6.11364 C6.77614,6.11364 7,5.88978 7,5.61364 L7,4.56818 Z M0.5,1 C0.223858,1 0,1.223858 0,1.5 L0,2.54545 C0,2.8216 0.223858,3.04545 0.5,3.04545 L12.5,3.04545 C12.7761,3.04545 13,2.8216 13,2.54545 L13,1.5 C13,1.223858 12.7761,1 12.5,1 L0.5,1 Z M0,8.68182 C0,8.95796 0.223858,9.18182 0.5,9.18182 L11.5,9.18182 C11.7761,9.18182 12,8.95796 12,8.68182 L12,7.63636 C12,7.36022 11.7761,7.13636 11.5,7.13636 L0.5,7.13636 C0.223858,7.13636 0,7.36022 0,7.63636 L0,8.68182 Z M0,11.75 C0,12.0261 0.223858,12.25 0.5,12.25 L9.5,12.25 C9.77614,12.25 10,12.0261 10,11.75 L10,10.70455 C10,10.4284 9.77614,10.20455 9.5,10.20455 L0.5,10.20455 C0.223858,10.20455 0,10.4284 0,10.70455 L0,11.75 Z"></path></svg></span>Misc</th></tr></thead><tbody><tr id="a9308834-9f0c-4f38-9790-40cfa2665b0e"><td class="cell-title"><a href="https://www.notion.so/Cityscapes-a93088349f0c4f38979040cfa2665b0e">Cityscapes</a></td><td class="cell-\[;t"><span class="selected-value select-value-color-brown">Disparity</span><span class="selected-value select-value-color-green">RGB</span></td><td class="cell-=Gd;">2016</td><td class="cell-{JVu">5000</td><td class="cell-oZm^"></td><td class="cell-LyNN">2975</td><td class="cell-Rzl@">1525</td><td class="cell-[yAr">500</td><td class="cell-MSuH">19</td><td class="cell-Gr|V">Separation-and-Aggregation Gate ECCV20; RFBNet arXiv’19; Malleable 2.5D Convolution ECCV’20; SSMA IJCV’19;</td><td class="cell-_frr"><span class="selected-value">Real</span></td><td class="cell-Z\bo"><span class="selected-value select-value-color-pink">Urban Street</span></td><td class="cell-ew?`"><span class="selected-value select-value-color-purple">Semantic Segmentation</span></td><td class="cell-CR;k"><a href="https://paperswithcode.com/sota/semantic-segmentation-on-cityscapes-val" class="url-value">https://paperswithcode.com/sota/semantic-segmentation-on-cityscapes-val</a></td><td class="cell-U}sm">27 cities</td></tr><tr id="c2231bf0-f3ae-4d8c-ac14-7e2b2620bb80"><td class="cell-title"><a href="https://www.notion.so/NYU-Depth-v2-c2231bf0f3ae4d8cac147e2b2620bb80">NYU Depth v2</a></td><td class="cell-\[;t"><span class="selected-value select-value-color-red">Depth</span><span class="selected-value select-value-color-green">RGB</span></td><td class="cell-=Gd;">2012</td><td class="cell-{JVu">1449</td><td class="cell-oZm^"></td><td class="cell-LyNN">795</td><td class="cell-Rzl@">654</td><td class="cell-[yAr">0</td><td class="cell-MSuH">40; 13</td><td class="cell-Gr|V">Separation-and-Aggregation Gate ECCV 20; ShapeConv ICCV’21; Cascaded Feature Network ICCV’17; CEN NeurIPS’20; Malleable 2.5D Convolution ECCV’20; Spatial Information Guided Convolution arXiv’21;</td><td class="cell-_frr"><span class="selected-value">Real</span></td><td class="cell-Z\bo"><span class="selected-value select-value-color-yellow">Indoor</span></td><td class="cell-ew?`"><span class="selected-value select-value-color-purple">Semantic Segmentation</span></td><td class="cell-CR;k"><a href="https://paperswithcode.com/sota/semantic-segmentation-on-nyu-depth-v2" class="url-value">https://paperswithcode.com/sota/semantic-segmentation-on-nyu-depth-v2</a></td><td class="cell-U}sm"></td></tr><tr id="b9c057d4-5632-4c56-8b24-77d960ae59fe"><td class="cell-title"><a href="https://www.notion.so/SUN-RGBD-b9c057d456324c568b2477d960ae59fe">SUN-RGBD</a></td><td class="cell-\[;t"><span class="selected-value select-value-color-red">Depth</span><span class="selected-value select-value-color-green">RGB</span></td><td class="cell-=Gd;">2015</td><td class="cell-{JVu">10335</td><td class="cell-oZm^"></td><td class="cell-LyNN">5285</td><td class="cell-Rzl@">5050</td><td class="cell-[yAr">0</td><td class="cell-MSuH">37</td><td class="cell-Gr|V">ShapeConv ICCV’21; Cascaded Feature Network ICCV’17; CEN NeurIPS’20; Spatial Information Guided Convolution arXiv’21; SSMA IJCV’19;</td><td class="cell-_frr"><span class="selected-value">Real</span></td><td class="cell-Z\bo"><span class="selected-value select-value-color-yellow">Indoor</span></td><td class="cell-ew?`"><span class="selected-value select-value-color-purple">Semantic Segmentation</span></td><td class="cell-CR;k"><a href="https://paperswithcode.com/sota/semantic-segmentation-on-sun-rgbd" class="url-value">https://paperswithcode.com/sota/semantic-segmentation-on-sun-rgbd</a></td><td class="cell-U}sm">RGB-D images from NYU depth v2, Berkeley B3DO and SUN3D</td></tr><tr id="10f0c7eb-98f5-43b8-92f2-3d4a9d6b15a7"><td class="cell-title"><a href="https://www.notion.so/Stanford-Indoor-Dataset-10f0c7eb98f543b892f23d4a9d6b15a7">Stanford Indoor Dataset</a></td><td class="cell-\[;t"><span class="selected-value select-value-color-red">Depth</span><span class="selected-value select-value-color-green">RGB</span><span class="selected-value select-value-color-blue">Surface Normals</span></td><td class="cell-=Gd;">2017</td><td class="cell-{JVu">70496</td><td class="cell-oZm^"></td><td class="cell-LyNN">52903</td><td class="cell-Rzl@">17593</td><td class="cell-[yAr">0</td><td class="cell-MSuH">13</td><td class="cell-Gr|V">ShapeConv ICCV’21; </td><td class="cell-_frr"><span class="selected-value">Real</span></td><td class="cell-Z\bo"><span class="selected-value select-value-color-yellow">Indoor</span></td><td class="cell-ew?`"><span class="selected-value select-value-color-purple">Semantic Segmentation</span></td><td class="cell-CR;k"></td><td class="cell-U}sm"></td></tr><tr id="feaa999e-6ee5-4ea9-9bda-ffc0ace9ff7e"><td class="cell-title"><a href="https://www.notion.so/ScanNett-feaa999e6ee54ea99bdaffc0ace9ff7e">ScanNett</a></td><td class="cell-\[;t"><span class="selected-value select-value-color-red">Depth</span><span class="selected-value select-value-color-green">RGB</span></td><td class="cell-=Gd;">2017</td><td class="cell-{JVu">27439</td><td class="cell-oZm^"></td><td class="cell-LyNN">19466</td><td class="cell-Rzl@">2537</td><td class="cell-[yAr">5436</td><td class="cell-MSuH">20</td><td class="cell-Gr|V">RFBNet arXiv’19; SSMA IJCV’19;</td><td class="cell-_frr"><span class="selected-value">Real</span></td><td class="cell-Z\bo"><span class="selected-value select-value-color-yellow">Indoor</span></td><td class="cell-ew?`"><span class="selected-value select-value-color-purple">Semantic Segmentation</span></td><td class="cell-CR;k"><a href="https://paperswithcode.com/sota/semantic-segmentation-on-scannet" class="url-value">https://paperswithcode.com/sota/semantic-segmentation-on-scannet</a></td><td class="cell-U}sm"></td></tr><tr id="4d8c5c96-7df7-42e5-9583-8f551936fd7e"><td class="cell-title"><a href="https://www.notion.so/SceneNet-RGB-D-4d8c5c967df742e595838f551936fd7e">SceneNet RGB-D</a></td><td class="cell-\[;t"><span class="selected-value select-value-color-red">Depth</span><span class="selected-value select-value-color-purple">Optical Flow</span><span class="selected-value select-value-color-green">RGB</span></td><td class="cell-=Gd;">2016</td><td class="cell-{JVu">5.3M</td><td class="cell-oZm^"></td><td class="cell-LyNN">5M</td><td class="cell-Rzl@">300k</td><td class="cell-[yAr"></td><td class="cell-MSuH"></td><td class="cell-Gr|V"></td><td class="cell-_frr"><span class="selected-value select-value-color-blue">Synthetic</span></td><td class="cell-Z\bo"><span class="selected-value select-value-color-yellow">Indoor</span></td><td class="cell-ew?`"><span class="selected-value select-value-color-purple">Semantic Segmentation</span></td><td class="cell-CR;k"></td><td class="cell-U}sm"></td></tr><tr id="72d53834-c0ac-466a-a813-10b56357513f"><td class="cell-title"><a href="https://www.notion.so/SYNTHIA-Rand-Cityscapes-72d53834c0ac466aa81310b56357513f">SYNTHIA-Rand-Cityscapes</a></td><td class="cell-\[;t"><span class="selected-value select-value-color-red">Depth</span><span class="selected-value select-value-color-green">RGB</span></td><td class="cell-=Gd;">2016</td><td class="cell-{JVu">9000</td><td class="cell-oZm^"></td><td class="cell-LyNN"></td><td class="cell-Rzl@"></td><td class="cell-[yAr"></td><td class="cell-MSuH">11</td><td class="cell-Gr|V">SSMA IJCV’19;</td><td class="cell-_frr"><span class="selected-value select-value-color-blue">Synthetic</span></td><td class="cell-Z\bo"><span class="selected-value select-value-color-pink">Urban Street</span></td><td class="cell-ew?`"><span class="selected-value select-value-color-purple">Semantic Segmentation</span></td><td class="cell-CR;k"><a href="https://paperswithcode.com/sota/semantic-segmentation-on-synthia-cvpr16" class="url-value">https://paperswithcode.com/sota/semantic-segmentation-on-synthia-cvpr16</a></td><td class="cell-U}sm"></td></tr><tr id="e738af3b-9e16-40bf-a7d1-8afdaa024fde"><td class="cell-title"><a href="https://www.notion.so/SYNTHIA-Rand-e738af3b9e1640bfa7d18afdaa024fde">SYNTHIA-Rand</a></td><td class="cell-\[;t"><span class="selected-value select-value-color-red">Depth</span><span class="selected-value select-value-color-green">RGB</span></td><td class="cell-=Gd;">2016</td><td class="cell-{JVu">13407</td><td class="cell-oZm^"></td><td class="cell-LyNN"></td><td class="cell-Rzl@"></td><td class="cell-[yAr"></td><td class="cell-MSuH">11</td><td class="cell-Gr|V"></td><td class="cell-_frr"><span class="selected-value select-value-color-blue">Synthetic</span></td><td class="cell-Z\bo"><span class="selected-value select-value-color-pink">Urban Street</span></td><td class="cell-ew?`"><span class="selected-value select-value-color-purple">Semantic Segmentation</span></td><td class="cell-CR;k"><a href="https://paperswithcode.com/sota/semantic-segmentation-on-synthia-cvpr16" class="url-value">https://paperswithcode.com/sota/semantic-segmentation-on-synthia-cvpr16</a></td><td class="cell-U}sm"></td></tr><tr id="d2464137-2543-45b2-a8aa-0d9591f32b6e"><td class="cell-title"><a href="https://www.notion.so/Freiburg-Forest-d2464137254345b2a8aa0d9591f32b6e">Freiburg Forest</a></td><td class="cell-\[;t"><span class="selected-value select-value-color-red">Depth</span><span class="selected-value select-value-color-default">EVI</span><span class="selected-value select-value-color-default">NDVI</span><span class="selected-value select-value-color-orange">NIR</span><span class="selected-value select-value-color-yellow">NRG</span><span class="selected-value select-value-color-green">RGB</span></td><td class="cell-=Gd;">2016</td><td class="cell-{JVu">366</td><td class="cell-oZm^"></td><td class="cell-LyNN">230</td><td class="cell-Rzl@">136</td><td class="cell-[yAr">0</td><td class="cell-MSuH">6</td><td class="cell-Gr|V">SSMA IJCV’19;</td><td class="cell-_frr"><span class="selected-value">Real</span></td><td class="cell-Z\bo"><span class="selected-value select-value-color-red">Forest</span></td><td class="cell-ew?`"><span class="selected-value select-value-color-purple">Semantic Segmentation</span></td><td class="cell-CR;k"></td><td class="cell-U}sm"></td></tr><tr id="a4358115-b8e5-427d-8250-07fa6ee7ed74"><td class="cell-title"><a href="https://www.notion.so/Tokyo-Multi-Spectral-a4358115b8e5427d825007fa6ee7ed74">Tokyo Multi Spectral</a></td><td class="cell-\[;t"><span class="selected-value select-value-color-pink">InfraRed</span><span class="selected-value select-value-color-green">RGB</span></td><td class="cell-=Gd;">2017</td><td class="cell-{JVu">1569</td><td class="cell-oZm^"></td><td class="cell-LyNN">785</td><td class="cell-Rzl@">392</td><td class="cell-[yAr">392</td><td class="cell-MSuH">8</td><td class="cell-Gr|V">MFNet IROS’17;</td><td class="cell-_frr"><span class="selected-value">Real</span></td><td class="cell-Z\bo"><span class="selected-value select-value-color-pink">Urban Street</span></td><td class="cell-ew?`"><span class="selected-value select-value-color-purple">Semantic Segmentation</span></td><td class="cell-CR;k"></td><td class="cell-U}sm"></td></tr><tr id="631d35a4-03f4-4c1a-864a-6e9ff039f0c6"><td class="cell-title"><a href="https://www.notion.so/CATS-2-631d35a403f44c1a864a6e9ff039f0c6">CATS 2</a></td><td class="cell-\[;t"><span class="selected-value select-value-color-pink">InfraRed</span><span class="selected-value select-value-color-green">RGB</span></td><td class="cell-=Gd;">2019</td><td class="cell-{JVu">686</td><td class="cell-oZm^"></td><td class="cell-LyNN"></td><td class="cell-Rzl@"></td><td class="cell-[yAr"></td><td class="cell-MSuH">9/96</td><td class="cell-Gr|V"></td><td class="cell-_frr"><span class="selected-value">Real</span></td><td class="cell-Z\bo"><span class="selected-value select-value-color-yellow">Indoor</span><span class="selected-value select-value-color-purple">Outdoor</span></td><td class="cell-ew?`"><span class="selected-value select-value-color-purple">Semantic Segmentation</span></td><td class="cell-CR;k"></td><td class="cell-U}sm"></td></tr><tr id="c34f6c43-e0f4-499e-8156-a31a4c493c40"><td class="cell-title"><a href="https://www.notion.so/RANUS-c34f6c43e0f4499e8156a31a4c493c40">RANUS</a></td><td class="cell-\[;t"><span class="selected-value select-value-color-orange">NIR</span><span class="selected-value select-value-color-green">RGB</span></td><td class="cell-=Gd;">2018</td><td class="cell-{JVu">4k</td><td class="cell-oZm^">36k</td><td class="cell-LyNN"></td><td class="cell-Rzl@"></td><td class="cell-[yAr"></td><td class="cell-MSuH">10</td><td class="cell-Gr|V"></td><td class="cell-_frr"><span class="selected-value">Real</span></td><td class="cell-Z\bo"><span class="selected-value select-value-color-purple">Outdoor</span></td><td class="cell-ew?`"><span class="selected-value select-value-color-purple">Semantic Segmentation</span></td><td class="cell-CR;k"></td><td class="cell-U}sm"></td></tr><tr id="3e792d56-a22b-4f1f-a379-d06adcb041cc"><td class="cell-title"><a href="https://www.notion.so/DISCOMAN-3e792d56a22b4f1fa379d06adcb041cc">DISCOMAN</a></td><td class="cell-\[;t"><span class="selected-value select-value-color-red">Depth</span><span class="selected-value select-value-color-green">RGB</span></td><td class="cell-=Gd;">2019</td><td class="cell-{JVu">600k</td><td class="cell-oZm^"></td><td class="cell-LyNN"></td><td class="cell-Rzl@"></td><td class="cell-[yAr"></td><td class="cell-MSuH"></td><td class="cell-Gr|V"></td><td class="cell-_frr"><span class="selected-value select-value-color-blue">Synthetic</span></td><td class="cell-Z\bo"><span class="selected-value select-value-color-yellow">Indoor</span></td><td class="cell-ew?`"><span class="selected-value select-value-color-purple">Semantic Segmentation</span></td><td class="cell-CR;k"></td><td class="cell-U}sm"></td></tr><tr id="e88123d1-6c9e-4405-aea2-f92ad6897ebc"><td class="cell-title"><a href="https://www.notion.so/TartanAir-e88123d16c9e4405aea2f92ad6897ebc">TartanAir</a></td><td class="cell-\[;t"><span class="selected-value select-value-color-red">Depth</span><span class="selected-value select-value-color-brown">Disparity</span><span class="selected-value select-value-color-gray">LiDAR</span><span class="selected-value select-value-color-purple">Optical Flow</span><span class="selected-value select-value-color-green">RGB</span></td><td class="cell-=Gd;">2020</td><td class="cell-{JVu">1M+</td><td class="cell-oZm^"></td><td class="cell-LyNN"></td><td class="cell-Rzl@"></td><td class="cell-[yAr"></td><td class="cell-MSuH"></td><td class="cell-Gr|V"></td><td class="cell-_frr"><span class="selected-value select-value-color-blue">Synthetic</span></td><td class="cell-Z\bo"><span class="selected-value select-value-color-yellow">Indoor</span><span class="selected-value select-value-color-gray">Nature</span><span class="selected-value select-value-color-purple">Outdoor</span><span class="selected-value select-value-color-default">Public</span><span class="selected-value select-value-color-green">Rural</span><span class="selected-value select-value-color-blue">Scifi</span><span class="selected-value select-value-color-brown">Urban</span></td><td class="cell-ew?`"><span class="selected-value select-value-color-purple">Semantic Segmentation</span></td><td class="cell-CR;k"></td><td class="cell-U}sm"></td></tr><tr id="f4344a0f-e449-46be-a9e4-0f19202c1a95"><td class="cell-title"><a href="https://www.notion.so/nuScenes-f4344a0fe44946bea9e40f19202c1a95">nuScenes</a></td><td class="cell-\[;t"><span class="selected-value select-value-color-gray">LiDAR</span><span class="selected-value select-value-color-brown">RADAR</span><span class="selected-value select-value-color-green">RGB</span></td><td class="cell-=Gd;">2020</td><td class="cell-{JVu">1.4M RGB; 390k LIDAR; 1.4M RADAR</td><td class="cell-oZm^">389k</td><td class="cell-LyNN">850</td><td class="cell-Rzl@">150</td><td class="cell-[yAr"></td><td class="cell-MSuH"></td><td class="cell-Gr|V"></td><td class="cell-_frr"><span class="selected-value">Real</span></td><td class="cell-Z\bo"><span class="selected-value select-value-color-purple">Outdoor</span></td><td class="cell-ew?`"><span class="selected-value select-value-color-gray">Bounding Boxes</span><span class="selected-value select-value-color-yellow">Lidar Segmentation</span></td><td class="cell-CR;k"></td><td class="cell-U}sm"></td></tr></tbody></table></div></article></body></html>
