# backToTop
[DEMO](https://tangyunyun.github.io/backToTop/demo.html)

#### Contribution Guides:

Based on zeptojs, encapsulation of a back top plug

1. Import file

   ```
   <script src="zepto.min.js"></script>
   <script src="backToTop.js"></script>
   ```

2. then

   ```
   $('.element').backToTop({
     type:'doubleTap',
     duration:500,
     target:100
   })
   ```

#### documentation

options

- type {String}, default is 'tap'
  - doubleTap, longTap, tap, click
- target {Number}, Moving target point
- duration {Number} Moving of time
  - must be ms
- easing {String}, Moving of easing
  - linear, ease-in, ease-out

#### How to build your own BackToTop

```
git clone https://github.com/tangyunyun/backToTop.git
```

```
bower install tinyBack
```

```
npm install tiny-back -D

```

#### Questions?

If you have any questions, please contact me.

#### [LICENSE

MIT

#### npm address

[https://www.npmjs.com/package/tiny-back](https://www.npmjs.com/package/tiny-back)