html-componet
=============

base on bootstrap 
```php
//配置参数
return Array(
    'debug'=> true,
    'db'=>Array(
        'host'=>'127.0.0.1',
        'port'=>'3306',
        'dbname'=>'image',
        'username'=>'root',
        'password'=>'',
    ),
    'image'=>Array(
        'url'=>'',
        'host'=>'img.p.cc',
        'path'=>'/image',           //  图片源文件目录
        'virtual'=>'/cache/',      //  图片缓存目录
        'image_root'=>'/source', //  上传根目录
        'tmppath'=> '/tmp',         //  /data/file/tmp 上传临时文件
        'chmod'  => 0777,         //  创建的缓存文件夹权限
    ),
    'measure' => Array(
        '150x100',
        '120x80',
        '30x30',
        '800*600',
        '', //原图
        '300x180',
        '800',
        '300',
        '350',
        '600',
    ),
    'header'=>array(
        'charset'=> 'utf-8'
    ),
);
```
