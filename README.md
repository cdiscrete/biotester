bio(logy) tester
=========

 帮助天朝高中生背诵生物基础知识的小网页。原本是用于背语文的，经过粗略的更改后可以遮挡任意用{}标记的内容，来达到背东西的目的。

 如何使用?
--------------------------------------
打开``bio.html``，找到第一份示例：
```html
<p><span>1、 蔗糖水解生成{葡萄糖}和{果糖}；乳糖水解生成{葡萄糖}和{半乳糖}；麦芽糖水解生成{两份葡萄糖}。</span></p>
```
其中，用{*}标记的就是要遮挡的内容。
要添加多个项目，只需在``<body></body>``之间添加形如以上的内容即可。
 离线使用?
--------------------------------------
显然可以。然而你可能需要一份离线的[jQuery](https://github.com/jquery/jquery/)，同时更改``bio.html``中的jQuery引用部分。
注意，目前使用的是``http://code.jquery.com/jquery-1.9.0.min.js``，其他版本**并未**经过测试。

 Credit
--------------------------------------
Originally By [@cxqn](https://twitter.com/cxqn) Edited by [@c_discrete](http://discrete.tk)

 协议
--------------------------------------
```
/*
 * Copyright (C) 2013 Discrete Chen
 *
 * This program is free software: you can redistribute it and/or modify
 * it under the terms of the GNU General Public License as published by
 * the Free Software Foundation, either version 3 of the License, or
 * (at your option) any later version.
 *
 * This program is distributed in the hope that it will be useful,
 * but WITHOUT ANY WARRANTY; without even the implied warranty of
 * MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 * GNU General Public License for more details.
 *
 * You should have received a copy of the GNU General Public License
 * along with this program.  If not, see <http://www.gnu.org/licenses/>.
 */
```