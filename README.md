# 수아파파의 뚝딱뚝딱 - 스트리밍 로그

[트위치-수아파파의 뚝딱뚝딱](https://twitch.tv/suapapa)

## 20200615-20200617

[eddystone](https://pkg.go.dev/github.com/suapapa/go_eddystone) 비콘 패키지를 손보고, 유명한,
`muka/go-bluetooth` 에 풀리퀘를 넣어 봅니다.

* [x] 5년 묵힌 에디스톤 비콘 패키지 손 봅니다. ==> 완료
* [x] EID Frame 구현 ==> 완료
* [x] MakeUIDFrame 리펙토링 ==> 완료
* [x] muka/go-bluetooth에 풀리퀘도 해 봅니다. ==> [머지됨](https://github.com/muka/go-bluetooth/pull/110)

[golangkorea/lotto](https://github.com/golangkorea/lotto) 프로그램에도 전에 트위치로또
만들며 정리한 내용을 풀리퀘 합니다. ==> 완료


## 20200612-20200614

라즈베리파이 - I2C CLCD 드라이버 만들기 ==> 완료

* 결과물: [github.com/suapapa/go_devices/pcf8574clcd](https://pkg.go.dev/github.com/suapapa/go_devices@v1.0.1/pcf8574clcd?tab=doc)


## 20200611

텍스트 파싱 -> csv로 만들어 엑셀에서 열기 ==> 완료

* 결과물: [gist](https://gist.github.com/suapapa/79cb476cafb8185d2b54473b66849123)


## 20200610

어제 기다리던 캐슁이 아직도 안됨? 뭔가 문제가 있나? ==> 됨
ebiten이라는 크로스플렛폼 고 게임 메이킹 라이브러리 살펴볼 예정 ==> 보다 맒

* [ebiten](https://github.com/hajimehoshi/ebiten)

라즈베리파이 크로스컴파일 (CGo) 해 보기 ==> 해보다 맒

    CC=x86_64-pc-linux-gcc GOOS=linux GOARCH=amd64 CGO_ENABLED=1 go build

* [prebuilt cross compiler for rpi](https://github.com/abhiTronix/raspberry-pi-cross-compilers)


## 20200609

한글라이즈(홍민희님) 한글 패키지 업데이트 풀리퀘 작성 ==> [머지됨](https://github.com/hangulize/hangulize/pull/13)

* [한글라이즈](https://hangulize.org)
* [한글라이즈-코드](https://github.com/hangulize/hangulize)

* [한글](https://github.com/suapapa/go_hangul) v1.1.0 -> v1.2.1 로 버전 업
* [pkg.go.dev](https://pkg.go.dev/github.com/suapapa/go_hangul) 에 아직 캐슁되지 않음==> 됨

Update pkg.go.dev cache: [adding-a-package](https://go.dev/about#adding-a-package)

    curl -X GET https://proxy.golang.org/github.com/suapapa/go_hangul/@v/v1.2.1.info


## 20200608

아두이노-네오픽셀-프로토버퍼 끊김 현상 디버깅. --> 수정완료!

* 결과물: https://github.com/suapapa/pb-neopixel


## 20200606-20200607

아두이노(esp8266) 네오픽셀 프로토버퍼로 메세지 만들어 제어해 봄.
그냥 불 켜지는 예제 말고, 예쁜 예제(rainbow chase) 만듦

* 결과물: https://github.com/suapapa/pb-neopixel


## 20200604-20200605

khaiii 와 함께 사용할 품사 설명 패키지

* 결과물: https://github.com/suapapa/go_krpos

STL을 모델을 OpenGL4로 그려봄 -> 망함. 쉐이더가 뭔지 모르겠음;;


## 20200603

TM1638 모듈을 사용한 FND 트위치 팔로워 카운터

* 결과물: https://github.com/suapapa/fnd-twitch-counter


## 20200602

TM1638 모듈 드라이버 패키지. periph.io 기반 재 작성

* 결과물: github.com/suapapa/go_deivces/tm1638


## 20200601

닉시 트위치 팔로워 카운터 -> 망함 (하드웨어불량)

* 결과물: https://github.com/suapapa/nixie-twitch-counter


## 20200529-20200601

트위치 API 사용해 추첨 프로그램 만들기 <-- 50 팔로워 달성시 사용

* 결과물: https://github.com/suapapa/twitch-lotto


## 20200527-20200528

khaiii (Kakao Hangul Analyzer III, 카카오 형테소 분석기 3) 를
고 패키지로 말아봅니다. (CGo) -> 완료

* 결과물: https://github.com/suapapa/go_khaiii


## 20200525-20200526

Jekyll로 만들었던 이력서가 더이상 빌드가 되지 않아 갱신을 못하고 있음.
기존에 생선된 gh-pages 브랜치의 index.html 파일만 탬플릿으로 변경해보고,
예전에 yaml로 정리했던 이력서 내용을 그대로 적용해 봄. -> 완료

* 결과물: https://github.com/suapapa/resume


## 20200523-20200524

SDL1으로 만들었던 고 동시성 예제 게임, whack-a-gopher를 WebAssembly + canvas 로 포팅

* 결과물: https://github.com/suapapa/whack-a-gopher/

