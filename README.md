SimpleHtmlDom
===================

__Simple HTML DOM port to [SimpleFramework](https://github.com/PeratX/SimpleFramework), optimized for those html files which cannot be correctly parsed by DOMDocument__

	This program is free software: you can redistribute it and/or modify
	it under the terms of the GNU General Public License as published by
	the Free Software Foundation, either version 3 of the License, or
	(at your option) any later version.

	This program is distributed in the hope that it will be useful,
	but WITHOUT ANY WARRANTY; without even the implied warranty of
	MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
	GNU General Public License for more details.

	You should have received a copy of the GNU General Public License
	along with this program.  If not, see <http://www.gnu.org/licenses/>.

Introduction
-------------
The way to convert the plain html into DOM, now available in objects.
```php
SimpleHtmlDom::initDomFromFile(string $url, bool $useIncludePath = false, $context = null, $offset = -1, bool $lowercase = true, bool $forceTagsClosed = true, string $targetCharset = SimpleHtmlDom::DEFAULT_TARGET_CHARSET, bool $stripRN = true, string $defaultBRText = SimpleHtmlDom::DEFAULT_BR_TEXT, string $defaultSpanText = SimpleHtmlDom::DEFAULT_SPAN_TEXT)
SimpleHtmlDom::initDomFromString(string $str, bool $lowercase = true, bool $forceTagsClosed = true, string $targetCharset = SimpleHtmlDom::DEFAULT_TARGET_CHARSET, bool $stripRN = true, string $defaultBRText = SimpleHtmlDom::DEFAULT_BR_TEXT, string $defaultSpanText = SimpleHtmlDom::DEFAULT_SPAN_TEXT)
```

 * Original Website: http://sourceforge.net/projects/simplehtmldom/
 * Original author S.C. Chen <me578022@gmail.com>

Get SimpleHtmlDom
-------------
__[Releases](https://github.com/PeratX/SimpleHtmlDom/releases)__