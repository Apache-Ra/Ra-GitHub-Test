This is a test file

--�����Լ����û���������--
git config --global user.name ""
git config --global user.email ""
--�鿴�����Ƿ����ssh key--
cd ~/.ssh ��cd .ssh
--����ssh key ��д�Լ�������--
ssh-keygen -t rsa -C "email@email.com"
--�����ɺõ�ssh key���õ�github��--
������
--�����Ƿ�ɹ�--
ssh -T git@github.com
������
--���ش���Ŀ¼--
mkdir fileName
--����Ŀ¼--
cd fileName
--git��ʼ��--
git init 
--��.git �ļ��������ļ���ֱ���ϴ�--
	git add fileName
	git commit -m "fileDescribe"
	git remote add origin git@github.com:XXXXXX/XXXXXXXXXt.git
	git push -u origin master
--ˢ��github--
--���ش����ļ�--
echo "fileContent" > fileName.**# Ra-GitHub-Test
