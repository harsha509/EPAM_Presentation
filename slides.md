---
highlighter: shiki
lineNumbers: false
drawings:
  persist: false
title: Se 4.6.0
---

# Selenium 4

New features and 🔋🔋🔋🔋 included

<div class="uppercase text-sm tracking-widest">
Sri Harsha
</div>

<div class="abs-bl mx-14 my-12 flex">
  <img src="https://wearecommunity.io/assets/webpack/data/7a0eddf5d235f0598f9834c7b3cd8040.svg" class="h-8">
  <div class="ml-3 flex flex-col text-left">
    <div><b>EPAM INDIA</b></div>
    <div class="text-sm opacity-50">Nov. 8th, 2022</div>
  </div>
</div>


<style>

.neonText {
  color: #fff;
  text-shadow:
      0 0 1px #fff,
      0 0 1px #fff,
      0 0 5px #fff,
      0 0 22px #0fa,
      0 0 32px #0fa,
      0 0 22px #0fa,
      0 0 32px #0fa,
      0 0 31px #0fa;
}
</style>
---
layout: 'intro'
---

# Sri Harsha

<div class="leading-8 opacity-80">
Technical Leadership committee (TLC) <span style="color: #00FF00">SeleniumHQ</span> <br>
Committer and member of <span style="color: #ea5906"> WebDriverIO </span><br>
Senior Test Engineer EPAM Systems <br>
I ❤️ JavaScript and Will code for cup of ☕☕☕☕

</div>

<div class="my-10 grid grid-cols-[40px,1fr] w-min gap-y-4">
  <ri-github-line class="opacity-50"/>
  <div><a href="https://github.com/harsha509" target="_blank">harsha509</a></div>
  <ri-twitter-line class="opacity-50"/>
  <div><a href="https://twitter.com/sri_harsha509" target="_blank">sri_harsha509</a></div>
</div>

<img src="logo/PP2.jpeg" class="rounded-full w-40 abs-tr mt-16 mr-12"/>

---
layout: center
---

<div class="container">
    <h2 class="neonText">Top Three Selenium Features </h2>
 </div>

<style>

.neonText {
  color: #fff;
  text-shadow:
      0 0 1px #fff,
      0 0 1px #fff,
      0 0 5px #fff,
      0 0 22px #0fa,
      0 0 32px #0fa,
      0 0 22px #0fa,
      0 0 32px #0fa,
      0 0 31px #0fa;
}
h2 {
  font-size: 4.2rem;
  animation: flicker 1.5s infinite alternate;     
}

/* Flickering animation */
@keyframes flicker {
    
  0%, 18%, 22%, 25%, 53%, 57%, 100% {
      text-shadow:
      0 0 4px #fff,
      0 0 11px #fff,
      0 0 19px #fff,
      0 0 40px #0fa,
      0 0 80px #0fa,
      0 0 90px #0fa,
      0 0 100px #0fa,
      0 0 150px #0fa;
  }
  
  20%, 24%, 55% {        
      text-shadow: none;
  }    
}
h2 {
 font-size: 1.8rem;
}

body {
  font-size: 20px;
  font-family: "Vibur", sans-serif;
  background-color: #010a01;
}
</style>

---
layout: center
---

# 1. WebAuthn - Virtual Authenticator

---
name: VirtualAuth
layout: center
---

<div class="grid grid-cols-[3fr,2fr] gap-4">
  <div class="text-center pb-4">
    <div class="opacity-60 mb-2 text-sm">
    <br>
    <br>
    WebAuth is an API enables servers to register and authenticate 
    user using public key cryptography instead of password.<br><br>
    WebAuth is standard is a universally accepted W3C standard.
    </div>
  </div>
  <div class="border-l border-gray-400 border-opacity-25 !all:leading-12 !all:list-none my-auto">

  - Public-key based authentication
  - Protection against phishing 
  - Invulnerable to password attacks
  - Less Impact on data breaches
  </div>
</div>


---
layout: center
class: text-center
---

# WebAuth in Action with [WebAuthn.io](https://webauthn.io/)

---
layout: center
class: text-center
---

# More info on WebAuth at https://www.w3.org/TR/webauthn-2/

---
layout: center
---

# 2. WebDriver BiDi

---

<div class="grid grid-cols-2 gap-x-4"><div>

# WebDriver

Selenium WebDriver (commonly referred to as just WebDriver) was released in 2011.<br><br>
It allows users to automate browsers with WebDriverAPI. <br> <br>
WebDriver has been a standard solution for cross-browsing testing in web development ever since then.

<div v-click>

###### Pros

- W3C Standard
- Cross Browser API

###### Cons

- HTTP Model
- Pull-Model
- New Connection

</div>

</div><div>

# CDP

CDP was developed to communicate between Chrome and DevTools.

<div v-click>

###### Pros

- Open Source
- Extensible

###### Cons

- Not Standard
- Applicable to chromium based browsers
- Designed for DevTools and not for tess

</div>
</div></div>

---
layout: center
class: text-center
---

# WebDriver BiDi <MarkerCore />
A New Browser Automation protocol

The idea of WebDriver BiDi is to make a new standard protocol for browser automation, which will be based on the bidirectional transport protocol (WebSocket or pipes). <br><br>
The idea is to get the best from 2 worlds: WebDriver and CDP.

---
layout: center
class: text-center
---

# WebDriver BiDi <MarkerCore />
A New Browser Automation protocol

The idea of WebDriver BiDi is to make a new standard protocol for browser automation, which will be based on the bidirectional transport protocol (WebSocket or pipes). <br><br>
The idea is to get the best from 2 worlds: WebDriver and CDP.

---

# Advantages

<div v-click>

###### Pros

- W3C standardisation
- Reduces CDP complexity
</div>
<br><br>

<div v-click>

###### Applications

- Mobile device emulation
- Geolocation emulation
- Network listeners

</div>
<br><br>
<div v-click>

###### Limitations

- Implementation In Progress (but available in beta)

</div>

---
layout: center
---

# More at https://w3c.github.io/webdriver-bidi/

---
layout: center
class: text-center
---

# 3. Selenium Manager

Automatic Driver Management 

🔋🔋🔋🔋 Included in Selenium 4.6.0

---

# SeleniumManager <Marker class="text-blue-400">4.6.0</Marker>

<div v-click> 

- Developed in Rust 

</div>

<div v-click> 

- A CLI tool

</div>

<div v-click> 

- Beta 1

</div>

<div v-click> 

- Integrated in Selenium 4.6.0

</div>


<div v-click> 

- No need of downloading driver and placing in path

</div>

<div v-click> 

- No need of driver management library in Selenium Ecosystem

</div>

<div v-click> 

- Binaries available at https://github.com/SeleniumHQ/selenium/tree/trunk/common/manager

</div>

---
layout: center
class: text-center
---

# SeleniumManager Demo
A demo on chrome, Firefox and Edge with Java Bindings

---
layout: center
class: text-center
---

# SeleniumManager CLI and options
A view of supported options and usage

---
layout: center
class: text-center
---

# Next Steps



