## Blursome 🖼️ 
`사용자 얼굴 인식을 통한 블러 처리 API`

<p align="center">
<img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https://github.com/BluringOther&count_bg=%2391A3D9&title_bg=%23254159&icon=&icon_color=%2391A3D9&title=%E2%9D%A4%EF%B8%8F&edge_flat=false"/>
</p>
<br/><br/>

> 총 3단계로 구성되어있다.    
#### 1. Preround  
* Input: (최초1회) 블러처리를 제외할 사용자의 얼굴  

#### 2. Step1  
* Input: 블러 처리 원하는 사진  
* Output: 해당 사진에서 detect된 얼굴들과 그 위치  

`사용자는 블러 처리 대상 선택에 오류가 있다면, 오류를 정정하여 blursome서버에게 요청한다.`  

#### 3. Step2  
* Input: 블러 처리 원하는 사진, 사진 내 얼굴의 위치, 블러 처리 대상 여부  
* Output: 블러 처리 완료된 사진  

#### [관련기사](https://youtube.com/watch?v=SHQF5vV291k&feature=shares)

### Face Detection Model : MTCNN
### Face Recognition Model : FaceNet
