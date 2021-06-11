<html>

<head>
	<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
	<title>I Am Rich</title>
	<style>
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

		li>ol:first-child,
		li>ul:first-child {
			margin-block-start: 0.6em;
		}

		ul>li {
			list-style: disc;
		}

		ul.to-do-list {
			text-indent: -1.7em;
		}

		ul.to-do-list>li {
			list-style: none;
		}

		.to-do-children-checked {
			text-decoration: line-through;
			opacity: 0.375;
		}

		ul.toggle>li {
			list-style: none;
		}

		ul {
			padding-inline-start: 1.7em;
		}

		ul>li {
			padding-left: 0.1em;
		}

		ol {
			padding-inline-start: 1.6em;
		}

		ol>li {
			padding-left: 0.2em;
		}

		.mono ol {
			padding-inline-start: 2em;
		}

		.mono ol>li {
			text-indent: -0.4em;
		}

		.toggle {
			padding-inline-start: 0em;
			list-style-type: none;
		}

		/* Indent toggle children */
		.toggle>li>details {
			padding-left: 1.7em;
		}

		.toggle>li>details>summary {
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
			height: 30vh;
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

		p>.user {
			opacity: 0.5;
		}

		td>.user,
		td>time {
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

		.code>code {
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

		.sans {
			font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol";
		}

		.code {
			font-family: "SFMono-Regular", Consolas, "Liberation Mono", Menlo, Courier, monospace;
		}

		.serif {
			font-family: Lyon-Text, Georgia, YuMincho, "Yu Mincho", "Hiragino Mincho ProN", "Hiragino Mincho Pro", "Songti TC", "Songti SC", "SimSun", "Nanum Myeongjo", NanumMyeongjo, Batang, serif;
		}

		.mono {
			font-family: iawriter-mono, Nitti, Menlo, Courier, monospace;
		}

		.pdf .sans {
			font-family: Inter, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC', 'Noto Sans CJK KR';
		}

		.pdf .code {
			font-family: Source Code Pro, "SFMono-Regular", Consolas, "Liberation Mono", Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC', 'Noto Sans Mono CJK KR';
		}

		.pdf .serif {
			font-family: PT Serif, Lyon-Text, Georgia, YuMincho, "Yu Mincho", "Hiragino Mincho ProN", "Hiragino Mincho Pro", "Songti TC", "Songti SC", "SimSun", "Nanum Myeongjo", NanumMyeongjo, Batang, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC', 'Noto Sans CJK KR';
		}

		.pdf .mono {
			font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC', 'Noto Sans Mono CJK KR';
		}

		.highlight-default {}

		.highlight-gray {
			color: rgb(155, 154, 151);
		}

		.highlight-brown {
			color: rgb(100, 71, 58);
		}

		.highlight-orange {
			color: rgb(217, 115, 13);
		}

		.highlight-yellow {
			color: rgb(223, 171, 1);
		}

		.highlight-teal {
			color: rgb(15, 123, 108);
		}

		.highlight-blue {
			color: rgb(11, 110, 153);
		}

		.highlight-purple {
			color: rgb(105, 64, 165);
		}

		.highlight-pink {
			color: rgb(173, 26, 114);
		}

		.highlight-red {
			color: rgb(224, 62, 62);
		}

		.highlight-gray_background {
			background: rgb(235, 236, 237);
		}

		.highlight-brown_background {
			background: rgb(233, 229, 227);
		}

		.highlight-orange_background {
			background: rgb(250, 235, 221);
		}

		.highlight-yellow_background {
			background: rgb(251, 243, 219);
		}

		.highlight-teal_background {
			background: rgb(221, 237, 234);
		}

		.highlight-blue_background {
			background: rgb(221, 235, 241);
		}

		.highlight-purple_background {
			background: rgb(234, 228, 242);
		}

		.highlight-pink_background {
			background: rgb(244, 223, 235);
		}

		.highlight-red_background {
			background: rgb(251, 228, 228);
		}

		.block-color-default {
			color: inherit;
			fill: inherit;
		}

		.block-color-gray {
			color: rgba(55, 53, 47, 0.6);
			fill: rgba(55, 53, 47, 0.6);
		}

		.block-color-brown {
			color: rgb(100, 71, 58);
			fill: rgb(100, 71, 58);
		}

		.block-color-orange {
			color: rgb(217, 115, 13);
			fill: rgb(217, 115, 13);
		}

		.block-color-yellow {
			color: rgb(223, 171, 1);
			fill: rgb(223, 171, 1);
		}

		.block-color-teal {
			color: rgb(15, 123, 108);
			fill: rgb(15, 123, 108);
		}

		.block-color-blue {
			color: rgb(11, 110, 153);
			fill: rgb(11, 110, 153);
		}

		.block-color-purple {
			color: rgb(105, 64, 165);
			fill: rgb(105, 64, 165);
		}

		.block-color-pink {
			color: rgb(173, 26, 114);
			fill: rgb(173, 26, 114);
		}

		.block-color-red {
			color: rgb(224, 62, 62);
			fill: rgb(224, 62, 62);
		}

		.block-color-gray_background {
			background: rgb(235, 236, 237);
		}

		.block-color-brown_background {
			background: rgb(233, 229, 227);
		}

		.block-color-orange_background {
			background: rgb(250, 235, 221);
		}

		.block-color-yellow_background {
			background: rgb(251, 243, 219);
		}

		.block-color-teal_background {
			background: rgb(221, 237, 234);
		}

		.block-color-blue_background {
			background: rgb(221, 235, 241);
		}

		.block-color-purple_background {
			background: rgb(234, 228, 242);
		}

		.block-color-pink_background {
			background: rgb(244, 223, 235);
		}

		.block-color-red_background {
			background: rgb(251, 228, 228);
		}

		.select-value-color-default {
			background-color: rgba(206, 205, 202, 0.5);
		}

		.select-value-color-gray {
			background-color: rgba(155, 154, 151, 0.4);
		}

		.select-value-color-brown {
			background-color: rgba(140, 46, 0, 0.2);
		}

		.select-value-color-orange {
			background-color: rgba(245, 93, 0, 0.2);
		}

		.select-value-color-yellow {
			background-color: rgba(233, 168, 0, 0.2);
		}

		.select-value-color-green {
			background-color: rgba(0, 135, 107, 0.2);
		}

		.select-value-color-blue {
			background-color: rgba(0, 120, 223, 0.2);
		}

		.select-value-color-purple {
			background-color: rgba(103, 36, 222, 0.2);
		}

		.select-value-color-pink {
			background-color: rgba(221, 0, 129, 0.2);
		}

		.select-value-color-red {
			background-color: rgba(255, 0, 26, 0.2);
		}

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
	</style>
</head>

<body>
	<article id="856d8519-759b-4788-9a3a-9771bdd88761" class="page sans">
		<header>
			<div class="page-header-icon undefined"><span class="icon">🔴</span></div>
			<h1 class="page-title">I Am Rich</h1>
			<table class="properties">
				<tbody>
					<tr class="property-row property-row-date">
						<th><span class="icon property-icon"><svg viewBox="0 0 14 14"
									style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.4);flex-shrink:0;-webkit-backface-visibility:hidden"
									class="typesDate">
									<path
										d="M10.8889,5.5 L3.11111,5.5 L3.11111,7.05556 L10.8889,7.05556 L10.8889,5.5 Z M12.4444,1.05556 L11.6667,1.05556 L11.6667,0 L10.1111,0 L10.1111,1.05556 L3.88889,1.05556 L3.88889,0 L2.33333,0 L2.33333,1.05556 L1.55556,1.05556 C0.692222,1.05556 0.00777777,1.75556 0.00777777,2.61111 L0,12.5 C0,13.3556 0.692222,14 1.55556,14 L12.4444,14 C13.3,14 14,13.3556 14,12.5 L14,2.61111 C14,1.75556 13.3,1.05556 12.4444,1.05556 Z M12.4444,12.5 L1.55556,12.5 L1.55556,3.94444 L12.4444,3.94444 L12.4444,12.5 Z M8.55556,8.61111 L3.11111,8.61111 L3.11111,10.1667 L8.55556,10.1667 L8.55556,8.61111 Z">
									</path>
								</svg></span>Created</th>
						<td><time>@Jun 10, 2021</time></td>
					</tr>
					<tr class="property-row property-row-url">
						<th><span class="icon property-icon"><svg viewBox="0 0 14 14"
									style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.4);flex-shrink:0;-webkit-backface-visibility:hidden"
									class="typesUrl">
									<path
										d="M3.73333,3.86667 L7.46667,3.86667 C8.49613,3.86667 9.33333,4.70387 9.33333,5.73333 C9.33333,6.7628 8.49613,7.6 7.46667,7.6 L6.53333,7.6 C6.01813,7.6 5.6,8.0186 5.6,8.53333 C5.6,9.04807 6.01813,9.46667 6.53333,9.46667 L7.46667,9.46667 C9.5284,9.46667 11.2,7.79507 11.2,5.73333 C11.2,3.6716 9.5284,2 7.46667,2 L3.73333,2 C1.6716,2 0,3.6716 0,5.73333 C0,7.124 0.762067,8.33453 1.88953,8.97713 C1.87553,8.83107 1.86667,8.6836 1.86667,8.53333 C1.86667,7.92013 1.98753,7.33447 2.2036,6.7978 C1.99267,6.4954 1.86667,6.12953 1.86667,5.73333 C1.86667,4.70387 2.70387,3.86667 3.73333,3.86667 Z M12.1095,5.28907 C12.1231,5.4356 12.1333,5.58307 12.1333,5.73333 C12.1333,6.34607 12.0101,6.9294 11.7931,7.46513 C12.0059,7.768 12.1333,8.13573 12.1333,8.53333 C12.1333,9.5628 11.2961,10.4 10.2667,10.4 L6.53333,10.4 C5.50387,10.4 4.66667,9.5628 4.66667,8.53333 C4.66667,7.50387 5.50387,6.66667 6.53333,6.66667 L7.46667,6.66667 C7.98187,6.66667 8.4,6.24807 8.4,5.73333 C8.4,5.2186 7.98187,4.8 7.46667,4.8 L6.53333,4.8 C4.4716,4.8 2.8,6.4716 2.8,8.53333 C2.8,10.59507 4.4716,12.2667 6.53333,12.2667 L10.2667,12.2667 C12.3284,12.2667 14,10.59507 14,8.53333 C14,7.14267 13.2375,5.93167 12.1095,5.28907 Z">
									</path>
								</svg></span>Github</th>
						<td><a href="https://github.com/Ankitkj1999/i_am_rich_flutter"
								class="url-value">https://github.com/Ankitkj1999/i_am_rich_flutter</a></td>
					</tr>
					<tr class="property-row property-row-select">
						<th><span class="icon property-icon"><svg viewBox="0 0 14 14"
									style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.4);flex-shrink:0;-webkit-backface-visibility:hidden"
									class="typesSelect">
									<path
										d="M7,13 C10.31348,13 13,10.31371 13,7 C13,3.68629 10.31348,1 7,1 C3.68652,1 1,3.68629 1,7 C1,10.31371 3.68652,13 7,13 Z M3.75098,5.32278 C3.64893,5.19142 3.74268,5 3.90869,5 L10.09131,5 C10.25732,5 10.35107,5.19142 10.24902,5.32278 L7.15771,9.29703 C7.07764,9.39998 6.92236,9.39998 6.84229,9.29703 L3.75098,5.32278 Z">
									</path>
								</svg></span>Level</th>
						<td><span class="selected-value select-value-color-red">Beginner</span></td>
					</tr>
					<tr class="property-row property-row-text">
						<th><span class="icon property-icon"><svg viewBox="0 0 14 14"
									style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.4);flex-shrink:0;-webkit-backface-visibility:hidden"
									class="typesText">
									<path
										d="M7,4.56818 C7,4.29204 6.77614,4.06818 6.5,4.06818 L0.5,4.06818 C0.223858,4.06818 0,4.29204 0,4.56818 L0,5.61364 C0,5.88978 0.223858,6.11364 0.5,6.11364 L6.5,6.11364 C6.77614,6.11364 7,5.88978 7,5.61364 L7,4.56818 Z M0.5,1 C0.223858,1 0,1.223858 0,1.5 L0,2.54545 C0,2.8216 0.223858,3.04545 0.5,3.04545 L12.5,3.04545 C12.7761,3.04545 13,2.8216 13,2.54545 L13,1.5 C13,1.223858 12.7761,1 12.5,1 L0.5,1 Z M0,8.68182 C0,8.95796 0.223858,9.18182 0.5,9.18182 L11.5,9.18182 C11.7761,9.18182 12,8.95796 12,8.68182 L12,7.63636 C12,7.36022 11.7761,7.13636 11.5,7.13636 L0.5,7.13636 C0.223858,7.13636 0,7.36022 0,7.63636 L0,8.68182 Z M0,11.75 C0,12.0261 0.223858,12.25 0.5,12.25 L9.5,12.25 C9.77614,12.25 10,12.0261 10,11.75 L10,10.70455 C10,10.4284 9.77614,10.20455 9.5,10.20455 L0.5,10.20455 C0.223858,10.20455 0,10.4284 0,10.70455 L0,11.75 Z">
									</path>
								</svg></span>Property</th>
						<td></td>
					</tr>
					<tr class="property-row property-row-select">
						<th><span class="icon property-icon"><svg viewBox="0 0 14 14"
									style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.4);flex-shrink:0;-webkit-backface-visibility:hidden"
									class="typesSelect">
									<path
										d="M7,13 C10.31348,13 13,10.31371 13,7 C13,3.68629 10.31348,1 7,1 C3.68652,1 1,3.68629 1,7 C1,10.31371 3.68652,13 7,13 Z M3.75098,5.32278 C3.64893,5.19142 3.74268,5 3.90869,5 L10.09131,5 C10.25732,5 10.35107,5.19142 10.24902,5.32278 L7.15771,9.29703 C7.07764,9.39998 6.92236,9.39998 6.84229,9.29703 L3.75098,5.32278 Z">
									</path>
								</svg></span>Status</th>
						<td><span class="selected-value select-value-color-yellow">In Progress 🙌</span></td>
					</tr>
				</tbody>
			</table>
		</header>
		<div class="page-body">
			<h1 id="bd03bfb9-05b7-46a2-9b74-e6babae0565e" class="">Overview</h1>
			<p id="41bcd470-29c9-4f71-8570-519928a92979" class="">This is a simple and static flutter application that
				displays an appbar and an asset image (diamond).</p>
			<h2 id="5e575987-4d61-47fe-bfb2-2ca7509c9d49" class="">GitHub</h2>
			<figure id="c96097f9-c919-4518-a219-324e47367359"><a href="https://github.com/Ankitkj1999/i_am_rich_flutter"
					class="bookmark source">
					<div class="bookmark-info">
						<div class="bookmark-text">
							<div class="bookmark-title">Ankitkj1999/i_am_rich_flutter</div>
							<div class="bookmark-description">A new Flutter application. This project is a starting
								point for a Flutter application.A few resources to get you started if this is your first
								Flutter project: For help getting started with Flutter, view our online documentation,
								which offers tutorials, samples, guidance on mobile development, and a full API
								reference.</div>
						</div>
						<div class="bookmark-href"><img src="https://github.com/favicon.ico"
								class="icon bookmark-icon" />https://github.com/Ankitkj1999/i_am_rich_flutter</div>
					</div><img
						src="https://opengraph.githubassets.com/bda8c5cf76c619053775964817cbc849de78d34ccf965d026e8292905817bfe2/Ankitkj1999/i_am_rich_flutter"
						class="bookmark-image" />
				</a></figure>
			<h3 id="ab668110-bf95-4c81-a392-4c5753601f27" class="">Problem Statement</h3>
			<ul id="20311165-5e4a-4467-a5c6-3d7aa966fc0d" class="bulleted-list">
				<li>This can be see and the introductiry app for the beginner.<ul
						id="279aee20-a314-4dc9-b6a6-170c0061047c" class="bulleted-list">
						<li>Through this app I was to learns the use of basic widgets in flutter.</li>
					</ul>
				</li>
			</ul>
			<h2 id="5ae951ab-222f-4d07-8f10-fbac54ab1ca2" class="">Success Criteria </h2>
			<ul id="ff45e830-4a10-4243-8ce4-c9477bed7111" class="bulleted-list">
				<li>The success criteria for this was to put an image and an appbar on the screen.</li>
			</ul>
			<h2 id="667321f0-c7f3-4ff8-ab91-9db287433a07" class="">Learnings</h2>
			<ul id="b4118ead-90e8-451d-98a0-705dd1150a33" class="toggle">
				<li>
					<details open="">
						<summary>Learned to put doen a very simple flutter app.</summary>
						<pre id="d674adb1-a7e3-484e-a1c8-4a2379320ad9" class="code code-wrap"><code>import &#x27;package:flutter/material.dart&#x27;;

void main() {
  runApp(
    MaterialApp(
      home: Scaffold(
        backgroundColor: Colors.blueGrey,
        appBar: AppBar(
          centerTitle: true,
          title: Text(&#x27;I Am Rich&#x27;),
          backgroundColor: Colors.blueGrey[800],
        ),
        body: Center(
          child: Image(
            image: AssetImage(&#x27;images/img3.png&#x27;),
          ),
        ),
      ),
    ),
  );
}</code></pre>
					</details>
				</li>
			</ul>
			<ul id="441604b1-7a92-436c-be39-77ebf63d4e3c" class="bulleted-list">
				<li>Use of <em><mark class="highlight-gray"><a
								href="https://api.flutter.dev/flutter/material/Scaffold-class.html">Scaffold</a></mark></em><em>
					</em>widget.<ul id="4b3bee92-6c17-404e-919e-23bc9ef509ca" class="bulleted-list">
						<li>In Scaffold I used the <a
								href="https://api.flutter.dev/flutter/material/Scaffold/body.html"><mark
									class="highlight-gray"><em>body</em></mark></a><a
								href="https://api.flutter.dev/flutter/material/Scaffold/body.html"> </a>and <a
								href="https://api.flutter.dev/flutter/material/Scaffold/appBar.html"><mark
									class="highlight-gray"><em>appBar</em></mark></a> parameters.</li>
					</ul>
				</li>
			</ul>
			<ul id="b40304d7-057d-4f6c-aa18-8198c2d23b05" class="bulleted-list">
				<li>Adding asset files and folders in the<a
						href="https://github.com/Ankitkj1999/i_am_rich_flutter/blob/master/pubspec.yaml"> </a><mark
						class="highlight-gray"><a
							href="https://github.com/Ankitkj1999/i_am_rich_flutter/blob/master/pubspec.yaml"><em>pubspec.yaml</em></a></mark>
					flile and then later using then on the app.</li>
			</ul>
			<pre id="0c030d06-6b66-4e87-b83b-1a6e8e4a31c9" class="code"><code># The following section is specific to Flutter.
flutter:

  # The following line ensures that the Material Icons font is
  # included with your application, so that you can use the icons in
  # the material Icons class.
  uses-material-design: true

  # To add assets to your application, add an assets section, like this:
  assets:
    - images/coal.png</code></pre>
			<ul id="14c78ad2-5885-4293-819b-2efa35b029fe" class="bulleted-list">
				<li>Creating app icons with <em><a href="http://appicon.co">appicon.co</a></em> and using then.<ul
						id="7deb7731-7473-407a-870b-a03821f24234" class="bulleted-list">
						<li>We can modify the fitting of the app icon through the android studio by following this path
							<mark class="highlight-orange"><em>android &gt; app &gt; src &gt; main &gt;
									res</em></mark><em> </em>and creating an <em>image asset</em> file.</li>
					</ul>
				</li>
			</ul>
			<ul id="afa2728b-86ea-48b4-9031-17e12197addd" class="bulleted-list">
				<li>We can modify the name of the flutter app for android by modifying this path <mark
						class="highlight-orange">android &gt; app &gt; src &gt; main &gt; AndroidManifest.xml.
					</mark>And for ios by modifying this path</li>
			</ul>
			<h2 id="7ff1652d-c5a0-4008-ad08-7bbdb782d22b" class="">Scope </h2>
			<p id="6235fb1e-a66c-498a-98e0-8c4b3d24a8a5" class="">Simple flutter app just for learning purposes.</p>
			<h2 id="bc7cb21f-5b87-4701-a2c9-8ec48b3723a0" class="">Screenshots \ Gifs</h2>
			<figure id="ff414265-f039-406f-bede-ea66eb24febf" class="image"><a
					href="images/Screenshot.png"><img style="width:384px"
						src="I%20Am%20Rich%20ff414265f039406fbedeea66eb24febf/Untitled.png" /></a>
				<figcaption>I Am Rich Flutter App</figcaption>
			</figure>
			<p id="2bd9adec-d6b3-414f-87be-30da5cf89d19" class="">
			</p>
		</div>
	</article>
</body>

</html>
