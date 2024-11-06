# troubleshooting-for-sa

### 상황
- `troubleshooting` 앱 이미지를 빌드하여 `cepgbaseacr.azurecr.io` ACR에 푸시를 완료했습니다.
- 이제 `troubleshooting` 이미지를 쿠버네티스 환경에 파드로 배포하려고 합니다.

### 목표
1. 자신이 생성한 AKS의 `troubleshooting` 네임스페이스에 파드를 정상적으로 배포하세요.


### 방법
- 현재 저장소의 매니페스트 파일을 받아서 진행해 주세요.
- 문제 상황이 발생하면 `deployment.yaml` 파일을 수정하여 해결해 주세요.
- 다른 설정은 변경하면 안됩니다.
