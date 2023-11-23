# opensw_mask_RCNN
[ 오픈소스 과제 1번 ]


### 아나콘다 가상환경 생성
![image](https://github.com/mungsil/opensw_mask_RCNN/assets/107127451/b81fc8f6-ead2-4b58-a014-9c58d14ad960)

### 가상환경 접속 및 MASK_RCNN clone 
![image](https://github.com/mungsil/opensw_mask_RCNN/assets/107127451/d89acdc5-a7a4-49ad-b831-c08e3b9a6701)

### keras ==2.1.2, tensorflow == 1.15.5 버전 이용
![image](https://github.com/mungsil/opensw_mask_RCNN/assets/107127451/e228313d-59e8-4436-b994-ef13d992833e)
![image](https://github.com/mungsil/opensw_mask_RCNN/assets/107127451/bef350d5-c01b-4dad-a14d-416a0d871947)

![image](https://github.com/mungsil/opensw_mask_RCNN/assets/107127451/1837122d-e9f9-44a0-ae9a-33547d9b124e)

### 가중치 모델, 데이터셋 다운로드
- mask_rcnn\model\balloon\datasets 경로에 제공받은 train, val에 대한 데이터셋을 저장
- 아래 가중치 모델 사용
- https://github.com/matterport/Mask_RCNN/releases/download/v2.1/mask_rcnn_balloon.h5
- https://github.com/matterport/Mask_RCNN/releases/download/v1.0/mask_rcnn_coco.h5
  ![image](https://github.com/mungsil/opensw_mask_RCNN/assets/107127451/510684c4-3ec9-4565-9389-d6bf3ac348c5)

### scikit-image==0.16.2 버전 이용
![image](https://github.com/mungsil/opensw_mask_RCNN/assets/107127451/d8582c53-6423-4a44-9571-4f09de52e113)


### inference 실행
- 결과 확인 : "mask_rcnn\samples\balloon\splash_20231121T224857.png"
![image](https://github.com/mungsil/opensw_mask_RCNN/assets/107127451/66d2c251-1dce-4790-aaaa-5ac42e3ae3f9)
![image](https://github.com/mungsil/opensw_mask_RCNN/assets/107127451/e57d9006-4ca0-4e8c-ae86-8209d3366e50)
