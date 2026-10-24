# 제출 이미지

- `architecture.svg`: 실제 제출 YAML에 맞춘 웹·DB 아키텍처입니다.
- `MinWook.jpg`: 기존 프로필 이미지 원본 자료입니다. 서비스 실행에 필요한 사진은 런타임 ConfigMap에 이미 들어 있습니다.

배포 후 아래 파일을 추가하고 상위 README에 실제 결과를 기록합니다.

| 파일 | 내용 |
| --- | --- |
| `topology.png` | OpenShift Topology 또는 웹·DB Pod 정상 상태 |
| `browser.png` | 실제 HTTPS Route에서 보이는 자기소개·방명록 |
| `persistence.png` | 웹·DB 재시작 후 방명록 글 보존 확인 |
| `oc-get-all.txt` | `oc get all` 출력 |
| `oc-get-pvc.txt` | `oc get pvc` 출력 |
| `route-url.txt` | 실제 HTTPS 접속 주소 |

로그인 토큰·Secret 내용은 캡처하지 않습니다. 로컬 화면이나 구성도를 OpenShift 배포 성공 증빙으로 사용하지 않습니다.
