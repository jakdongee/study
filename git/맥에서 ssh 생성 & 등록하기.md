ssh 생성
--------

```bash
$ cd ~/.ssh
ssh-keygen -t rsa -b 4096 -C "[git account mail]"
```

### 생성된 ssh 공개키 확인

```bash
$ cat id_rsa.pub
```

확인된 공개키를 github 에 등록

### 생성한 ssh 기기에 등록

```bash
$ ssh-add id_rsa
```
