# 5nly-code-repository
**🦁 Likelion AI SCHOOL7 🧏‍♀️🧏‍♂️ 으샤으샤팀2 5조 5직우리만봐 팀**       

#### 👨‍👩‍👧‍👦 Team Info.            
|이름|github|                    
|:---:|:---:|                                     
|<span style="color:blue">[이재모👑](https://github.com/generalleejaemo)</span>|<a href="https://github.com/generalleejaemo"><img src="https://img.shields.io/badge/github-181717?style=flat-square&logo=github&logoColor=White"/>|                            
|<span style="color:blue">[김호연](https://github.com/hooun)</span>|<a href="https://github.com/hooun"><img src="https://img.shields.io/badge/github-181717?style=flat-square&logo=github&logoColor=White"/>|          
|<span style="color:blue">[우신](https://github.com/tvn123)</span>|<a href="https://github.com/tvn123"><img src="https://img.shields.io/badge/github-181717?style=flat-square&logo=github&logoColor=White"/>|            
|<span style="color:blue">[이혜빈](https://github.com/dkssudgb)</span>|<a href="https://github.com/dkssudgb"><img src="https://img.shields.io/badge/github-181717?style=flat-square&logo=github&logoColor=White"/>|             
|<span style="color:blue">[우혜진](https://github.com/hyejinWooo)</span>|<a href="https://github.com/hyejinWooo"><img src="https://img.shields.io/badge/github-181717?style=flat-square&logo=github&logoColor=White"/>|           
|<span style="color:blue">[김예지](https://github.com/meji9086)</span>|<a href="https://github.com/meji9086"><img src="https://img.shields.io/badge/github-181717?style=flat-square&logo=github&logoColor=White"/>|             

---

## 1. 🚥 Prediction Road Traffic in Jeju Island 🚥         
<img src="https://user-images.githubusercontent.com/72390138/201039705-4141a0b9-9230-4141-85c3-9efdf5c91e71.png">        

dacon AI 경진대회 : **제주도 도로 교통량 예측하기**                    
주소 : [https://dacon.io/competitions/official/235985/data](https://dacon.io/competitions/official/235985/data)        

팀 1️⃣ : 이재명, 우신, 김예지          
팀 2️⃣ : 우혜진, 이혜빈, 김호연         

### 📜 Summary    
<img src="https://user-images.githubusercontent.com/72390138/202985924-8a7c9ca6-c9a4-46cd-8a74-4c9189bb35aa.png">      

**제주도내 주민등록인구**는 2022년 기준 약 68만명으로, **연평균 1.3%정도 매년 증가**하고 있습니다.     
또한 외국인과 관광객까지 고려하면 **전체 상주인구는 90만명**을 넘을 것으로 추정되며,     
제주도민 증가와 외국인의 증가로 현재 제주도의 교통체증이 심각한 문제로 떠오르고 있습니다.    

따라서, 여러 상황별로 **시간을 추측할 수 있도록 속도를 예측하는 것이 목표**이다.       
실제 Tmap과 네이버지도와 같은 거리간의 시간을 예측하는 알고리즘에서 유용하게 사용될 것이다.       

### 🗃 Data Info.                                            
**dacon 제주도 도로 교통 데이터** : [https://dacon.io/competitions/official/235985/data](https://dacon.io/competitions/official/235985/data)     
 
<img src="https://user-images.githubusercontent.com/72390138/201040309-ab16c7c3-ea57-4834-b3d2-b3a17ba3665d.png">            

**Data Shape**           
train (4701217, 23)             
test (291241, 22)               

### 🛠 Code & Pipeline          
|이름|코드 및 파이프라인|         
|:---:|:---:|          
|<span style="color:blue">[이재모👑](https://github.com/generalleejaemo)</span>|미니2 - 오직_이재모.ipynb|         
|<span style="color:blue">[김호연](https://github.com/hooun)</span>|머신러닝 미니프로젝트_김호연.ipynb|        
|<span style="color:blue">[우신](https://github.com/tvn123)</span>||         
|<span style="color:blue">[이혜빈](https://github.com/dkssudgb)</span>|Miniproject_ML_이혜빈.ipynb|       
|<span style="color:blue">[우혜진](https://github.com/hyejinWooo)</span>|Jeju_Traffic_Randomforest_우혜진.ipynb|         
|<span style="color:blue">[김예지](https://github.com/meji9086)</span>|Jeju_Traffic_LightGBM_YJ.ipynb|             

### 📊 Visualization    
**1️⃣ 요일별 평균 속도**      
<img src="https://user-images.githubusercontent.com/72390138/202987700-8e7cf624-f8b2-4700-a30c-dd7ed084c963.png">     
금요일에 속도가 감소함에 따라, 교통량이 증가한 것을 알 수 있다.   
이는, 금요일의 차량 이동량이 많다는 것을 의미한다.     

**2️⃣ 시간별 평균 속도**        
<img src="https://user-images.githubusercontent.com/72390138/202988024-db4da307-71d2-468b-a93c-54edfedfb302.png" >      
00시 - 05시, 18 - 24시에 속도가 증가함에 따라, 교통량은 감소한 것을 알 수 있다.     
18시에는 가장 속도가 느린 것으로 보아 차량 이동량이 많다는 것을 알 수 있다.     
이는, 퇴근 길에 가장 차량 이동이 많다는 것을 추측할 수 있다.        

**3️⃣ 연간 속도 추이**       
<img src="https://user-images.githubusercontent.com/72390138/202988769-a14e9747-542c-4f1d-a81c-144135fd459d.png">      
7월에 가장 평균 속도가 급감소함에 따라 교통량이 급증가한 것을 알 수 있다.    
이는, 여름 휴가로 인한 차량 이동이 증가함을 추측할 수 있다.        

**4️⃣ 도로별 최고 속도 상위 top10**           
<img src="https://user-images.githubusercontent.com/72390138/202984309-ea82d1e4-8b6f-4e7d-a300-50a610f1652a.png" weight="400" height="400">     
평균적으로 일반국도에서 속도가 높다.     

**5️⃣ 각 feature별 상관관계**      
<img src="https://user-images.githubusercontent.com/72390138/202992579-652384d7-324f-410f-9615-9a8440b2c1b4.png" weight="950" height="600">       

**6️⃣ 각 feature별 histogram**     
<img src="https://user-images.githubusercontent.com/72390138/202990875-64eb022a-a2d1-44f2-b315-eab975abc9f0.png" weight="950" height="600">        
 
 
### 🌳 Tree-based Machine Learning Modeling : RandomForestRegressor        
**Feature Importances**     
<img src="https://user-images.githubusercontent.com/72390138/202991325-e7b6245c-5f50-4c42-9ce3-6c87eaa6d2b3.png" weight="500" height="400">       
feature 간의 중요도는 1위 maximum_speed_limit, 2위 end_longitude 순으로 높은 것을 알 수 있다.          

### 🍀 Submission MAE       
 **Submission MAE** : 3.35      
 **RandomForestRegressor Accuracy** : 0.91     

---

## 2. 💰💻 Predicting the Price of a Laptop 💻💰        
<img src="https://user-images.githubusercontent.com/72390138/202939016-9aa9e0ac-ec67-4028-95d9-daf7e31ac588.png">     

Kaggle AI 경진대회 : **노트북 가격 예측하기**               
주소 : [https://www.kaggle.com/competitions/laptop-price-prediction](https://www.kaggle.com/competitions/laptop-price-prediction)

### 📜 Summary      
<img src="https://user-images.githubusercontent.com/72390138/203260010-f611f8e0-45e4-44c3-abb3-48461f6cfdc1.png">     

**노트북의 가격은 끊임없이 오르는 점을 파악**했고, 가격이 적당한가에 대한 의문점을 갖게 되었습니다.        
하드웨어, 노트북 제조사 등 모든 요구사항을 만족하는 노트북을 찾기는 쉽지 않았을 뿐만 아니라, **가격이 적절한가**에 대한 의문이 들었습니다.      

따라서, 지금까지 판매되었던 노트북 데이터를 이용하여, 원하는 스펙을 가진 노트북의 적절한 인터넷 최저가를 예측하는 모델을 생성해보고자 합니다.    
**원하는 스펙을 가진 노트북의 적정 인터넷 최저가 분석을 통한 합리적인 노트북을 구입할 수 있도록 하는 것이 목표**입니다.         


### 🗃 Data Info.     
**Kaggle 노트북 데이터** : [https://www.kaggle.com/competitions/laptop-price-prediction/data](https://www.kaggle.com/competitions/laptop-price-prediction/data)     

<img src="https://user-images.githubusercontent.com/72390138/202943765-98cbb4ac-58d4-443b-bf55-54dfe5354745.png">       

**Data Shape**         
train (950, 12)      
test (350, 11)          

### 🛠 Code & Pipeline          
|이름|코드 및 파이프라인|         
|:---:|:---:|          
|<span style="color:blue">[이재모👑](https://github.com/generalleejaemo)</span>|오직우리만봐_laptop-price_이재모.ipynb|         
|<span style="color:blue">[김호연](https://github.com/hooun)</span>||        
|<span style="color:blue">[우신](https://github.com/tvn123)</span>||         
|<span style="color:blue">[이혜빈](https://github.com/dkssudgb)</span>||       
|<span style="color:blue">[우혜진](https://github.com/hyejinWooo)</span>|Laptop price prediction_우혜진.ipynb|         
|<span style="color:blue">[김예지](https://github.com/meji9086)</span>|Laptop_price_predict_YJ.ipynb|     

### 📊 Visualization  
**1️⃣ 컴퓨터 종류 Top5**    
<img src="https://user-images.githubusercontent.com/72390138/203262255-0d0271e7-9ec6-4821-9374-cb4a3f21f4f2.png" weight="500" height="400">      
Notebook의 종류가 월등하게 높은 것을 확인할 수 있다.    
이는, 들고다닐 수 있는 편의성으로 인해 구매율이 높아 생산률도 높을 것이라고 추측할 수 있다.    

**2️⃣ 제조업 종류**          
<img src="https://user-images.githubusercontent.com/72390138/203263872-972f5506-cea6-42c7-a9d4-51532bb8749b.png">       
제조업은 Dell, Venovom, HP의 제품들이 월등하게 많은 것을 확인할 수 있다.     

**3️⃣ 하드디스크 Top5**     
<img src="https://user-images.githubusercontent.com/72390138/203264327-d698d49a-1b8a-4f1e-98a1-d4347279efce.png" weight="500" height="400">     
일반적으로 많이 사용하는 256GB SSD 제품이 가장 많은 것을 확인할 수 있다.    

**4️⃣ CPU Top5**      
<img src="https://user-images.githubusercontent.com/72390138/203264495-ac4f7525-1cb4-4125-ad30-5bf3aaee33fc.png" weight="500" height="400">          
Intel제품의 제품들이 많았고, 그 중 Intel Core i5 7200U 2.5GHz의 CPU가 가장 많은 것을 확인할 수 있다.      

**5️⃣ 각 feature별 상관관계**     
<img src="https://user-images.githubusercontent.com/72390138/203265947-139720cd-3a8f-4f83-981b-4cf97049706f.png" weight="950" height="600">     

**6️⃣ 각 feature별 histogram**      
<img src="https://user-images.githubusercontent.com/72390138/203265240-a410982b-26c5-47b3-99c2-2989de76b553.png" weight="950" height="600">     
   

### 🌳 Tree-based Machine Learning Modeling : RandomForestRegressor    
**Feature Importances**     
<img src="https://user-images.githubusercontent.com/72390138/203267028-fd907b70-f633-457a-ac45-9947e02fad92.png" weight="500" height="400">       
feature 간의 중요도는 1위 CPU, 2위 Peso(무게) 순으로 높은 것을 알 수 있다.          

**각 Feature에 대한 전처리 후 Feature Importances**    
<img src="https://user-images.githubusercontent.com/72390138/203267744-ff0cd8ac-0508-4c54-bf62-476a704473bc.png" weight="500" height="400">       
feature 간의 중요도는 1위 RAM, 2위 Peso(무게) 순으로 높은 것을 알 수 있다.     

**가격을 예측하는데에 있어서 무게는 중요하게 평가하는 것으로 예상**할 수 있다.     

### 🍀 Submission MAE       
**Submission RMSE** : 402     
**RandomForestRegressor Accuracy** :           
<img src="https://user-images.githubusercontent.com/72390138/203268734-f42ab75f-4d2b-4e3b-86c4-987a9e26d77c.png" weight="500" height="400">       
     
