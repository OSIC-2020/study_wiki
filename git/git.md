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
 
