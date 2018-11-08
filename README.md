Directory Lister - The simple PHP directory lister
==================================================
Created by, [Chris Kankiewicz](http://www.ChrisKankiewicz.com)


Introduction
------------

Directory Lister is a simple PHP script that lists the contents of any web-accessable directory and
allows navigating there within. Simply upload Directory Lister to any directory and get immediate
access to all files and sub-direcories under that directory. Directory Lister is written in PHP and
distributed under the [MIT License](http://www.opensource.org/licenses/mit-license.php).

Like this project? Want to keep it free? [Make a donation](https://cash.me/$ChrisKankiewicz).

More info available at <http://www.directorylister.com>


Features
--------

  * Extremely simple installation
  * Creates on-the-fly listing of any web-accessable directory
  * Custimizable sort order of files/folders
  * Easily define hidden files to be excluded from the listing


Requirements
------------

Directory Lister requires PHP 5.3+ to work properly.  For more information on PHP, please visit
<http://www.php.net>.


Installation
------------

  1. Copy `resources/default.config.php` to `resources/config.php`
  2. Upload `index.php` and the `resources` folder to the folder you want listed
  3. Upload additional files to the same directory as index.php


文件结构
---

假设你的虚拟主机根目录是 /home/wwwroot/xxx.xx  
```
/home/wwwroot/xxx.xx/
├─ resources/
│   ├ themes/
│   │ └ bootstrap/
│   │    ├ css/
│   │    ├ fonts/
│   │    ├ img/
│   │    ├ js/
│   │    ├ default_footer.php # 底部公共文件 #
│   │    ├ default_header.php # 顶部公共文件（可以放网站流量统计代码） #
│   │    └ index.php # 网页主文件，其中可以修改顶部公告栏内容 #
│   │
│   ├ DirectoryLister.php
│   ├ config.php
│   └ fileTypes.php
│
├ README.html # 该文件夹页面内的 说明简介文件 #
├ index.php
│
├─ 其他文件夹/
│   ├ 其他文件.txt
│   └ README.html # 该文件夹页面内的 说明简介文件 #
│
└ 其他文件.txt
```
via [逗比根据地](https://doub.io/dbrj-3/)

Troubleshooting
---------------

Ensure you have the latest version of Directory Lister installed.

Verify that you have PHP 5.3 or later installed. You can verify your PHP version by running:

    php --version


Contact Info
------------

Contact us via our mailling list at [Directory-Lister@GoogleGroups.com](mailto:Directory-Lister@GoogleGroups.com)
or [join our Google Group](https://groups.google.com/forum/?fromgroups#!forum/directory-lister) online.

Follow Directory Lister on Twitter at [@DirectoryLister](https://twitter.com/directorylister) or
follow the developer at [@PHLAK](https://twitter.com/PHLAK)

Find a problem or bug with Directory Lister?
[Open an issue](https://github.com/DirectoryLister/DirectoryLister/issues) on GitHub.


License
-------

Directory Lister is distributed under the terms of the
[MIT License](http://www.opensource.org/licenses/mit-license.php).
Copyright 2017 [Chris Kankiewicz](http://www.chriskankiewicz.com)
