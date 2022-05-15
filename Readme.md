# [LEVEL1 P_stage 마스크 착용 분류] 🔥열정열정열정!🔥
![image](https://user-images.githubusercontent.com/59071505/168462665-5c956e29-8cce-4d8d-bb2c-4dc43002c40d.png)

&nbsp; 
## 😎 Member 
<table>
  <tr height="125px">
    <td align="center" width="120px">
      <a href="https://github.com/ed-kyu"><img src="https://avatars.githubusercontent.com/ed-kyu"/></a>
    </td>
    <td align="center" width="120px">
      <a href="https://github.com/GwonPyo"><img src="https://avatars.githubusercontent.com/GwonPyo"/></a>
    </td>
    <td align="center" width="120px">
      <a href="https://github.com/seonahmin"><img src="https://avatars.githubusercontent.com/seonahmin"/></a>
    </td>
    <td align="center" width="120px">
      <a href="https://github.com/ysw2946"><img src="https://avatars.githubusercontent.com/ysw2946"/></a>
    </td>
    <td align="center" width="120px">
      <a href="https://github.com/Dongwoo-Im"><img src="https://avatars.githubusercontent.com/Dongwoo-Im"/></a>
    </td>
  </tr>
  <tr height="70px">
    <td align="center" width="120px">
      <a href="https://github.com/ed-kyu">김승규_T3037</a>
    </td>
    <td align="center" width="120px">
      <a href="https://github.com/GwonPyo">남권표_T3072</a>
    </td>
    <td align="center" width="120px">
      <a href="https://github.com/seonahmin">민선아_T3078</a>
    </td>
    <td align="center" width="120px">
      <a href="https://github.com/ysw2946">유승우_T3130</a>
    </td>
    <td align="center" width="120px">
      <a href="https://github.com/Dongwoo-Im">임동우_T3179</a>
    </td>
  </tr>
</table>

&nbsp; 
## 🔍Project Overview

COVID-19의 확산으로 우리나라를 포함한 전 세계 사람들은 경제적, 생산적 활동에 많은 제약을 가지게
되었습니다. COVID-19 확산을 방지하기 위해서는 모든 사람이 올바르게 마스크를 착용하여 전파 경로를
원천 차단해야 합니다. 하지만, 이를 확인하기 위해서는 많은 인적자원이 소모되므로, 올바른 마스크 착용
여부를 자동으로 검출해주는 시스템이 필요합니다

&nbsp;

## 🗂️Dataset
- Total : 4500

- 학습 데이터와 평가 데이터전체를 구분하기 위해 임의로 섞어서 분할하였습니다. 
- 학습 데이터셋이 아닌 나머지 40%의 데이터셋 중에서 20%는 public 테스트셋, 그리고 20%는 private 테스트셋으로 사용됩니다.
- Train : 2700
- Test : 1800 (900(public) + 900(private))
  
- 한 사람당 사진의 개수: 7 [마스크 착용 5장, 이상하게 착용(코스크, 턱스크) 1장, 미착용 1장]
- 이미지 크기: (384, 512)

![image](https://user-images.githubusercontent.com/59071505/168463193-5399fae7-5d19-4418-b95a-0dad912ee279.png)

&nbsp;

## 🏆Result
- Rank : 34등 / 57팀
- Public_f1 : 0.7445
- Private_f1 : 0.7270

![image](https://user-images.githubusercontent.com/59071505/168463477-cd79b953-a816-495c-94ec-f551dff90509.png)

&nbsp;

## 💡Wrap up Report

[이미지 분류_팀 리포트(CV_15조)](https://github.com/boostcampaitech3/level1-image-classification-level1-cv-15/blob/master/%EC%9D%B4%EB%AF%B8%EC%A7%80%20%EB%B6%84%EB%A5%98_CV_%ED%8C%80%20%EB%A6%AC%ED%8F%AC%ED%8A%B8(15%EC%A1%B0).pdf)
