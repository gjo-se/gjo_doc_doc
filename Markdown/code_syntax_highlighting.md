# Code Highlighting

## Navigation

* [Readme](../README.md)
 * [Markdwon](markdown.md)
   * [Useful Helper](helper.md)
   * [Header](header.md)
   * [Emphasis](emphasis.md)
   * [List](list.md)
   * [Links](links.md)
   * [Images](images.md)
   * [Code Highlighting](code_syntax_highlighting.md)
   * [Tables](tables.md)
   * [Blockquotes](blockquotes.md)
   * [Inner HTML](inner_html.md)
   * [Horizontal Rule](horizontal_rule.md)
   * [Line Breaks](line_breaks.md)
   * [Escaping](escaping.md)


## Single-Line

\`phpinfo();\`

---

`phpinfo();`

## Multi-Line

### HTML

\``` html
&lt;b&gt;tag&lt;/b&gt;
\```

---

```html
<b>tag</b>
```

### JavaScript

\```javascript
var s = "JavaScript syntax highlighting";
alert(s);
\```
---

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

### PHP

\```php
\$EM_CONF[$_EXTKEY] = array(
    'title' => 'gjo_doc_doc',
    'description' => 'How to build a documentation for your Extension',
    'category' => '',
    'author' => 'Gregory Jo',
    'author_email' => 'gregor.jo@gjo-se.com',
    'author_company' => 'gjo-se.com',
    ),
);
\```
---

```php
$EM_CONF[$_EXTKEY] = array(
    'title' => '^gjo_example_documentation',
    'description' => 'How to build a documentation for your Extension',
    'category' => '',
    'author' => 'Gregory Jo',
    'author_email' => 'gregor.jo@gjo-se.com',
    'author_company' => 'gjo-se.com',
    ),
);
```

## Complete list and how to write the language names:
[highlight.js demo page](https://highlightjs.org/static/demo/)