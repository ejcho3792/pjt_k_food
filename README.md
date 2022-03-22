# pjt_k_food
korean food classification and AI service project
---
# TO DO     
* 데이터 전처리     
    * 소단위 클래스 별 crop area가 정해져 있음. (각 폴더 내 croparea.properties 파일)    
        - 먼저 잘라서 저장 후에 split이나 다른 전처리 하는 것이 좋을 것 같음    
    * 데이터 split ( train/ val/ test )
```bash
ㄴtrain     
    ㄴclass1     
        ㄴjpg    
        ㄴjpg     
    ㄴclass2     
        ㄴjpg     
        ㄴjpg     

ㄴvalidation     
    ㄴclass1
        ㄴjpg
        ㄴjpg
    ㄴclass2
        ㄴjpg
        ㄴjpg

ㄴtest
    ㄴclass1
        ㄴjpg
        ㄴjpg
    ㄴclass2
        ㄴjpg
        ㄴjpg
```
