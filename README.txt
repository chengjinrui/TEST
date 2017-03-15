文档小记 

	GIT 使用

	首先在working dir 里面写自己的东西 无所谓随便写
	git status 查看git状态
	git add 把对工作区的修改提交到暂存区中 
	git commit -m '一个描述或者记录' 写下记录并且将修改推到master中 
	git log 查看git日志

		
		git diff <file> 与版本库之间的对比 看看修改了啥东西
	
	git log --pretty=oneline 显示的是当前状态下的操作 如果你回滚了 回滚的操作在这里看不到 回滚之前的修改在这里也看不到
	git reflog 查看历史包括了各种操作甚至是回滚操作都有 显示的内容的第一项是一个唯一的id表示

	git reset 
	git checkout

