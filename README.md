# HW2

*[GitHub repository](https://github.com/JungHyun21/HW2.git)*


### config
- working directory인 dev로 이동 후, 깃허브 계정을 연결해줘야함
- config --global user.name "닉네임" 
- config --global user.email "이메일" 
- config --list : 입력한 정보 출력


![image](https://user-images.githubusercontent.com/76541903/117542673-8597ed80-b054-11eb-829d-daa3b419e34f.png)

<br><br>

### init
- git 저장소 생성
- 로컬 레포지토리를 생성함


![image](https://user-images.githubusercontent.com/76541903/117542924-939a3e00-b055-11eb-87f6-1a19b384de89.png)

<br><br>

### status
- 로컬 레포지토리의 상태 확인
- on branch master : 아직 branch를 생성 혹은 branch off 하지 않았기 때문에 현재는 master branch 상에 상주하고 있다는 뜻
- Untracked files : 파일이 git의 관리하에 존재하지 않을 때, 이 목록에 뜸
- 따라서 add 명령어를 통해 staging Area로 파일을 보내줘야함


![image](https://user-images.githubusercontent.com/76541903/117543105-5f734d00-b056-11eb-9846-91965b9a4b77.png)

<br><br>

### add
- 이제는 파일이 git 관리하에 있는 파일로 변경됨
- 즉, staging Area로 이동함


![image](https://user-images.githubusercontent.com/76541903/117543185-b416c800-b056-11eb-807c-4120841fca48.png)

<br><br>

### commit
- 지금까지의 변경사항을 로컬 레포지토리로 이동시킴
- commit -m "message" : 지금까지의 변경사항을 commit하고 commit message를 남김


![image](https://user-images.githubusercontent.com/76541903/117543281-15d73200-b057-11eb-98f8-f3e846bbbe28.png)

<br><br>

### remote
- 원격 레포지토리와 로컬 레포지토리를 연결해줌


![image](https://user-images.githubusercontent.com/76541903/117543340-5a62cd80-b057-11eb-98ee-cc6d39bc1916.png)

<br><br>

### push
- commit한 변경사항을 원격 레포지토리에 push함
- push -u origin master : master branch를 생성하고 여기에 push하라는 명령어

