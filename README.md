# CodeHighlighter
This library was made to highlight code in websites. So if you have an element in your page that contains code, you just call a function on it and everything gets a specific class. Then CSS makes ist look similar to what you are used to from Notepad++. So far I have implemented HTML, CSS, JavaScript and PHP. There might be things that are not marked or that are marked incorrectly, so if you find a mistake just let me know. Also, you should avoid valid html-tags inside of your code element (they might confuse the browser!). I.e. you shouldn't have a &lt;/html> but instead you could use \&lt;/html>, which the browser would not recognize as the html being closed.

An example can be seen in the two example files 'example.html' and 'example.js'. The example.js just calls the function on the code elements from the example.html. The PHP code I used as an example is from XENUX, a free and open-source CMS (<a href="https://github.com/sveneberth/xenux" title="https://github.com/sveneberth/xenux" target="_blank">https://github.com/sveneberth/xenux</a>. The specific code is from <a href="https://github.com/sveneberth/xenux/blob/master/index.php" title="https://github.com/sveneberth/xenux/blob/master/index.php" target="_blank">https://github.com/sveneberth/xenux/blob/master/index.php</a>)

Example can be seen in <a href="http://jsfiddle.net/LBBO/1vngx7ey/" title="JSfiddle with example files" target="_blank">this fiddle</a>.

Requires jQuery.

Copyright (C) 2015  Michael David Kuckuk

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <a href="http://www.gnu.org/licenses/" target="_blank" title="http://www.gnu.org/licenses/"><http://www.gnu.org/licenses/></a>.
