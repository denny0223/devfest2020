title: 咻的～滑進 App - 透過 Firebase Dynamic Link 順暢導入使用者
output: index.html

--

<h1 style="font-size: 48px">
  咻的～滑進 App - <br />
  透過 Firebase Dynamic Link <br />
  順暢導入使用者
</h1>
<br />
<br />
## GDG DevFest Taiwan 2020
## Denny Huang
## 2020/10/17

--

### Slide link
<h1 style="font-size: 52px">
https://denny.one/devfest2020/
</h1>

--

### Online Q & A

<div align="center">
  <img width="300px" src="img/slido.png" />
</div>
## https://sli.do/firebase

--

<br />
<h2 style="font-size: 60px">
  <b>Denny Huang</b>
</h2>

* OPass project coordinator

* SITCON co-founder, Chief Coordinator of 2013, 2014

* 雷亞遊戲 Rayark Inc.

* [About me](https://denny.one)

--

<h1 style="font-size: 62px">
  Firebase Dynamic Links / Deep Link
</h1>

--

<div align="center">
  <img width="300px" src="img/dynamic-links-logo.png" />
</div>
## [Firebase Dynamic Links](https://firebase.google.com/docs/dynamic-links)

--

<div align="center">
  <img height="500px" src="img/link-analytics.png" /><br />
  追蹤使用者安裝來源
</div>

--

<div align="center">
  <video height="600px" controls>
    <source src="webex.mp4" type="video/mp4">
  </video>
</div>

--

<br />
<div align="center">
  <img width="300px" src="img/opass-logo.png" />
</div>
<br />
## https://opass.app/

--

<h1 style="font-size: 60px">
  https://hackmd.io/@OPass
</h1>

--

<div align="center">
  <img height="600px" src="img/opass-side.png" />
  <img height="600px" src="img/opass-fastpass.png" />
</div>

--

<div align="center">
  <img height="600px" src="img/opass-ticket.png" />
  <img height="600px" src="img/opass-booth.png" />
</div>

--

<div align="center">
  <video height="500px" controls>
    <source src="installed.mp4" type="video/mp4">
  </video>
  <video height="500px" controls>
    <source src="not-installed.mp4" type="video/mp4">
  </video>
  <br />
  <h2>　installed　　　not installed</h2>
</div>

--

### 信件內連結
<br />
<br />
<br />
`https://opass.app/r/SITCON_2020/40440179-278d-4c38-aa8f-bafadcf76f41`

--

<br />
<div align="center">
  <img width="400px" src="img/doc-create-link.png" />
</div>

--

- `https://dl.opass.app/`

- `https://opass.app/r/SITCON_2020/40440179-278d-4c38-aa8f-bafadcf76f41`

- ` https://dl.opass.app/?link=https%3A%2F%2Fopass.app%2Fopen%2F%3Fevent_id%3DSITCON_2020%26token%3D40440179-278d-4c38-aa8f-bafadcf76f41&isi=1436417025&ibi=app.opass.ccip&apn=app.opass.ccip&amv=40 `

--

# [Debugging](https://firebase.google.com/docs/dynamic-links/debug)
<br />
## `?d=1`

--

<div align="center">
  <img height="500px" src="img/debug.png" />
  https://dl.opass.app/open?d=1
</div>

--

### Link for user

- `https://opass.app/r/SITCON_2020/40440179-278d-4c38-aa8f-bafadcf76f41`

### Deep Link

- `https://opass.app/open/?event_id=SITCON_2020&token=40440179-278d-4c38-aa8f-bafadcf76f41`

--

### Dynamic Link

- ` https://dl.opass.app/?`

  `link=https%3A%2F%2Fopass.app%2Fopen%2F%3Fevent_id%3DSITCON_2020%26token%3D40440179-278d-4c38-aa8f-bafadcf76f41&`

  `isi=1436417025&`

  `ibi=app.opass.ccip&`

  `apn=app.opass.ccip&`

  `amv=40 `

--

# [Parameters](https://firebase.google.com/docs/dynamic-links/create-manually)

--

<div align="center">
  <video height="600px" controls>
    <source src="not-install-web.mp4" type="video/mp4">
  </video>
</div>

--

### Social Meta Tag parameters
<div align="center">
  <br />
  <img height="500px" src="img/social-media-tag.png" />
  <img height="500px" src="img/social-media-tag1.png" />
</div>

--

# Analytics parameters

--

### iOS 14
<div align="center">
  <img width="300px" src="img/ios14.png" />
</div>
- [#5893](https://github.com/firebase/firebase-ios-sdk/issues/5893)

- [#5905](https://github.com/firebase/firebase-ios-sdk/issues/5893)

- Version 6.28.0 - July 14, 2020

- [iOS 14 剪貼簿竊資恐慌，隱私與便利的兩難](https://medium.com/zrealm-ios-dev/8a04443024e2)

--

# Q & A

--

<h1 style="font-size: 72px">
  Thanks for listening!
</h1>

<br /><br /><br />
<div align="center">
  <img style="width:100px;" src="./img/by-sa.png" />
</div>
<h2 style="font-size: 18px">
本投影片採用<a href="http://creativecommons.org/licenses/by-sa/3.0/tw/" target="_blank">創用 CC「姓名標示—相同方式分享 3.0 台灣」授權條款</a>
</h2>

