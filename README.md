# Public_procurement
2021 공공조달 빅데이터 공모전에 참여하기 위해서 작성한 코드입니다.
개인적인 사정으로 비록 끝까지 참여하지는 못하였지만, 제가 작성한 코드를 정리하여 올립니다.
고려대학교 김성범 교수님의 '품질공학' 수업을 수강하고 참고하였습니다.

용량 관계상, 코드만 올리겠습니다.
주요 내용은 다음과 같습니다.

# [용역 / 공사 / 물품] 에 대해서 관리도를 통한 예산 관리 & 예산 사용량 예측
여러가지 관리도를 적용시켜 보았으며 예산 사용량 예측은 좋은 결과를 내지는 못하였지만 좋은 시도라고 생각되어져서 올립니다.
[생성한 관리도는 다음과 같습니다.]
1) X_bar - S 관리도
2) X_bar - R_bar 관리도
3) bootstrapping을 적용시킨 T_square 관리도
4) bootstrapping을 적용시킨 SVD 관리도

[사용한 회귀모델은 다음과 같습니다.]
1) XGBoostRegression
2) RandomForestRegression
3) GradientBoostingRegressor
4) LinearRegression

여러 관리도 및 회귀모델을 사용해보면서 많은 것들을 깨달을 수 있었으며, 무엇보다 팀원들과의 관계가 매우 중요하다는 것을 깨달을 수 있었습니다.
