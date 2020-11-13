# 한양대학교 ERICA 나노광전자학과 2020-1학기 캡스톤
---------------------------------------
### SiGe의 조성에 따른 E-K diagram, Effective mass, Optical abosrption, Refractive index를 계산하는 모듈입니다.

## 파일 설명
----------------------------------------
### 본 코드를 이용하여 얻어낼 수 있는 결과는 다음과 같습니다.
+ SiGe의 조성비 따라 생기는 kx방향의 E-K diagram
    + ky,kz방향의 추가는 아직 구현하지 않았습니다!

+ SiGe E-K diagram을 이용한 HH,LH,SO, effective mass

+ effective mass에 따른 Optical_absorption 및 Refractive_index

-----------------------------------------
### 코드 사용 예시

+ band_fork.py 의 21번째 줄의 x가 Ge의 몰 분율을 결정합니다
조성비를 0.5로 할 경우

``` Python
#SiGe의 x
x = 0.5
```

+ 나머지 모든 코드는 x값에 의해서만 바뀝니다. 조성비에 따라 바뀌는 굴절율과 흡수율은 Optical_absorption.py , Refractive_index.py 를 실행하시면 됩니다.

+ Mole_f_E_mass는 조성비에 따라 바뀌는 effective mass 를 보여주는 그래프입니다.