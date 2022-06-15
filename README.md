## POSCO AI BIGDATA 아카데미 17기(AI 프로젝트)
## 개발 추진 배경
* 시각안내견을 대신할 4족 보행 로봇에 탑재할 기능 개발 필요
* 실시간으로 도로 상황을 파악하고 시각장애인에게 정확한 위치와 장애물 안내 필요

## 프로젝트 개발 목표
* OpenCV를 활용하여 차선 검출과 점자 블록 인식을 진행하여 시각장애인에게 안전한 보행 경로를 안내하고자 한다.

## 프로젝트 개발 내용
* https://medium.com/@mrhwick/simple-lane-detection-with-opencv-bfeb6ae54ec0 을 참고하여 차선 검출 진행
* Grayscale 변환과 Canny Edge Detection을 이용하여 관심 영역의 Edge 파악
* Hough 변환을 통해 차선으로 인식할 수 있는 직선 검출
* MoviePy 라이브러리를 이용하여 동영상 파일에서 차선 검출 진행
* RGB에서 HSV로 색상공간 변환 후 노란색 검출을 위한 상하한값 설정
* 점자 블록 부분을 제외하고는 검은색으로 Masking 작업
* 점자 블록의 가장자리 검출을 통한 경로 안내

## 프로젝트 결과 사진
![차선1](https://user-images.githubusercontent.com/39369255/173752822-b1c680a4-86a0-4cc5-855e-43fc5d0e3fcd.png)
![차선2](https://user-images.githubusercontent.com/39369255/173752828-2e66bc65-a88b-4e3f-9452-987c1290fce7.png)
![점자1](https://user-images.githubusercontent.com/39369255/173752834-08b46aef-e79a-4440-a69e-f81a91935e0e.PNG)
![점자2](https://user-images.githubusercontent.com/39369255/173752842-a0583aa5-26ab-48b9-b36b-d29fb4a5cc28.PNG)


