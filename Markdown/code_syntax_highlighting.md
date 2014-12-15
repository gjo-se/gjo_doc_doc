# Code Highlighting

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