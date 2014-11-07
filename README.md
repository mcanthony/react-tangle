# react-tangle

A [tangle.js](http://worrydream.com/Tangle/)-style numeric input for React.js.

# api

**required**

```
<TangleText
  value={numeric value}
  onChange={function to be called on change} />
```

**optional**

```
onInput={function}
className={string, default 'react-tangle-input'}
min={numeric, default -Infinity}
max={numeric, default Infinity}
step={numeric, default 1}
format={function, function(x) { return x; }}
disabled={boolean, default false}
```

Step is a ratio of pixels moved by mouse versus change in the number.
