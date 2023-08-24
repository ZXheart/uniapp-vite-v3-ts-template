# 使用vscode开发uniapp的一些配置模板(2023/08/24)

- 所用技术
  - uniapp+vite+vue3+ts+uni-ui(这里没有引入pinia,根据需要自己添加)
- 遇到的问题
  1. page.json / manifest.json会报错,因为json文件不允许注释
     - 解决办法: 1. 设置 2. 搜文件关联 3. key:pages.json; value:json
