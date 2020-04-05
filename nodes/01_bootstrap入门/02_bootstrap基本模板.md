## bootstrap 基本模板

我使用的是 bootstrap 3 的版本

### 初始化模板

```html
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <!-- 开启视口模式, 方便在移动端显示 -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>撩课学院-IT人的自我成长社区</title>
    <!-- 引入Bootstrap核心样式文件(必须) -->
    <link rel="stylesheet" href="../node_modules/bootstrap/dist/css/bootstrap.css">
    <!-- 引入自己的样式或其它文件-->
    <link rel="stylesheet" href="css/index.css">
  </head>
  <body>
  <!-- html结构 -->

  <!-- 如果需要使用 js 插件, 则需要导入-->
  <!-- 由于 Bootstrap 的 JS 插件依赖 JQuery, 所以需要导入 JQuery-->
  <script src="../node_modules/jquery/dist/jquery.js"></script>
  <!-- 引入所有的 Bootstrap 的 JS 插件 -->
  <script src="../node_modules/bootstrap/dist/js/bootstrap.js"></script>
  <!-- 引入自己的 JS 代码 -->
  <script src="js/index.js"></script>
  </body>
</html>
```



