![hexo-theme-apollo](https://cloud.githubusercontent.com/assets/9530963/13026956/08e76eca-d277-11e5-8bfc-2e80cea20a0d.png)

## 文档

- [中文文档](https://github.com/YanWQ-monad/hexo-theme-apollo/blob/master/doc/doc-zh.md)
- [Document](https://github.com/YanWQ-monad/hexo-theme-apollo/blob/master/doc/doc-en.md)

## 安装

``` bash
hexo init Blog 
cd Blog 
npm install
npm install --save hexo-renderer-pug hexo-generator-feed hexo-generator-sitemap hexo-browsersync hexo-generator-archive
git clone https://github.com/YanWQ-monad/hexo-theme-apollo.git themes/apollo
```

## 启用

修改 `_config.yml` 的 `theme` 配置项为 `apollo`:

```yaml
theme: apollo

# 在归档页面显示所有文章
# 需要上面安装的 hexo-generator-archive 插件支持
archive_generator:
    per_page: 0
    yearly: false
    monthly: false
    daily: false
```

## 更新

``` bash
cd themes/apollo 
git pull
```

## License

MIT
