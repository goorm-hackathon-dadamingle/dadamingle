# dadamingle팀


<h2>🏫 mingle 프로젝트</h2>

![Group 807](https://github.com/goorm-hackathon-dadamingle/dadamingle/assets/123868471/7d16aa51-40cc-4dd9-99d8-7204a2b05f1b)


<h2>💡 코드 컨벤션</h2>

<aside>
함수명, 변수명은 카멜케이스로 작성합니다.

</aside>
<br/>
<br/>
<aside>
boolean값은 접두어 is-를 붙여 카멜케이스로 작성합니다.

</aside>
<br/>
<br/>
<aside>
이벤트 핸들러 함수는은 접두어 handle-을 붙여 카멜케이스로 작성합니다.

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
컴포넌트는 폴더명(파스칼케이스)/파일명(파스칼케이스, 폴더명과 동일) <br/>
- ex) components/Button/Button.tsx <br/>
- ex) _components/Button/Button.tsx

</aside>
<br/>
<br/>

<aside>
컴포넌트 제외한 일반 폴더명은 스네이크 케이스 고려 ex) sign_up

</aside>
<br/>

<br>
<h2>🧑🏻‍💻 팀원</h2>

<table>
  <tr>
    <td>
      <a href="https://github.com/stop0ho">
        <img src="https://avatars.githubusercontent.com/u/68852637?v=4" width="120px" height="120px"/>
      </a>  
    </td>
     <td>
      <a href="https://github.com/zivivle">
        <img src="https://avatars.githubusercontent.com/u/123868471?v=4" width="120px" height="120px"/>
      </a>  
    </td>
    <td>
      <a href="https://github.com/choiminwoo98">
        <img src="https://avatars.githubusercontent.com/u/61531483?v=4" width="120px" height="120px"/>
      </a>  
    </td>
  </tr>
  <tr>
    <th>
      정지호
    </th>
    <th>
      지성경
    </th>
    <th>
      최민우
    </th>
  </tr>
  <tr>
    <th>
       프론트엔드
    </th>
    <th>
       프론트엔드
    </th>
    <th>
       프론트엔드
    </th>
  </tr>
  
  <tr>
    <td>
      <a href="https://github.com/wlstnam">
        <img src="https://avatars.githubusercontent.com/u/127458907?v=4" width="120px" height="120px"/>
      </a>  
    </td>
     <td>
      <a href="https://github.com/sbslc2000">
        <img src="https://avatars.githubusercontent.com/u/60257970?v=4" width="120px" height="120px"/>
      </a>  
    </td>
    <td>
      <a href="https://github.com/hstla">
        <img src="https://avatars.githubusercontent.com/u/83001865?v=4" width="120px" height="120px"/>
      </a>  
    </td>
     
  </tr>
  <tr>
    <th>
      남진수
    </th>
    <th>
      서범석
    </th>
    <th>
      황현성
    </th>
  </tr>
  <tr>
    <th>
       백엔드
    </th>
    <th>
       백엔드
    </th>
    <th>
       백엔드
    </th>
  </tr>
</table>


<br/>

<h2>📁 폴더 구조(app Router 방식)</h2>

<aside>

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

<h2> 🎃 사용 스택 및 라이브러리 </h2>

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

<h2>커밋 컨벤션</h2>

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
