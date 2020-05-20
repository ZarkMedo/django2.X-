### django 2.2.12脚手架
#### 1. 创建项目
- 在根目录创建apps和utils空packages

#### 2. 修改mysql驱动，以及修复django连接mysql驱动bug
[django的mysql驱动bug](http://119.3.32.55:8090/archives/pythondjangobug)

#### 3. 逆向生成models
```bash
# 生成model
python manage.py inspectdb
# 创建app user,将所有的models导入user的models.py中
python manage.py inspectdb > user/models.py
```

