## 简介
To get this working in Firefox, you have to open `about:config`. Once there, enter `network.protocol-handler.expose.vlc` in the search field and create it as a boolean. Once created, set the value to `false`.

You are probably interested in my [Open with VLC](https://github.com/stefansundin/open-with-vlc) browser extension.


## 使用
```html
<a href="vlc://http://xxxx/test.mp4">
        vlc播放器
 </a>
```
