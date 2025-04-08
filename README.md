# Whisper documentation

When writing documentation, consider the following questions:

- Why did we make this decision?
- What are the benefits of doing it this way?
- What did this enable us to do?

## 🛠️ Components you can use in your documentation:

### 1. Codeblock: create a `pre` html element like so:

```html
<pre class="brush: js">
function hello():
    return "hello"
</pre>
```

You can choose from the following languages:

- Python
- Bash
- Javascript

### 2. Subtabs: Each tab has subtabs attached to it:

```html
<a href="#line2">Choosing Technologies</a>
<ul class="nav">
  <li><a href="#line2_1">Frontend</a></li>
  <li><a href="#line2_2">Server</a></li>
  <li><a href="#line2_3">Database</a></li>
</ul>
```

If you want to add a functioning subtab, simply add it to the nav list, and give the element that you want to scroll to on click the same id as the one specified in the href. For example:

```html
<li><a href="#line2_4">Deployment</a></li>
```

Where you'd have a title `deployment` using the following structure and id:

```html
<h4 id="line2_4">Deployment</h4>
```

[Visit the docs](https://whisper-inc.github.io/docs)
