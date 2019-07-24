# cron-selector

#### 项目介绍
基于bootstrap的cron表达式选择器的jQuery插件，提供按年，按月，按周，按小时，按天，按分钟周期触发的选择策略。

![界面示例](https://raw.githubusercontent.com/wiki/zhanghuang03/cron-selector-master/images/menu.saveimg.savepath20190724183559.jpg "界面示例")

![界面示例](https://raw.githubusercontent.com/wiki/zhanghuang03/cron-selector-master/images/menu.saveimg.savepath20190724183628.jpg "界面示例")


#### 使用示例

依赖jquery和bootstrap，需要先导入bootstrap样式和jquery以及bootstrap的javascript脚本。


```
<!DOCTYPE html>

<html lang="en" xmlns="http://www.w3.org/1999/xhtml">
<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- 最新版本的 Bootstrap 核心 CSS 文件 -->
    <link rel="stylesheet" href="https://cdn.bootcss.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
    
    <script src="https://code.jquery.com/jquery-3.3.1.min.js"></script>

    <!-- 最新的 Bootstrap 核心 JavaScript 文件 -->
    <script src="https://cdn.bootcss.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
    
    <script src="cron-selector.js"></script>
    
    <title></title>
</head>
    <body>
        
        <div class="container" style="margin-top:30px;text-align:center;">
            <div>
                <label>Cron表达式选择器</label><br><br>
            </div>
            <form class="form-inline">
                <div class="form-group">
                    <input id="cronDemo" name="cronDemo" class="form-control" />
                </div>
            </form>
        </div>
    
    <script>
            $(function () {
                $("#cronDemo").cronSelector();                
            });
    </script>
        
    </body>
</html>
```

original project github link: https://github.com/hsal/cronGen
