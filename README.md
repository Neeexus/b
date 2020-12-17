# PCR
Positive criteria for fluorescence measurement PCR device

---
## Real-Time PCR 이란?
![pcr.PNG](./imgs/pcr.PNG)
> 실시간 중합효소연쇄반응(real-time polymerase chain reaction, real-time PCR, qPCR)은 분자생물학에서 중합효소 연쇄 반응을 기반으로한 실험방법이다. 실시간 중합효소연쇄반응은 목표 DNA분자의 증폭과 양의 측정을 동시에 한다. DNA샘플에서 하나 또는 그 이상의 특정 서열을 위해, 실시간 중합효소연쇄반응은 검출과 양의 측정을 할 수 있게한다. 계량은 절대적인 복제 수 또는 상대적인 양을 셀 수 있다.


---
## 과제 목적
![project.PNG](./imgs/project.PNG)
>- 최근 코로나 19와 같은 감염자가 늘어난 만큼, 진단에 필수적인 Real-Time PCR의 제작에 기여
>- 기존 PCR 장치의 형광 데이터로부터, 감염 여부를 판단하는 보다 효율적인 방법론을 제시하는 것이 목표
>- Real-Time PCR의 형광 데이터로 부터, 농도를 정확히 모르는 임상데이터가 주어졌을때, 보다 나은 양성 판정 기준을 제시하기 위해 Cycle Threshold(Ct)의 variance를 줄여야 함

---
## 과제 진행 순서

### RealTime-PCR 사전조사
- 사용할 PCR 기기 광학구조 조사 
- 사용할 PCR Chip 조사 및 확인
![light.PNG](./imgs/light.PNG)
![top.PNG](./imgs/top.PNG) 

### RealTime-PCR 실험
![silhum.PNG](./imgs/silhum.PNG)
### PCR Chip 제작
![chip.PNG](./imgs/chip.PNG)  
### 각기 다른 3농도에 대한 Real-Time PCR 실험 및 모니터링
---
- RealTime-PCR 데이터 분석
    - PCR 기기들이 사용하는 Fixed-Threshold 방식 조사 및 적용
    - DNN를 이용한 Ct값 검출(Ours)
    - 위 두 방법을 비교
