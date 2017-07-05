This is a test file

--配置自己的用户名和邮箱--
git config --global user.name ""
git config --global user.email ""
--查看本地是否存在ssh key--
cd ~/.ssh 或cd .ssh
--生成ssh key 填写自己的邮箱--
ssh-keygen -t rsa -C "email@email.com"
--将生成好的ssh key配置到github中--
···
--测试是否成功--
ssh -T git@github.com
···
--本地创建目录--
mkdir fileName
--进入目录--
cd fileName
--git初始化--
git init 
--在.git 文件夹下有文件可直接上传--
	git add fileName
	git commit -m "fileDescribe"
	git remote add origin git@github.com:XXXXXX/XXXXXXXXXt.git
	git push -u origin master
--刷新github--
--本地创建文件--
echo "fileContent" > fileName.**# Ra-GitHub-Test
