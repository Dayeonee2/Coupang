# Coupang

1년치 월별 합산 금액 

## 필수사항
[오빠두엑셀](https://www.oppadu.com/%EC%BF%A0%ED%8C%A1-%EB%84%A4%EC%9D%B4%EB%B2%84%ED%8E%98%EC%9D%B4-%EB%B6%84%EC%84%9D/)
매크로 엑셀 파일 다운받기 -> txt파일로 원하는 부분 크롤링 후 저장

### 순서
1. txt 파일을 txt폴더에 저장후 해당 이름으로 된 파일에 labeling.ipynb를 실행시켜 구매내역의 카테고리를 라벨링 함
2. 라벨링 후 저장된 엑셀파일을 graph.ipynb를 실행시켜 월별 평균과 사용내역을 카테고리 별로 알 수 있음
3. graph 폴더에 정리된 파일이 저장됨
