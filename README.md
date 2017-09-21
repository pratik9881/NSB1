# 用 React, Redux 构建的 2048 游戏

2048 是一个经典的消除小游戏，基于 React 和 Redux 的最佳实践构建一个好玩又好看的小游戏是我这段时间以来的目标。

👉 [开始游戏](https://devrsi0n.github.io/React-2048-game/)

## 预览

<a href="https://devrsi0n.github.io/React-2048-game/">
  <img src="https://github.com/devrsi0n/React-2048-game/blob/master/screenshot.png" width="500px" alt="screenshot">
</a>

## 填坑记录

在写烟花动画的时候发现怎么调都没效果，仔细对比了下 webpack 编译后的 css 文件发现所有的 @keyframes
的名字都加了 hash 值（也就是当成普通的局部 css 类名），解决办法就是在 @keyframes 的名字前面和整个 scss 文件添加伪类 :global，可以参考烟花的 scss 文件，这不是完美的解决办法，后续再深挖一下。

## License

[MIT](http://opensource.org/licenses/MIT)