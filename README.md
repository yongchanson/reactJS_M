yarn add global react-scripts

# ReactJs No

### 7.2
useEffect
- component가 처음으로 render시 / 함수를 즉시실행시킬때 사용
- 한번만 실행시킬 때 빈배열을 사용 `useEffect(() => {}, [])`

useState
- date를 component에 보여줄때 사용 `const [conis, setCoins] = useState([])`

# ReactJs Master

- 2.7 Theme
  - 기본적으로 모든 색상들을 가지고 있는 object
- 4.7 Nasted Routes
  - 라우터 안에 라우터(보통 탭에 사용)
-  4.10 useQuery(Hook)
  - 모든 state, fetch 대체
-  5.0 Recoil
  - ReactJs 상태관리 library!(nodeJS 미들웨어와 비슷한 역할)
- 5.4 useRecoilValue
  - `const isDark(원하는값) = useRecoilValue(atom)`
- 5.4 useSetRecoilState
  - atom(매개변수)을 받고 atom을 변경하는 함수 반환(atom을 변경하는 것)
  - `const setDarkAtom = useSetRecoilState(atom)`
  - `const toggle = setDarkAtom((prev) => !prev)`                     
  - `const toggle = setDarkAtom(true))`                      
                        
