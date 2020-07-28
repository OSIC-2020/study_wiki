# git干货资料

## git
```text
    1.git 如何查看某个文件的提交历史
        git log -p file
    
    2.如何列出所有已合并到 master 的分支并删除
        # 列出所有已合并到 master 的分支
        $ git branch --merged master
        
        # 删除所有已合并到 master 的分支
        $ git branch --merged master | grep -v '^\*' | xargs git branch -d
```
## 项目管理工具平台
  [云效](https://devops.aliyun.com/) :阿里云企业级一站式DevOps平台，支持公共云、专有云和混合云多种部署形态，通过人工智能、自动化技术的应用提升开发者的研发效能，持续交付有效价值。
