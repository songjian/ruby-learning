# Rails环境搭建

## 常用命令

```bash
# 创建rails项目
rails new new_project_name

# 启动服务
rails s

# 创建数据库
rake db:create

# 删除数据库
rake db:drop

# 执行迁移
rake db:migrate
```

## 资源预处理

### 禁止生成控制器静态资源

```ruby
config.generators do |g|
  g.assets false
end
```

## 参考网站

* [http://rubyonrails.org/](http://rubyonrails.org/)
