## �鿴
```
ls -al �鿴�����ļ�
```
## �����ļ�
```
touch **

cat **  �鿴�ļ�����

vi ** ����༭״̬

�༭�� ��esc�˳��༭״̬,
esc + :wq �����˳�
ǿ���˳� q!
```
## �ӵ��ݴ���
```
git add **(��Ҫ�ŵ��ļ���)
git add . (��������ļ�)
��git add -A
```

## �ύ����ʷ��
```
git commit -m "****"
```
## �Աȴ���
Ĭ���ǹ��������ݴ���
```
git diff

git diff --cached  �ݴ�������ʷ����

git diff master(��֧��) ����������ʷ��
```
## git checkout �ļ���
```
���ݴ������ص�������
```
## �ع�
```
git log ����ǰ�Լ�֮ǰ����־
git reset --hard �汾��

git reflog �����е���־
```

### ��֧����
- �鿴��֧
```
git branch
```
- ������֧
```
git branch <branchName>
```
- �л���֧
```
git checkout <branchName>
```
- ɾ����֧(�����Լ�ɾ���Լ�)
```
git branch -D <branchName>
```
- �������л���֧(�൱���ڵ�ǰ��֧�Ļ����ϸ���һ��)
```
git checkout -b <branchName>
```
- �ϲ����� (�ڵ�ǰ��֧�� �ϲ�<branchName>,��<branchName>�Ĵ���ϲ�����ǰ��֧��)
```
git merge <branchName>
```

## �����ղֿ�
- �����ղֿ�,дһ���ֿ���
```
new respository
```
- ����Ҫ��


```
git log --grep=me ������עΪme��
git log --author=zhufeng ��������Ϊ����ύ��
```

- �������ﴴ��һ���������ݵ��ļ�(>> ��ʾ��������, > �Ḳ��ԭ�����ļ�)
```
echo ".idea" >> .gitignore
```

- ����Զ�̵�ַ
```
git add
git commit -m ""
git remote add origin <url>
git remote -v �鿴���й���
git remote rm <name>

```

- �Ƶ�Զ�̵�ַ
```
git push origin master -u (upstream�´��ύ����������origin master)
git push origin master
```


