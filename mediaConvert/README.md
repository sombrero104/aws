
# MediaConvert

## 1. MediaConvert 서비스 Role(역할) 생성
MediaConvert 에서 S3로 접근하여 파일을 읽어오고 변환 후 다시 저장을 해야 하기 때문에 <br/>
MediaConvert 서비스에 권한을 주기 위하여 MediaConvert용 서비스 Role(역할)을 생성한다. <br/>

<img src="./images/mediaConvert_serviceRole.png" width="70%" />

추후 Lambda 작업 생성 시 MediaConvert 의 서비스 Role(역할)을 사용하기 때문에 <br/>
Lambda 환경변수에 아래 ARN을 입력해 준다. <br/>

<img src="./images/mediaConvert_serviceRole_arn.png" width="70%" />

<br/><br/>

## 2. Lambda 서비스 Role(역할) 생성


<br/><br/><br/><br/>
