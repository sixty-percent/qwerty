# About qwerty
Welcome to qwerty ヽ(´∀｀)
- [Download the zip](https://codeload.github.com/thousandjapan/qwerty/zip/master)

qwerty is Simple, Clean, and Efficient Design Framework.
It's naturally responsive.

## Why it's awesome

qwerty is completely simple css framework. It's under active development.
- Around 1000 lines of unminified CSS.
- You don't need any compiling or installing. This is as easy as typing "qwerty".

# How to use

## Getting started

There are a couple ways to use qwerty:
- [Download the zip](https://codeload.github.com/thousandjapan/qwerty/zip/master)
- Clone the repo: `git clone https://github.com/thousandjapan/qwerty.git`

## What's in the download?

The zip file includes qwerty's core CSS(Normalize.css is contained), and an index.html as a starting point.

```
qwerty/
├── index.html
├── css/
│   ├── qwerty.css(normalize.css is contained.)
│   └── style.css
├── js/
│   └── pushy.js
└── images/
    └── favicon.ico

```


# Grid System
The folloing is relation of contents.

```
<div class="wrap">
  <div class="pack">
    <div class="row">
      <div class="six col"><h1>First Content</h1></div>
      <div class="four col"><h1>Second Content</h1></div>
      <div class="two col"><h1>Second Content</h1></div>
    </div>
  </div>
</div>
```

qwerty requires the element is added classname **.wrap** to wrap all site contents.
**.pack** is container of contents.

# Components

## Text Selector
Related to text style, use **tx-xxxx**,
For example:
- **.tx-center**  
- **.tx-right**  
- **.tx-color**  

## Color List
.xxxx-dark (#333333)
.xxxx-smoke (#F5F5F5)

## Visiblity
- **.show-xs** Visible (max-width: 550px) Screen: Like a Mobile devices.  
- **.show-sm** Visible (max-width: 750px) Screen: Like a Phablet devices.  
- **.show-md** Visible (max-width: 1000px) Screen: Like a Tablet devices.  
- **.show-lg** Visible (max-width: 1200px) Screen: Like a Desktop devices.  
- **.show-xl** Visible (min-width: 1200px) Screen: Like a Desktop HD devices.  

- **.hide-xs** Unvisible (max-width: 550px) Screen: Like a Mobile devices.  
- **.hide-sm** Unvisible (max-width: 750px) Screen: Like a Phablet devices.  
- **.hide-md** Unvisible (max-width: 1000px) Screen: Like a Tablet devices.  
- **.hide-lg** Unvisible (max-width: 1200px) Screen: Like a Desktop devices.  
- **.hide-xl** Unvisible (min-width: 1200px) Screen: Like a Desktop HD devices.  

# Theming

Coming soon.

# Extensions

Coming soon.

## Browser support

- Chrome latest
- Firefox (Unverified)
- Opera (Unverified)
- Safari (Unverified)
- IE (Unverified)

## License

[open-source MIT license](https://github.com/thousandjapan/qwerty/blob/master/LICENSE).

## Acknowledgement

qwerty was created by [Hiro(@hiro__dev)](https://twitter.com/hiro__dev).
