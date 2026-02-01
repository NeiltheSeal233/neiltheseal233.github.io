以后每次站点目录下执行 hugo 命令后，再到public下执行推送命令：
hugo
cd public
git add -A
git commit -m "[介绍，随便写点什么，比如日期]"
git push -u origin main
