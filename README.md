# yyxutils
项目开发过程中常用的一些开发工具，减少自己的重复代码量。


##安装
```
pip install yyxutils
```

##使用
```
import yyxutils as yu
```


##API
```
yu.file.save(dump_path, content, keep_ori) # 将str/np.array保存到指定文件中

yu.list.rm_elem(input_list, elem) # 检查elem是否存在于input_list中，如果存在则删除

yu.video.info(mp4_path) # 返回mp4信息，fps, total frames, image width, image height

yu.checkdir(dir_path) # 检查dir_path是否存在，如果不存在则创建

yu.load_yaml(yaml_path) # load yaml 并将其结构化和打印
```