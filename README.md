## Hugo Stellar

[Hexo theme stellar](https://github.com/xaoxuu/hexo-theme-stellar) 的 [Hugo 移植版本](https://github.com/Yharimium/hugo-stellar) 。

**此 fork 為適配hugo v0.145**

## Demo

Yharim Area：<https://yharim.com/>

## Preview

![image](https://github.com/Yharimium/hugo-stellar/assets/97100140/01f07272-8959-4d2d-b40e-0dc388daa47a)


## Usage

> 请使用 hugo extended `v0.109.0` 或更新版本。

全自动建站脚本：

``` sh
mkdir mySite
cd mySite
git init
git submodule add https://github.com/Yharimium/hugo-stellar themes/hugo-stellar
cp -R themes/hugo-stellar/exampleSite/* .

```

预览网站：

```
hugo server
```

如果网站不能实时显示最新效果的话请使用：

```
hugo server --disableFastRender
```

## Content Management

`content` 目录结构：支持 `posts`（博客）和 `docs`（文档）两种模式。

```
content/
├── posts/
│   ├── test.md         <- example.com/posts/test.html
│   └── folder/
│       ├── index.md    <- example.com/posts/index.html
│       └── test.md     <- example.com/posts/folder/test.html
└── docs/
    └── test.md         <- example.com/docs/test.html
```

## Experimental Features

### 扩展语法支持

> ~~注：此功能可能存在 bug，请谨慎使用。~~
>
> 此功能已稳定。

支持在正文中使用 mkdocs 语法，例如：

```
!!! note
    `markdown` text
```

详见 [扩展语法支持](https://yharim.com/posts/%E5%BB%BA%E7%AB%99/%E6%89%A9%E5%B1%95%E8%AF%AD%E6%B3%95%E6%94%AF%E6%8C%81/)
