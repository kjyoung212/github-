# github- 정리

STUDY!!!


!!!깃허브 연결 에러 났을시 하는것
git remote set-url origin git@github.com:kjyoung212/CC2.git

1. 만일 ssh-keygen 이 생성되지 않았다면 생성해줘야 합니다. (만일 기존에 생성되어있다면 3번부터 해주시면 됩니다.)
ssh-keygen -t rsa -C "이메일"

2. 생성한 ssh 키는 /home/유저/.ssh/id_rsa 에 생성되었습니다.

3. 먼저 해당 폴더로 이동후 ssh 키를 복사해줘야 합니다.
?
1
cat /home/유저/.ssh/id_rsa.pub

---------------------------------------- 연결 에러 났을시 이렇게 해주면 된다.!
