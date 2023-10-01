# 目录结构

| 名称           | 功能                                                         |
| -------------- | ------------------------------------------------------------ |
| `_includes`    | 小模块，属于 HTML 文件的一部分，可以在多个页面中复用，比如导航（navigation）、脚注（footer）等 |
| `_layouts`     | 布局文件，相当于一类页面（比如博客类页面）的“父类”           |
| `_posts`       | 稿件,用于存放博客文章                                        |
| `_draft`       | 博客草稿，不会被构建成静态文件，也不会公开                   |
| `_data`        | 网站所需要的数据文件（相当于一个小型数据库），格式包括 JSON、YAML、CSV 和 TSV，支持全局访问。 |
| `assets`       | 静态文件                                                     |
| `_pages`       | 页面文章                                                     |
| `_site`        | 用于存放项目构建完成之后所生成的静态文件，也就是说，静态网站的所有文件都会来源于此，其中 CSS 文件、JS 文件以及图片文件，会存放在该目录下的 assets 文件夹中。 |
| `_config.yml`  | 项目的配置文件，一些全局配置会写在这个文件内                 |
| `Gemfile`      | 它指定了你想要使用的gem的位置和版本                          |
| `Gemfile.lock` | 依赖安装完后，生成一个`Gemfile.lock`文件                     |
| `index.html`   | 主页                                                         |
| `404.html`     | 404页面                                                      |
| `README.md`    |                                                              |

## 运行

安装依赖

`bundle install`

运行

`bundle exec jekyll serve`或`jekyll serve`

# 主题
 minimal-mistakes-jekyll
