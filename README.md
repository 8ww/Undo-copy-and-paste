# Undo-copy-and-paste

# 解除复制粘贴

```js
javascript:!function () { function t(e) { e.stopPropagation(), e.stopImmediatePropagation && e.stopImmediatePropagation() } document.querySelectorAll("*").forEach(e => { "none" === window.getComputedStyle(e, null).getPropertyValue("user-select") && e.style.setProperty("user-select", "text", "important") }), ["copy", "cut", "contextmenu", "selectstart", "mousedown", "mouseup", "mousemove", "keydown", "keypress", "keyup"].forEach(function (e) { document.documentElement.addEventListener(e, t, {capture: !0}) }), alert("解除限制成功啦！") }();
```
