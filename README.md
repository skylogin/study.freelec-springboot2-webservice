# freelec-springbot2-webservice

#### linux 설정

JDK8 설치
```sudo yum install -y java-1.8.0-openjdk.devel.x86_64```

JDK 변경
```sudo /usr/sbin/alternatives --config java```

JDK 삭제
```sudo yum remove java-1.7.0-openjdk```

타임존 변경
```sudo rm /etc/localtime```
```sudo ln -s /usr/share/zoneinfo/Asia/Seoul /etc/localtime```

HostName변경 (파일 안 HOSTNAME 변경)
```sudo vi /etc/sysconfig/network```

Host 등록 (파일 안 127.0.0.1 뒤에 삽입)
```sudo vi /etc/hosts```