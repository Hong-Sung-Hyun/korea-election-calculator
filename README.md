# korea-election-calculator
2020년에 준연동형비례대표가 도입된 새로운 선거법에 따라 비례대표의석을 할당하는 알고리듬을 R로 구현한 것입니다. 
코드는 세 가지 인풋이 필요합니다. 

- pr.vote.share: 각 당의 비례대표 득표율로 %가 아니라 1이하의 소숫점으로 입력해야 합니다. 
- smd.seat: 각 당의 지역구 의석입니다. 정수로 입력되어야 합니다. 
- nonparty.district.winner: 무소속 지역구 당선자 수입니다. 총합계를 입력합니다.
 
<script>
pr = c(25.54,33.5,26.79,14.17,0,0,0,0,0)/100
smd = c(110,105,25,2,0,0,0,0,0)
non = 11
seat.calculator(pr, smd, non) 
<\script> 
