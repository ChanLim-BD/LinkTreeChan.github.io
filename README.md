![](https://velog.velcdn.com/images/chan9708/post/56b9c680-189f-4e7c-abb3-84a112d55164/image.jpg)

# 1. Repository 생성
* 웹을 구성하는 파일(HTML, CSS, JS ...)이 업로드될 저장소(Repository)를 만들어야 한다.

![](https://velog.velcdn.com/images/chan9708/post/11c2059e-89d3-4834-818c-780d34c65697/image.png)

* **GitHub**에 로그인 한 후 오른쪽 상단에 위치하고 있는 **New**를 클릭하여 저장소를 생성한다.

![](https://velog.velcdn.com/images/chan9708/post/a034f934-4c1c-42a6-8be9-8e9c7cd1bce5/image.png)

저장소 정보를 입력하는 화면에는 아래 사항에 유의하여 작성한다.

### Repository name:
- 반드시 `<사용자이름>.github.io` 또는 `<조직이름>.github.io`로 명명해야 한다.
- 반드시 <사용자이름>에는 자신의 github 사용자이름을 명확하게 넣자!
- 만약 <span>`[사용자이름].github`.<span style="color : red">com</span></span>이라는 저장소와 <span >`[사용자이름].github`.<span style="color : red">io</span></span>라는 저장소가 공존하는 경우 오직 `<사용자이름>.github.io` 만 사이트로 배포된다. 
(github 가이드의 #types-of-github-pages-sites)


### Description:
- 선택 사항이므로 자유롭게 기입한다.

### Public 또는 Private:
- 당연히 공공연히 공개할 것이므로 Public에 체크한다.

### Initialize this repo....:
- 'Add a README file' 공식 가이드에서는 체크표시를 해두라고 하지만, 체크를 하거나 안 하거나 아무 문제 없다.

- 그 외엔 자신의 프로젝트에 맞춰주자.
  
# 2. Repository 세팅하기

![](https://velog.velcdn.com/images/chan9708/post/a05b2e0b-b2c4-4a0f-98e4-8f3467856a90/image.png)

* 방금 만든 Github 저장소의 페이지에 진입한 후에 상단에 있는 **[Settings]**를 클릭해준다.

![](https://velog.velcdn.com/images/chan9708/post/7b7ec71e-d3bc-483e-b7f7-296fe8a1c3e1/image.png)

* 나타나는 화면에서 스크롤을 거의 아래쪽으로 내리다 보면 **[Pages]**라는 항목이 보일 것이다.

![](https://velog.velcdn.com/images/chan9708/post/b6c229c8-b8de-4b5f-9f0c-8ff7e52c4c49/image.png)

* 기본적으로 **[None]** 으로 선택된 상자를 클릭하고
자신이 보여주고자하는 브랜치(Branch, 분기점)를 선택한 다음
**[Save]** 버튼을 클릭한다.

![](https://velog.velcdn.com/images/chan9708/post/03191bd6-5d05-40e0-b349-be776994b03d/image.png)

* 설정 사항을 저장한 후 **[Actions]** 탭에 들어가면 **[pages-build-deployment]** 라는 워크플로우가 실행되고 있다. 한 30초 정도 기다리면 웹사이트 배포가 완료되어 접속할 수 있는 URL을 얻으실 수 있다.

![](https://velog.velcdn.com/images/chan9708/post/9c23b039-8ec6-4db7-9d2b-eb050c466f38/image.png)

* **그리고 현재 화면이 새로고침되는데, 다시 GitHub Pages 항목을 본다면 
`"Your site is published at http(s)://XXX.github.io"` 라는 메시지가 보일 것이다.**

# 3. 완료
![](https://velog.velcdn.com/images/chan9708/post/bc7a2c8e-3684-4eb1-81af-e391c50c4192/image.png)

* 그리고 알려준 주소로 접속해보면 저장소에 있는 정적 파일들이 호스팅된다.
* **블로그 주인은 미리 제작해둔 LinkTree를 저장하고 호스팅을 하였다.**

---
# Reference

>
[Github Docs](https://docs.github.com/en/pages/getting-started-with-github-pages)
