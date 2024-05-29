# Resume_challenge

참고 : [https://cloudresumechallenge.dev/docs/the-challenge/aws/](https://cloudresumechallenge.dev/docs/the-challenge/aws/)

레포 : https://github.com/glen15/resume_challenge

- 자신의 레포지토리로 `fork` 후 진행

## mission 1 : S3 구성 → html 배포

- `resume.html` 활용
- S3 정적 웹페이지 호스팅 기능으로 배포

## mission 2 : React 프로젝트 배포

- `Resume 폴더` 활용

## mission 3 :  Lambda 함수 구성

- `lambda.py` 활용
- DynamoDB로 방문, 좋아요 정보를 전달

## mission 4 : S3 → Lambda

- 정해진 `Path, Method`로 요청이 전달되는지 확인

## mission 5 : DynamoDB 구성

- 테이블 생성
- 항목 추가
  - ```json
    {
      "id": "visit_count",
      "visits": 0
    }

    {
      "id": "like_count",
      "likes": 0
    }

    ```

## mission 6 : Lambda → DynamoDB 연결 확인

- 관련 구성 설정 : `코드 변경` 등
- DynamoDB 테이블에서 수치 변경 확인

## mission 7 : S3 → Lambda → DynamoDB 연결 확인

- 웹사이트 `네트워크 탭`에서 전달 사항 확인
- 관련 구성 설정 후 최종 확인

## mission 8 : Codepipeline 구축

- Codepipeline 활용

## mission 9 : HTTPS 구성

- ACM, CloudFront, Route53 활용
