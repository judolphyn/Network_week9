# Network_week9
9th Week Homework : report suricata rule

suricata 설치 후, 디렉토리에 test.rules 작성

설치 : https://m.blog.naver.com/PostView.nhn?blogId=skyon1111&logNo=221030199899&proxyReferer=https:%2F%2Fwww.google.com%2F

sudo suricata -s test.rules -i <interface name> 입력해 실행.
  
이후 사이트 접속 시 /var/log/suricata의 fast.log에 찍힘.
