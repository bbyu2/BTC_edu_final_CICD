## ABCbit CI/CD
### Github, Jenkins, ArgoCD를 활용한 Test, Production 파이프라인으로 분리 운영

***

#### TEST 파이프라인
```
변경된 코드를 DEV 브랜치로 Push, Test파이프라인으로 배포
```
![image](https://user-images.githubusercontent.com/84059211/212466737-475f9f3f-ab44-4284-98a9-7e23d2c7a803.png)

#### Production 파이프라인
```
Test 파이프라인에서 정상 작동시, MAIN 브랜치로 merge하여 Production파이프라인으로 실제 배포
```
![image](https://user-images.githubusercontent.com/84059211/212467001-9bc9fdd6-3215-4fa1-a8a6-b265b46a951e.png)
