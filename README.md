# sayho
aaaaa
dli@dli-desktop:$ cd Downloads
사용자의 현재 위치를 Downloads로 변경

 dli@dli-desktop:~/Downloads$ git clone
원격 저장소의 코드를 컴퓨터로 변경
 
 dli@dli-desktop:~/Downloads$ ls
폴더 내의 파일과 폴더 목록을 보여줌
 
 dli@dli-desktop:~/Downloads$ cd jetson-fan-ctl
현재 위치에서 'jetson-fan-ctl'이라는 폴더로 이동
 
 Downloads/jetson-fan-ctl$ sudo sh install.sh
sudo'를 사용하여 관리자 권한으로 스크립트를 실행하고, 'install.sh'라는 스크립트 파일을 실행

sudo apt-get upgrade
시스템에 설치된 모든 패키지를 최신 버전으로 업그레이드

sudo apt-get update
모든 소스의 패키지 정보를 업데이트하고 다운로드


sudo apt install python3-pip
파이썬 3 버전을 사용하기 위해 필요한 패키지 관리자인 pip를 설치

sudo pip3 list
시스템에 설치된 파이썬 패키지를 나열

sudo -H pip3 install -U jetson-stats
jetson-stats'라는 Python 패키지를 설치하고 업그레이드

rc@rc-desktop:~$ pip3 list| grep jetson
'jetson'이라는 단어를 포함하는 모든 설치된 패키지를 검색하여 나열

rc@rc-desktop:~$ reboot
시스템을 다시 시작

rc@rc-desktop:~$ jtop
시스템의 리소스 사용 상태를 실시간으로 모니터링

ifconfig
네트워크 인터페이스의 정보 확인
