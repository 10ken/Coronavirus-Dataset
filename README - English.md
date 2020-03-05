# Coronavirus-Dataset
-** Coronavirus Infectious Disease-19 (COVID-19) ** Reconstructed the information of domestic sponsors into CSV files for easy data analysis.

1. patient Dataset: Information on 5766 confirmed participants (as of March 5, 2020)  
2. route Dataset: Information about the path of the follower
3. time Dataset: Daily scan results and status information
  
-Information that has not been confirmed yet will be updated later.
- kaggle Data Is also open to [Coronavirus-Dataset](https://www.kaggle.com/kimjihoo/coronavirusdataset) 

***

### 1. patient Data set information
- ***id***: Id of the confirmer (n th confirmer)
- ***sex***: male or female
- ***birth_year***: Birth year
- ***country***: Nationality
  - *Korea*: 대한민국
  - *China*: 중국
  - *Mongolia*: 몽골
- ***region***: Main activity area (by metropolitan / province)
  - *capital area*: Metropolitan Area (Seoul / Incheon / Gyeonggi-do)
  - *filtered at airport*: Inactivity after airport quarantine
  - *Busan*: 부산광역시
  - *Daegu*: 대구광역시
  - *Daejeon*: 대전광역시
  - *Gwangju*: 광주광역시
  - *Ulsan*: 울산광역시
  - *Gangwon-do*: 강원도
  - *Chungcheongbuk-do*: 충청북도
  - *Chungcheongnam-do*: 충청남도
  - *Jeollabuk-do*: 전라북도
  - *Jeollanam-do*: 전라남도
  - *Gyeongsangbuk-do*: 경상북도
  - *Gyeongsangnam-do*: 경상남도
  - *Jeju-do*: 제주도
- ***group***: Specific groups
  - *Shincheonji Church*: 신천지 관련
  - *Cheongdo Daenam Hospital*: Qingdao University Hospital
  - *Eunpyeong St. Mary's Hospital*: Eunpyeong St. Mary's Hospital
  - *Onchun Church*: Hot Spring Church Related
  - *Myungsung Church*: Reputation Church
  - *Pilgrimage*: Pilgrimage to Israel
- ***infection_reason***: Infection path
  - *visit to ooo*: Infection Country / City Visit
  - *contact with patient*: Contact with domestic sponsors
  - *contact with patient in ooo*: Contact with overseas sponsors
  - *residence in Wuhan*: Wuhan, China
  - *pilgrimage to Israel*: Pilgrimage to Israel
- ***infection_order***: Infection Order (n-th Infection)
- ***infected_by***: Infectious agent id of the confirmation
- ***contact_number***: Contact number
- ***confirmed_date***: Confirmation date
- ***released_date***: Discharge date (Date not released)
- ***deceased_date***: Date of death
- ***state***: state
  - *isolated*: Hospitalization (Isolated)
  - *released*: Discharge (uncontained)
  - *deceased*: Dead

***

### 2. route 데이터셋 정보
- ***id***: Id of the confirmer (n th confirmer)
- ***date***: Date
- ***province***: State / Province / Province
- ***city***: City
- ***visit***: Place visited (kind)
  - *airport*: airport
  - *hospital_isolated*: An insulated hospital
                         (maybe ment ot be isolated)
  - *hospital*: Large hospital or health center
  - *clinic*: Clinic
  - *hotel*: hotel
  - *store*: Small shop
  - *market*: supermarket
  - *restaurant*: Restaurant
  - *cafe*: Cafe
  - *house*:House
  - *bus_terminal*: Bus terminal
  - *train_station*:train station
  - *movie_theater*: Movie Theaters
  - *hair_salon*: Salon
  - *church*: church
  - *etc*:Other places to visit
- ***latitude***: 위도
- ***longitude***: 경도

***

### 3. time, Data set information
- ***date***: 일자
- ***acc_test***: Cumulative checks (including ongoing checks)
- ***acc_negative***: Cumulative Negative Results
- ***acc_confirmed***: Cumulative Positive Results (Confirmed)
- ***acc_released***: Cumulative Quarantine Releases
- ***acc_deceased***: Cumulative Deaths
- ***new_test***: New checks
- ***new_negative***: New negative results
- ***new_confirmed***: Number of new positive results (confirmed)
- ***new_released***: New quarantine released
- ***new_deceased***: New deaths

***

**Dataset License**: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

***

### Reference site
- Official Website of Disease Control Division
  (http://www.cdc.go.kr/) (government)
- [Coronavirus Infectious Disease-19 Official Website
  (http://ncov.mohw.go.kr/) (government)
- Corona Map (https://coronamap.site/) (Private)
- [COVID-19 real time status board]
  (https://wuhanvirus.kr/) (Private)
- [Korea's Coronavirus Infection-19 Epidemic](https://ko.wikipedia.org/wiki/%EB%8C%80%ED%95%9C%EB%AF%BC%EA%B5%AD%EC%9D%98_%EC%BD%94%EB%A1%9C%EB%82%98%EB%B0%94%EC%9D%B4%EB%9F%AC%EC%8A%A4%EA%B0%90%EC%97%BC%EC%A6%9D-19_%EC%9C%A0%ED%96%89) (Wikipedia)
- [Corona Virus Infection-19 / Elapsed / Korea Confirmation](https://namu.wiki/w/%EC%BD%94%EB%A1%9C%EB%82%98%EB%B0%94%EC%9D%B4%EB%9F%AC%EC%8A%A4%EA%B0%90%EC%97%BC%EC%A6%9D-19/%EA%B2%BD%EA%B3%BC/%EB%8C%80%ED%95%9C%EB%AF%BC%EA%B5%AD%20%ED%99%95%EC%A7%84%EC%9E%90%20%ED%98%84%ED%99%A9) (TreeWiki or Wiki)
