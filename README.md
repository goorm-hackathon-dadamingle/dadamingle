# dadamingle

### 코드 컨벤션

<aside>
🐫 함수명, 변수명은 카멜케이스로 작성합니다.

</aside>
<br/>
<br/>
<aside>
⭕ boolean값은 접두어 is-를 붙여 카멜케이스로 작성합니다.

</aside>
<br/>
<br/>
<aside>
💡 이벤트 핸들러 함수는은 접두어 handle-을 붙여 카멜케이스로 작성합니다.

</aside>
<br/>
<br/>
<aside>
➡️ 함수 스타일은 화살표 함수로 통일합니다. <br/>
const Header = () ⇒ {}

</aside>
<br/>
<br/>
<aside>
🧩 컴포넌트는 폴더명(파스칼케이스)/파일명(파스칼케이스, 폴더명과 동일) <br/>
- ex) components/Button/Button.tsx <br/>
- ex) _components/Button/Button.tsx

</aside>
<br/>
<br/>

<aside>
☝ 컴포넌트 제외한 일반 폴더명은 스네이크 케이스 고려 ex) sign_up

</aside>
<br/>
<br/>
<aside>
### 📁 폴더 구조(app Router 방식)

```
- app
	- api
		- page_name
			route.ts : 해당 페이지 api 로직
	- page_name
		- _components : 해당 페이지에서 사용 가능한 컴포넌트
		page_name.types.ts : 해당 페이지에서만 사용하는 타입 정의

- components : 공용 컴포넌트
- hooks : 공용 훅함수
- styles : 공용 스타일
- types : 공용 type
- utils : 유틸 함수
- constants : 상수화, 쿼리키
```

</aside>
<br/>

### 🎃 사용 스택 및 라이브러리

```
typescript
NextJS
tailwind
shadcn
msw
rtk
nextAuth
axios
react-hook-form + yup
```

<br/>

### 커밋 컨벤션

|   Type   | Description                   |
| :------: | ----------------------------- |
|   feat   | Add a new feature             |
|   fix    | Fix the bug                   |
|  design  | UI design changes such as CSS |
|  style   | code formatting               |
| refactor | Refactoring the code          |
|   docs   | Modify the document           |
|  chore   | etc.                          |

<br>
