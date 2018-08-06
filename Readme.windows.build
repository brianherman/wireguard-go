Wireguard Windows Build
=======================
1. Download go from `https://dl.google.com/go/go1.10.3.windows-amd64.msi`
2. Download git from `https://git-scm.com/download/win`
3. Press `Windows Key + R` to get into the run menu
4. Type `cmd.exe` into the prompt
5. `cd %HOMEPATH%\go\src`
6. `mkdir git.zx2c4.com`
7. `git clone https://git.zx2c4.com/wireguard-go`
8. `cd wireguard-go\src`
9. `go env` should look similar to this:
```C:\Users\bherman.RANDOM\go\src\git.zx2c4.com\wireguard-go\src>go env
set GOARCH=amd64
set GOBIN=
set GOCACHE=C:\Users\bherman.RANDOM\AppData\Local\go-build
set GOEXE=.exe
set GOHOSTARCH=amd64
set GOHOSTOS=windows
set GOOS=windows
set GOPATH=C:\Users\bherman.RANDOM\go
set GORACE=
set GOROOT=C:\Go
set GOTMPDIR=
set GOTOOLDIR=C:\Go\pkg\tool\windows_amd64
set GCCGO=gccgo
set CC=gcc
set CXX=g++
set CGO_ENABLED=1
set CGO_CFLAGS=-g -O2
set CGO_CPPFLAGS=
set CGO_CXXFLAGS=-g -O2
set CGO_FFLAGS=-g -O2
set CGO_LDFLAGS=-g -O2
set PKG_CONFIG=pkg-config
set GOGCCFLAGS=-m64 -mthreads -fmessage-length=0 -fdebug-prefix-map=C:\Users\BHERMA~1.RAN\AppData\Local\Temp\go-build891771962=/tmp/go-build -gno-record-gcc-switches```
10. If it does not you have did something wrong.
12. Run the build script under the windows branch
```git checkout windows```
```.\build.cmd```
EOF. This is only a piece of getting wireguard working in windows currently the TAP adapter does not work unless I get more instructions or look at the code.
