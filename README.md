# kich@wear

외부온도는 tag expression으로 넣을 수 없음. 

따라서 위젯으로 넣되, 온도만 출력하게 설정하고, 텍스트의 위치, 폰트, 크기를 정확히 지정해줘야 함. 

갤럭시 워치의 기본 날씨 위젯으로 설정하면 아래와 같이 표시됨. 온도가 한 자리 수인 경우, 영하인 경우, 두 자리 수인 경우의 텍스트 위치를 모두 확인함.  

<img src="https://user-images.githubusercontent.com/93939472/219828936-fd98f731-20a1-48ef-bd02-fe65cb5ea8f6.png" width="198">

| Single-digit | Sub-zero | Double-digit |
| --- | --- | --- |
| ![single-digit](https://user-images.githubusercontent.com/93939472/219828937-8d91ab38-15e7-4138-b7a5-e3af787ae75f.png) | ![sub-zero](https://user-images.githubusercontent.com/93939472/219828938-52708483-a029-4fd5-bf66-d004dc68098f.png) | ![double-digit](https://user-images.githubusercontent.com/93939472/219828940-51de77b1-a6ee-4d60-952d-97b64499daaf.png) |




