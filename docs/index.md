# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.



![](/assets/image-20240719153625199.png)

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.



```yaml
#cd C:/Users/Admin/dir_name
#mkdocs serve  更新
#git remote add origin https://github.com/SongTao2021/mymkdocs.git
#mkdocs build
#mkdocs gh-deploy
plugins:
    - search
    - img2fig
site_name: 福赛创新
#theme:
  #name: readthedocs
theme:
  name: material
  
nav: 
  - 主页: index.md
  - 文档:
    - V316烧录方式: V316.md
    - C++: about.md
  - 测试:
    - 测试1: V316_download.md
    - 测试2: 回调函数.md
    - 测试3: markdown快捷键测试.md
```

{{ read_csv('path_to_table.csv') }}
