**QUESTION :**

```Create a Webpage with Inline and Block Elements. Demonstrate understanding of <span> vs <div>, and other elements.```

**CODE :**
```
<!DOCTYPE html>
<html>
<head>
  <title>Inline vs Block</title>
  <style>
    body {
      text-align: center;
      font-family: sans-serif;
      background-color: #f0f0f0;
    }

    div {
      background-color: #a2d5f2;
      padding: 10px;
      margin: 10px;
    }

    span {
      background-color: #ffe699;
      padding: 3px 6px;
    }

    hr {
      width: 50%;
      margin: 20px auto;
    }
  </style>
</head>
<body>

  <h1>Inline vs Block Elements</h1>

  <h2>Block Elements</h2>
  <div>This is a div (block)</div>
  <p>This is a paragraph (block)</p>

  <h2>Inline Elements</h2>
  <p>This is <span>span</span> inside text.</p>
  <p>This is <b>bold</b> and <i>italic</i> (inline)</p>

  <h2>div vs span</h2>
  <div>This is a div</div>
  <p><span>This is a span</span> beside text</p>

  <hr>
  <p>Made by Jaseer</p>

</body>
</html>
```

**OUTPUT :**

