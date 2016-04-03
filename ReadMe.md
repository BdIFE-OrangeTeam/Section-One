## [第一阶段任务](http://ife.baidu.com/task/all)


### 一、任务目录
* [任务一: 零基础HTML编码](http://bdife-orangeteam.github.io/Section-One/build/task-1.html) (`完成`)
* [任务二: 零基础HTML及CSS编码（一）](http://bdife-orangeteam.github.io/Section-One/build/task-2.html) (`完成`)
* [任务三: 三栏式布局](http://bdife-orangeteam.github.io/Section-One/build/task-3.html) (`完成`)
* [任务四: 定位和居中](http://bdife-orangeteam.github.io/Section-One/build/task-4.html) (`完成`)
* [任务五: 零基础HTML及CSS编码（二）](http://bdife-orangeteam.github.io/Section-One/build/task-5.html)(`完成`)
* [任务六: 零基础HTML及CSS编码（二）](http://bdife-orangeteam.github.io/Section-One/build/task-6.html)(`完成`)
* [任务七: 实现常见的技术产品官网的页面架构及样式布局](http://bdife-orangeteam.github.io/Section-One/build/task-7.html) (`完成`)
* [任务八: 响应式网格（栅格化）布局](http://bdife-orangeteam.github.io/Section-One/build/task-8.html) (`完成`)
* 任务九: 使用HTML/CSS实现一个复杂页面
* [任务十: Flexbox 布局练习](http://bdife-orangeteam.github.io/Section-One/build/task-10.html) (`完成`)
* 任务十一: 移动Web页面布局实践
* 任务十二: 学习CSS 3的新特性

### 二、成员
* [Eason](https://github.com/whatwewant)
* [Synyo](https://github.com/Synyo)

### 三、如何加入
* Team Name: 橙橙子 
* Email to Administer: [uniquecolesmith@gmail.com](mailto:uniquecolesmith@gmail.com)

## 四、代码工具
* vim (或 Atom `推荐`, 或者 sublime)
* gulp
* html + sass + js
* (当然你也可以用自己的工具)

### 五、文件结构
* src: 源文件目录
* build: 编译最终目录 (要演示的文件都要放在该目录下)
* src/index.html: 你的html源文件
* src/sass/app.scss: 你的scss文件
* src/js/app.js: 你的js文件
* (你可以自己设置)

```
.
├── build
│   ├── css
│   ├── images
│   ├── js
│   ├── task-1.html
│   ├── task-2.html
│   ├── task-3.html
│   ├── task-4.html
│   ├── task-5.html
│   ├── task-6.html
│   └── task-7.html
├── gulpfile.js
├── LICENSE
├── package.json
├── ReadMe.md
└── src
    ├── css
    │   ├── app.css
    │   └── ReadMe.md
    ├── fonts
    │   └── ReadMe.md
    ├── images
    ├── index.html
    ├── js
    └── sass
```

### 六、如何启动
* Initial(初始化)
    * `npm install`
* Develop Mode(开发)
    * `npm run start`
    * `npm run start --index task-8.html` 设置浏览器默认打开路径`/task-8.html`
* Release Mode(发布)
    * `npm run build`

### 七、欢迎PR
