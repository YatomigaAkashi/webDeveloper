## 图片显示

#### 图片类型：jpeg/jpg png gif

- jpeg/jpg: 大图，压缩比高，有损压缩

- png：支持透明色，小图标可以使用，大图不要使用，体积太大

- gif： 支持动画，透明

#### \<img>标签

- href: 资源路径

- alt: 图像无法显示时的替代文本

## 链接

#### \<a>链接详解

- href：

    - \#: 如果路径后有#，则#的后面则可以成为锚点与html元素绑定跳转
    
    - mailto:XXX@163.com 邮件url，会调用邮件应用
    
    - tel:999 会调用手机上的拨号功能
    
    - 下载: 如果浏览器无法代理资源，则会提供资源下载

- target: 在何处打开链接
    
    - _blank: 新开窗口
    
    - _self: 当前窗口，默认值
    
    - 自定义值：如果不存在则新开窗口，存在则在该窗口加载
