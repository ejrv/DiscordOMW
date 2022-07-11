# DiscordOMW
DiscordOnMyWay! Is a Discord CSS Modification to change Discord Design And API To the Good Old 2015 Discord
Just Some ;)

(Browser) How to Use: 

1. Open https://discord.com/app/ On your Browser. (e.g. Chrome)

2. Ctrl + Shift + i

3. Paste This Code In your Console (CSS Exploit):

```js
const injectCss = (id, css) => {
  const style = document.createElement('style');
  style.id = id;
  style.innerText = css;
  document.head.appendChild(style);
  return style;
}
```

4. Last Step!: Now inject the theme:

```
@import url(https://xyzenix.github.io/XYZenixThemes/DTM-16-V5/DTM-16.css);
:root {
 --showRtcConnectionStatusIcon: block; /* show the vc ping/status icon | block = show | none = hide */
 --jumboEmojiSize: 2rem; /* Old - 2rem | New - 3rem */
}
```

5. E n j o y
