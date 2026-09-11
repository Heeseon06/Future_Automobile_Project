# 🚗 Jetson Nano 기반 실시간 도로 및 주변 상황 인식 시스템

> **YOLOv7과 StrongSORT를 활용해 도로 객체를 실시간으로 탐지·추적하고,
> GPS 정보를 연동하여 객체 위치를 시각화한 Jetson Nano 기반 도로 상황 인식 시스템입니다.**

2022년 미래자동차 인력양성 산학 프로젝트로 수행했으며,
**미래자동차 인력양성 산학 프로젝트 성과발표회 우수상**을 수상했습니다.

---

## 📌 프로젝트 개요

자율주행 환경에서 차량 주변의 객체를 실시간으로 인식하고 추적할 수 있도록
**YOLOv7 기반 객체 탐지와 StrongSORT 기반 객체 추적 시스템**을 구현했습니다.

추가 데이터셋을 활용해 객체 탐지 모델을 학습하고,
학습된 모델을 **Jetson Nano에 이식하여 실제 주행 환경에서 실시간 동작을 검증**했습니다.

또한 GPS 정보를 연동하여 탐지된 객체의 위치 정보를 시각화하고 저장함으로써
주변 상황 인식과 위치 기반 데이터 활용이 가능하도록 구현했습니다.

---

## ⚙️ 주요 기능

- **YOLOv7 기반 객체 탐지**
  - 도로 및 주변 객체 실시간 탐지
  - 추가 데이터셋 학습을 통해 탐지 성능 개선

- **StrongSORT 기반 객체 추적**
  - 탐지된 객체에 ID를 부여하여 프레임 간 지속적으로 추적
  - 이동 객체의 위치 변화 확인

- **Jetson Nano 실시간 추론**
  - 학습된 객체 탐지 모델을 Jetson Nano 환경에 적용
  - 실제 주행 환경에서 객체 탐지·추적 성능 검증

- **GPS 기반 위치 정보 연동**
  - 객체 탐지 결과와 GPS 정보를 연계
  - 탐지된 객체의 위치를 지도에 시각화하고 관련 데이터 저장

---

## 👩‍💻 담당한 부분

- YOLOv7 객체 탐지 모델 추가 학습
- 데이터셋 추가 및 학습을 통한 **탐지 성능 약 0.5% 향상**
- StrongSORT 기반 객체 추적 기능 구현
- 학습 모델을 Jetson Nano에 이식하여 실시간 탐지·추적 환경 구성
- GPS 데이터와 객체 탐지 결과 연동
- 객체 위치 지도 시각화 및 데이터 저장
- 실제 주행 환경에서 시스템 테스트 및 실시간 처리 성능 검증

---

## 🛠 Tech Stack

**AI / Computer Vision**
- YOLOv7
- StrongSORT
- OpenCV

**Development**
- Python
- Linux / Ubuntu

**Edge Device**
- NVIDIA Jetson Nano

**Others**
- GPS
- Git / GitHub

---

## 🏆 Result

**미래자동차 인력양성 산학 프로젝트 성과발표회 우수상**

YOLOv7과 StrongSORT를 활용한 객체 탐지·추적 시스템을
Jetson Nano에서 실시간으로 구현하고,
GPS 기반 위치 정보 연동 및 실제 주행 환경 검증까지 수행했습니다.

---

## 🖼 프로젝트 이미지

![프로젝트 성과 포스터](https://github.com/user-attachments/assets/622fe7ed-1e9b-4293-ba93-7bb6b61c3e3d)

<details>
<summary>발표 자료 보기</summary>

![79a4db7b684480f162cf5411037dc4a2-0](https://github.com/user-attachments/assets/035dc56c-3e27-473a-a2fc-040a9ebd1d96)
![79a4db7b684480f162cf5411037dc4a2-1](https://github.com/user-attachments/assets/2ea65d9c-e9e7-429e-9646-c2c84ba17e7b)
![79a4db7b684480f162cf5411037dc4a2-2](https://github.com/user-attachments/assets/e0179860-f440-462b-8ab2-36dc2b97cda1)
![79a4db7b684480f162cf5411037dc4a2-3](https://github.com/user-attachments/assets/e7a4f8ca-dcf4-4a4c-a0da-0f6dcf759883)
![79a4db7b684480f162cf5411037dc4a2-4](https://github.com/user-attachments/assets/5a87fbb7-a6de-4fec-8e13-dd78501e34e7)
![79a4db7b684480f162cf5411037dc4a2-5](https://github.com/user-attachments/assets/3ca1fe62-3109-4518-8e5e-d05bf05aeef8)
![79a4db7b684480f162cf5411037dc4a2-6](https://github.com/user-attachments/assets/3e5769e5-0953-4c42-bb70-77e3254fe95c)
![79a4db7b684480f162cf5411037dc4a2-7](https://github.com/user-attachments/assets/4ba24c91-39dc-4084-8e31-c45683e971d2)
![79a4db7b684480f162cf5411037dc4a2-8](https://github.com/user-attachments/assets/8e98e1d0-d9b6-4b7c-a767-bc30f8dfaa63)
![79a4db7b684480f162cf5411037dc4a2-9](https://github.com/user-attachments/assets/a6e79cc2-c0c3-458a-a0d4-4fc81d22f36a)
![79a4db7b684480f162cf5411037dc4a2-10](https://github.com/user-attachments/assets/e1cf0bcc-aaef-4359-a033-e6596db02563)
![79a4db7b684480f162cf5411037dc4a2-11](https://github.com/user-attachments/assets/8e968a42-6986-40b2-b5d9-fbc97c2eb6b7)
![79a4db7b684480f162cf5411037dc4a2-12](https://github.com/user-attachments/assets/bb0e8f68-fd53-4e52-934f-8fd0e5100829)
![79a4db7b684480f162cf5411037dc4a2-13](https://github.com/user-attachments/assets/76ece726-ff87-4834-bd94-0abd673c93da)
![79a4db7b684480f162cf5411037dc4a2-14](https://github.com/user-attachments/assets/21eb7f4d-3b6d-4128-9923-308c33f8f4df)
![79a4db7b684480f162cf5411037dc4a2-15](https://github.com/user-attachments/assets/a47f510e-3d4c-4c9b-8eec-920d7355ef4f)
![79a4db7b684480f162cf5411037dc4a2-16](https://github.com/user-attachments/assets/758634f3-c9e8-4b3d-952d-8c27f454cd9c)
![79a4db7b684480f162cf5411037dc4a2-17](https://github.com/user-attachments/assets/27cbf381-3202-47c9-a2ef-fc0f61359145)
![79a4db7b684480f162cf5411037dc4a2-18](https://github.com/user-attachments/assets/8df322b5-2ecc-4804-be56-72d3831b0ef8)
![79a4db7b684480f162cf5411037dc4a2-19](https://github.com/user-attachments/assets/c75b781d-94c0-4235-9a53-e9437b761bc1)
![79a4db7b684480f162cf5411037dc4a2-20](https://github.com/user-attachments/assets/234fdc31-0304-4e57-b2ca-71e075831997)
![79a4db7b684480f162cf5411037dc4a2-21](https://github.com/user-attachments/assets/6875355d-96f9-4571-8f2f-a52e1c0d7002)
![79a4db7b684480f162cf5411037dc4a2-22](https://github.com/user-attachments/assets/aa0df31b-e835-4c05-882b-af412f7426ca)
![79a4db7b684480f162cf5411037dc4a2-23](https://github.com/user-attachments/assets/e21722a0-7f6c-4560-b3ff-b0d7a8a48c1b)
![79a4db7b684480f162cf5411037dc4a2-24](https://github.com/user-attachments/assets/caa9aa31-1b90-45a2-9e78-c71ba52851c7)

</details>
