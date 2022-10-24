# Dialysis-patient-hub-spoke-service

## Abstract 
본 프로젝트는 혈액투석치료기기의 부족 및 불균형을 문제로 삼고, 보건소를 거점으로 네트워크 형성을 목적으로 진행되었다.
혈액투석환자들은 투석기를 통한 치료를 매주 3회 정도 반복해야 함에도 불구하고 청주를 포함한 천안, 원주 등 지방에서 20% 안팎의 환자들은 지역 외부로 이동해 치료를 받아야 하는 상황이다.

이러한 문제 상황을 개선하기 위해 전국 의료시설 데이터를 활용해 SNA와 Clustering을 진행하였다. 구체적인 프로젝트를 진행하기 위해 특정 지역을 선정하고자 선행연구를 바탕으로 의료 취약지역으로 충청북도를 선정하였고, 충청북도의 투석치료기기가 있는 의료시설을 대상으로 SNA를 진행해 보건소를 이용한 네트워크의 효용성을 확인했다. 이후 환자로부터 접근성이 좋은 보건소를 선정하기 위해 랜덤으로 추출한 환자 노드와 혈액투석치료기기를 보유하고 있는 병원 노드 데이터를 사용해 Clustering분석을 진행한 결과 12개의 군집을 형성하였다. 각 군집별로 Centroid에서 가장 근접한 곳에 위치한 핵심 보건소를 선정하였다.

형성된 군집 네트워크를 토대로 보건소 기반 혈액 토석 환자 관리 시스템을 제안하였고, 추가적으로 인프라, 일자리, 데이터 관리 프로세스 등의 관점에서 개선 방안을 제시하였다.

## Data
<img width="414" alt="image" src="https://user-images.githubusercontent.com/76830616/197580916-3d791cbf-dc3b-40e1-a922-49febd7717d7.png">

## SNA
<img width="850" alt="image" src="https://user-images.githubusercontent.com/76830616/197581010-330fff88-3e5e-4561-b151-523f60e14a11.png">

## Clustering
<img width="846" alt="image" src="https://user-images.githubusercontent.com/76830616/197581086-4686013e-3419-459a-973c-250ac29f41ad.png">

## 결론
핵심 보건소 기반 혈액 투석 환자 네트워크 관리 시스템 제안 

<img width="451" alt="image" src="https://user-images.githubusercontent.com/76830616/197581298-14d739e3-5f4e-4842-9362-49a04c66e74f.png">
