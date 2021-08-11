# ✍ Code review study

## 📄 Study content
- innerHTML  
✔해당 element의 html, xml을 읽어오거나 설정할 수 있다.  
⛔사이트의 공격 경로가 되어 잠재적인 보안 위험이 발생할 수 있다.

- innerText  
✔해당 element에서 사용자에게 보여지는 text값을 읽어온다.  
✔display:none으로 숨겨진 text는 보여지지 않는다.  
✔즉, text의 렌더링 후 모습을 인식한다.  
✔연속된 공백은 하나만 처리.

- textContent  
✔'<script>'나 '<style>' 태그와 상관없이 해당 node가 가지고 있는 text값을 그대로 읽어온다.  
✔연속된 공백 표시.

## 💻 BLOG - Code review log
> 3주차 과제 제출 이후 받은 code review feedback을 정리하여 blog에 업로드
<!-- [Choi Minji](your blog url) 와 같이 표시 -->
- [Choi Minji - Week3 Code Review Summary](https://developerntraveler.tistory.com/105)
- [Lee Sora - Week3 Code Review Summary](https://velog.io/@sora2821/3%EC%A3%BC%EC%B0%A8-%EA%B3%BC%EC%A0%9C-%EC%BD%94%EB%93%9C-%EB%A6%AC%EB%B7%B0)
- [Jeon Sujin  - Week3 Code Review Summary](https://velog.io/@serenity/3%EC%A3%BC%EC%B0%A8-Quiz-code-review)
- [Kim Jinkwon - Week3 Code Review Summary](https://velog.io/@effort_jk/3%EC%A3%BC%EC%B0%A8-%EA%B3%BC%EC%A0%9C-Review)
