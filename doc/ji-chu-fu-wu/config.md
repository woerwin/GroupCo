### Config

##### 用于查找config目录下得配置参数，提供get与set方法

#### Config::Get\($key\)

```
use Config;

//文件名::key
Config::get('app::environment');//指获取config/app.php中的environment值
```

#### Config::Set\($fileName, $key, $value\)

```
use Config;
//也可以重新设置变量值
Config::set('app', 'environment', 'dev');
```



