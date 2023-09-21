# tech-at-work

📖 整理工作中技术相关的信息，也会包含一些实践和练习。

## Webpack 生态

- [speed-measure-webpack-plugin](https://www.npmjs.com/package/speed-measure-webpack-plugin) - 分析各阶段的打包耗时。
- [happypack](https://www.npmjs.com/package/happypack) - 多线程构建，作者已放弃维护。
- [thread-loader](https://www.npmjs.com/package/thread-loader) - 多线程构建，原理涉及node worker。
- [cache-loader](https://www.npmjs.com/package/cache-loader) - 缓存构建后的资源达到二次构建提速。
- [webpack-merge](https://www.npmjs.com/package/webpack-merge) - 合并webpack配置。

## NodeJs 生态

- [dotenv](https://www.npmjs.com/package/dotenv) - 扩展nodejs环境变量。
- [dotenv-expand](https://www.npmjs.com/package/dotenv-expand) - 和dotenv搭配使用。
- [np](https://github.com/sindresorhus/np#readme) - npm publish npm发布工具。
- [npkill](https://github.com/voidcosmos/npkill) - 快速找到目录下node_modules文件夹，i/o操作用go编写的，效率非常高。
- [yalc](https://www.npmjs.com/package/yalc) - package发布到本地，避免npm link繁琐操作。
- [chokidar](https://github.com/paulmillr/chokidar) - 监控文件变化，没有fs.watch奇怪的问题。
- [tsx](https://github.com/esbuild-kit/tsx) - 可以直接运行TypeScript和ESM的NodeJs Runtime。
- [zx](https://github.com/google/zx) - 在NodeJs环境中编写Bash脚本，google出品。
## 好文推荐

- [Virtual DOM is pure overhead](https://svelte.dev/blog/virtual-dom-is-pure-overhead) svelteJS的作者对Virtual DOM的见解。
- [Chrome View Transitions API](https://developer.chrome.com/docs/web-platform/view-transitions/) 谷歌支持页面过渡动画 View Transitions API
- [Unlocking view transitions in SvelteKit 1.24](https://svelte.dev/blog/view-transitions) 在 SvelteKit 1.24 中使用 View Transitions
- [Astro View Transitions doc](https://docs.astro.build/en/guides/view-transitions/) 前端“岛屿”架构的框架 Astro 3.0 支持 View Transitions
- [Astro View Transitions](https://developer.chrome.com/blog/astro-view-transitions/) Chrome Developer Blog Astro View Transitions

## 2023 你应该试试这些

- 20230908 Bun 发布 1.0。强劲的性能、与 Web Api 保持一致。试着用她的包管理工具链，例如：使用 bun 初始化 react-native 项目。
