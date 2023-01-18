```bat
cargo build -q | .\target\debug\httpie.exe get https://httpbin.org/get
cargo build -q | .\target\debug\httpie.exe post https://httpbin.org/post greeting=hola name=Tyr
```
