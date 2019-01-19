# dev-cli

封装常用的开发操作到一个命令行工具.

譬如最常用的根据模板自动生成项目初始目录和配置文件.

```$javascript
// 生成一个基于webpack作为构建工具的项目
mkdir bar
cd bar
jdev init wepback
// 会生成以下目录结构     
    bar
        build
              webpack
                      index.js
                      config.js
                      prod.js
                      dev.js
        src
        .gitignore
        package.json
        README.me
```