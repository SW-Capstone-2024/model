# model

YOLOv8 Nano 모델은 경량화된 구조로, 라즈베리 파이와 같은 저사양 하드웨어에서 원활하게 동작할 수 있도록 설계되었다. 일반적인 딥러닝 모델에 비해 메모리 사용량과 연산 요구량이 현저히 낮아 임베디드 시스템에서도 실시간 처리가 가능하다. 이러한 특징 덕분에 본 프로젝트에 적합한 모델로 선택되었으며, YOLOv8 Nano는 높은 FPS(Frames Per Second)를 제공하여 실시간 장애물 감지에 최적화된 성능을 발휘한다.

![image](https://github.com/user-attachments/assets/3dd4c068-3d5f-4f25-81f0-aa4be7000c72)

또한 YOLOv8 Nano 모델을 NCNN으로 변환하는 과정을 수행하였다. 이를 통해 라즈베리파이에서 YOLOv8 Nano 모델의 실시간 추론 시간이 기존 대비 약 3배 단축되었다.
