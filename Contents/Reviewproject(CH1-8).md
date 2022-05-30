# Reviewproject(CH1-8)
## Info
- 날짜: 2022.5.8

## 내용
### Project Link

||닉네임|프로젝트 링크|
|:---:|:---:|:---:|
|1|빠각|https://github.com/LetsSwifty/keenkim_projects|
|2|미시시피|https://github.com/LetsSwifty/YongHoon_projects|
|3|메론|https://github.com/LetsSwifty/florence96_projects|
|4|jinjin|https://github.com/LetsSwifty/JINHYUNGP_projects|
|5|Rx|https://github.com/LetsSwifty/kangddong_projects|
|6|밍|https://github.com/LetsSwifty/mingging_project|
|7|김희진|https://github.com/LetsSwifty/heejin_project|
|8|프프|https://github.com/LetsSwifty/yoogail105_projects|
|9|서윗|https://github.com/LetsSwifty/lii0730_projects|

### Project Review
<details>
  <summary> indexPath의 프로퍼티 row, item 둘의 차이점</summary>
  
  내용 작성
</details>

<details>
  <summary> 네비게이션 바 사용법</summary>
  
    ```Swift
    self.navigationItem.hidesBackButton = true
    let backButton = UIBarButtonItem(image: UIImage(systemName: "chevron.backward"), style: UIBarButtonItem.Style.done, target: self, action: #selector(backButton(sender:)))
    self.navigationController?.navigationBar.tintColor = .black
    self.navigationItem.leftBarButtonItem = backButton
    ```
</details>

<details>
  <summary> UIAlertController에 delegate Pattern을 적용했을 때  tableView에서 reloadData 안되는 이슈</summary>
  
  내용 작성
</details>

<details>
  <summary> conovenience init에 대하여</summary>

  내용 작성
</details>




### 챕터 9 이후 Project 기능 추가
<details>
  <summary> Project 기능 추가 </summary>

+ 주제: 도서 관리 앱
+ 내용: 여러 도서 중 원하는 도서를 마이페이지(즐겨찾기)에 등록할 수 있다.
+ 화면 구성: 도서 목록 / 마이페이지(즐겨찾기)
+ 기능
    1. 목록 페이지에서 도서 목록을 볼 수 있다.
    2. 목록 페이지에서 버튼을 통해 도서를 마이페이지로 추가할 수 있다.
    3. 마이페이지에서는 선택된 도서를 확인할 수 있다.
    4. 마이페이지에서는 선택된 도서를 삭제할 수 있다.
    5. 목록페이지에서는 마이페이지에 선택된 도서를 확인할 수 있다.
+ 네이버 오픈 API 활용 : [링크](https://developers.naver.com/docs/search/book/)
  
</details>
