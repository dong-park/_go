# _GO
## GO Install
[Install Page](http://golang.org/dl)

## GO Manual
1. Go project의 디렉토리 구조 안에 안에 bin, pkg, src 서브 폴더를 만들어 준다.
> Go는 2개의 중요한 환경변수(GOROOT와 GOPATH)를 사용한다.
> * GOROOT: Go가 설치된 디렉토리(윈도우즈의 경우 디폴트로 C:\Go)를 가리키며, Go 실행파일은 GOROOT/bin 폴더에, Go 표준 패키지들은 GOROOT/pkg 폴더에 있다. (윈도우즈에 GO 설치시 시스템 환경변수로 자동으로 설정된다)
> * GOPATH: Go는 표준 패키지 이외의 3rd Party 패키지나 사용자 정의 패키지들을 이 GOPATH 에서 찾는다. 복수 개의 경로를 지정한 경우, 3rd Party 패키지는 처음 경로에 설치된다
2. 데이터 타입
   - 부울린 타입
     - bool
   - 문자열 타입
     - string: string은 한번 생성되면 수정될 수 없는 Immutable 타입임
   - 정수형 타입
     - int int8 int16 int32 int64
     - uint uint8 uint16 uint32 uint64 uintptr
   - Float 및 복소수 타입
     - float32 float64 complex64 complex128
   - 기타 타입
     - byte: uint8과 동일하며 바이트 코드에 사용
     - rune: int32과 동일하며 유니코드 코드포인트에 사용한다
 


