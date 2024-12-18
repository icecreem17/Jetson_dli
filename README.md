# Jetson_dli_SUJIN PARK

### Learn the basics of Jetson Nano
```
Supplies
1. Jetson Nano
2. monitor(Recommend having a monitor in addition to your computer. If you use it on your computer (especially a laptop), there is a possibility of an OS collision.)
3. LAN USB
4. power(You have to use 5A with power. If you use more than that, Jetson Nano will be ruined.)
5. Wired mouse and keyboard(Wireless mice and keyboards are also available, but this repository does not show how to connect them.)
6. sdcard(least to 32 GB)

P. S. MY laptop OS is Window. If your computer's OS is not Windows, steps 2-5 are different. So please find a method that suits you.
```

```
1. Download images
```

![화면 캡처 2024-12-19 014545](https://github.com/user-attachments/assets/86d6c6e6-bd53-4e94-bd7e-ccc3e40dafa8)

```
GO to 'https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit#write' and download the file for your computer's operating system
```

```
2. Download SD Memory Card Formatter program
```

![화면 캡처 2024-12-19 015407](https://github.com/user-attachments/assets/de929b3f-c47d-4e2b-bacf-6bbf7a4a091f)
![image](https://github.com/user-attachments/assets/93e80f1f-637a-4640-bc16-8b1e15d5176b)


```
GO to 'https://sd-memory-card-formatter.en.softonic.com/download','https://etcher.balena.io/' and download the file' and download the file
When you finish download, format your sd card
```
GO to 'https://etcher.balena.io/' and download the file' and download the file

```
1. Assemble Jetson Nano
```

![KakaoTalk_20241128_214356790_04](https://github.com/user-attachments/assets/1bc22d5f-6785-476f-ac9a-f135a0e2cbf7)
###

```
- Insert the SD card containing the baked image into the Jetson Nano slot and gently press it. 
- Insert the hdmi wire cable 
- Insert wired mouse and keyboard cables
- Insert wired LAN USB
- Connecting the power(5A)

```
```
2. 우분투 설치
```

![KakaoTalk_20241128_214356790_06](https://github.com/user-attachments/assets/4b14d757-ca1a-4d19-bf7a-0f4fcaffb056)
![KakaoTalk_20241128_214356790_12](https://github.com/user-attachments/assets/b11d5f87-b292-4c07-9d8c-0d6a85fe0b8f)
![KakaoTalk_20241128_214356790_16](https://github.com/user-attachments/assets/5c4005e4-fa96-47de-9ac6-5ac0b3910a3b)
![KakaoTalk_20241128_214356790_17](https://github.com/user-attachments/assets/48ab2db5-89b9-417a-807a-5b7fc9f931b3)
![KakaoTalk_20241128_214356790_20](https://github.com/user-attachments/assets/cb21e048-b21a-482b-9f8d-634485670470)
![KakaoTalk_20241128_214356790_22](https://github.com/user-attachments/assets/51633137-b97f-449c-8a09-5c6f78a6ec1e)
![KakaoTalk_20241128_214356790_24](https://github.com/user-attachments/assets/4436a9e9-db3c-44a0-8b99-c82eaad342dd)
![KakaoTalk_20241128_214356790_26](https://github.com/user-attachments/assets/c929d2a8-beb0-4b5a-a261-baef39327d08)
![KakaoTalk_20241128_214356790_28](https://github.com/user-attachments/assets/47a1c001-c143-431b-b514-861efb227cd7)
![KakaoTalk_20241128_214356790_29](https://github.com/user-attachments/assets/aee9b4e0-6780-4ef0-acba-e928affd6af3)
![KakaoTalk_20241128_214356790_30](https://github.com/user-attachments/assets/9f88e68e-61e5-471d-929c-d351c24c8dcc)
![KakaoTalk_20241128_215122143_05](https://github.com/user-attachments/assets/c7fdf4c7-c706-465f-8e3a-eeeba64e7a6b)
![KakaoTalk_20241128_215122143_06](https://github.com/user-attachments/assets/af0d4989-abee-4526-bb51-b2532081b657)
![KakaoTalk_20241128_215122143_08](https://github.com/user-attachments/assets/b48c60c4-aa59-4f3c-8a87-5834e51799a5)
![KakaoTalk_20241128_215122143_12](https://github.com/user-attachments/assets/32e79e12-0922-4293-9217-bbe66d048d15)
![KakaoTalk_20241128_215122143_14](https://github.com/user-attachments/assets/49ade21d-a3af-4635-a03a-5a3f2c3843aa)
![KakaoTalk_20241128_215122143_15](https://github.com/user-attachments/assets/6159f73f-805a-484f-b3b9-2388ee6ccbd0)
![KakaoTalk_20241128_215122143_17](https://github.com/user-attachments/assets/c95807d0-4bbe-4ec8-b5f5-a5c0cdcfc87b)
![KakaoTalk_20241128_215122143_18](https://github.com/user-attachments/assets/ae50df59-96ef-43fa-a0d9-86e638e95146)
###
```
3. L4T-Readme 살펴보기 & ifconfig
```

![KakaoTalk_20241128_215122143_19](https://github.com/user-attachments/assets/3d77df6f-0ff0-4d9a-b201-8dc84d2dff2e)
![KakaoTalk_20241128_215122143_21](https://github.com/user-attachments/assets/3263f7eb-895d-4bb7-8be7-e3aba589c84a)
![KakaoTalk_20241128_215122143_22](https://github.com/user-attachments/assets/5828ac46-de94-413e-93e6-8cf08725c402)
![KakaoTalk_20241128_215122143_23](https://github.com/user-attachments/assets/3de86873-b4b9-4252-a88a-472b54de5b6e)
![KakaoTalk_20241128_215122143_24](https://github.com/user-attachments/assets/bdef3423-d426-4aaf-adb3-d9a915b7e8a9)
![KakaoTalk_20241128_215122143_25](https://github.com/user-attachments/assets/8c33fbe3-9deb-49a7-912b-323b1f0d9ccb)
![KakaoTalk_20241128_215122143_26](https://github.com/user-attachments/assets/bd2d09fa-d29c-421d-bee4-adaa42f379a3)
![KakaoTalk_20241128_215122143_28](https://github.com/user-attachments/assets/9d038fcb-3435-4bb4-9bec-5b983047220b)
![KakaoTalk_20241128_215122143_29](https://github.com/user-attachments/assets/c8c6cc3a-d95d-4612-9213-36895f6110e6)
###
```
4. 잭슨 나노 한글 설치
```

![KakaoTalk_20241128_215141595_02](https://github.com/user-attachments/assets/f7dce8e4-fcf5-4de0-af0f-b5ab9ec1159d)
![KakaoTalk_20241128_215141595_04](https://github.com/user-attachments/assets/80d9d093-4d5f-4e84-b0ce-0a96d1f37363)
![KakaoTalk_20241128_215141595_05](https://github.com/user-attachments/assets/aedcd221-7d2b-4f8e-b1c2-94324350168b)
![KakaoTalk_20241128_215141595_06](https://github.com/user-attachments/assets/9ce59ff2-547c-4c79-b45d-17fe69eef8aa)
![KakaoTalk_20241128_215141595_07](https://github.com/user-attachments/assets/80d1186a-c0d1-4b41-82b5-4bd142c9383d)
![KakaoTalk_20241128_215141595_08](https://github.com/user-attachments/assets/f158951f-d387-44e6-8731-4caf60857506)
![KakaoTalk_20241128_215141595_09](https://github.com/user-attachments/assets/9de4399b-457f-4f23-ab09-2e91577308e0)
![KakaoTalk_20241128_215141595_12](https://github.com/user-attachments/assets/c9bdb197-d3f2-4921-b06d-42ec0268fabf)
![KakaoTalk_20241128_215141595_14](https://github.com/user-attachments/assets/18cf6daa-1836-4e0a-bddb-835961929f68)
![KakaoTalk_20241128_215141595_15](https://github.com/user-attachments/assets/21d843cb-2993-4d9a-b65f-c94e2d94d5b0)
![KakaoTalk_20241128_215141595_16](https://github.com/user-attachments/assets/0aec0515-3358-42de-a6d5-82ffba3369a8)
![KakaoTalk_20241128_215141595_17](https://github.com/user-attachments/assets/9787bb6d-34c8-42f6-8ffa-118f4538b00e)
![KakaoTalk_20241114_184028807](https://github.com/user-attachments/assets/e7bd0456-608a-486b-8ed4-6df9e4007686)
![KakaoTalk_20241114_184028807_01](https://github.com/user-attachments/assets/6f5923d1-277b-4f20-a6fa-071122d3d931)
![KakaoTalk_20241114_184028807_02](https://github.com/user-attachments/assets/53871aeb-74bb-432b-b43c-2ce575c0791e)
![KakaoTalk_20241114_184028807_03](https://github.com/user-attachments/assets/1e10cd75-019e-4310-aeea-fe65a15e5839)
![KakaoTalk_20241114_184028807_04](https://github.com/user-attachments/assets/548d8c5e-c6bb-44b4-badc-056601b73fe8)
![Screenshot from 2024-11-14 20-51-02](https://github.com/user-attachments/assets/46ddcb10-888a-4458-9901-f863b119ff4d)

#### day 2 :

```
1. 잭슨 나노 영상 캡쳐 이미지
```

![image](https://github.com/user-attachments/assets/4f6050d6-6fe3-41dd-886a-4f8b2a7a6888)
![Screenshot from 2024-11-14 20-59-17](https://github.com/user-attachments/assets/1ddb0609-342e-42b7-8a71-1262b339d05b)
###
```
2. 잭슨 나노 영상 캡쳐 동영상
```

https://github.com/user-attachments/assets/753b3ac5-ee2d-4176-bb74-15c2a446380b
###
```
3. 엔비디아 사진 다운로드
```

![Screenshot from 2024-11-14 21-45-16](https://github.com/user-attachments/assets/950ff074-5eb5-486b-b481-387118ec2d9f)
![Screenshot from 2024-11-14 21-45-32](https://github.com/user-attachments/assets/60e8b810-42c9-4dd8-8294-44478b930d15)

#### day 3 :

```
1. 엔비디아 사진 다운로드 완료 & 주피터 노트북 url생성
```

![Screenshot from 2024-11-21 18-54-55](https://github.com/user-attachments/assets/9586b14b-d830-40a7-b480-eaff1186b8e7)
###
```
2. 스왑 18기가 생성
```

![스왑 사진  jpg](https://github.com/user-attachments/assets/a7e28215-6e86-488c-8f4b-01feaf3d4039)
 -> reboot 중 GUI 모드로 설정하는 과정

![Screenshot from 2024-11-21 20-20-05](https://github.com/user-attachments/assets/9793be0a-ea05-4966-9041-73e2d057b8b4)

 -> 메모리가 1.9기가 에서 18기가로 늘어난 것을 볼 수 있음
###
```
3. 주피터 노트북 접속
```

![Screenshot from 2024-11-21 19-33-56](https://github.com/user-attachments/assets/cc3f49f8-a8ee-41e4-9002-1b09daa73b44)
###
```
4. 엄지 방향 사진 학습
```

![Screenshot from 2024-11-21 20-15-42](https://github.com/user-attachments/assets/a9084f30-7b82-4cbb-94a6-bd2273331c10)
###
```
5. 엄지 방향 사진 예측 완료
```

![Screenshot from 2024-11-21 20-23-43](https://github.com/user-attachments/assets/e84f3a5c-9297-408d-9863-99cf1b86ab61)
![Screenshot from 2024-11-21 20-24-24](https://github.com/user-attachments/assets/39db115d-eaa8-46e2-bc2b-9e46daa147e7)
