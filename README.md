# Habanita Theme for Obsidian

This is a quiet and comfortable dark theme for Obsidian.

**Author:** Nikos
**Version:** 1.0.0

![It looks like this](/img/habanita-big.png)

### For a better experience

• You can download and activate the plugin *'Rainbow-colored-sidebar'*
• Add this css snippet :

---
```css
img {
    border-radius: 10px;
    width: 100%;
    height: auto;
}

/* CRT Scanline Effect habanita Theme */
body::before {
  content: "";
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: repeating-linear-gradient(
    0deg,
    rgba(0, 255, 65, 0.03),
    rgba(0, 255, 65, 0.03) 1px,
    transparent 1px,
    transparent 2px
  );
  pointer-events: none;
  z-index: 9999;
}
```
