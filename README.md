# ArduinoMonitoring
 Arduino로 조도센서의 값을 받아와 C# WPF로 시각화해주는 프로그램입니다.

## 프로젝트 정보
### 설치
- Visual Studio, Arduino, MySQL

### 사용 방법
- Photocell.ino 실행 후 조도센서 연결
- MySQL을 열어 iot_sensordata_database.sql을 실행 후 쿼리 실행
- Visual Studio를 이용하여 AMTest.sln 파일을 실행 
- Ctrl + F5 후 PORT를 자동으로 읽어오면 Arduino에 연결된 PORT 선택 후 Connect
- 또는 위 과정 없이 시뮬레이션 시작


## 실행화면
### 1. Main 화면
![Arduino PhotoRegister](https://user-images.githubusercontent.com/70622083/92350522-38a1f700-f114-11ea-923e-a72bd498ead5.png)
### 2. 실행 Connect
![CDS_Winform](https://user-images.githubusercontent.com/71310919/93295773-c96d8680-f828-11ea-82d4-f1cbcabd61ef.png)
### 3. 도움말
![Arduino PhotoRegister_정보](https://user-images.githubusercontent.com/70622083/92350565-52dbd500-f114-11ea-85ec-dff9aa51abe0.png)
### 4. My SQL
![CDS_MYSQL](https://user-images.githubusercontent.com/71310919/93295765-c5416900-f828-11ea-865e-baec52a688f7.png)
