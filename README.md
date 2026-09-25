## Screenshots
![pintu-fulicat com-1739372828559](https://github.com/user-attachments/assets/bfeecf8b-35c0-4e7d-83db-720b9f2326cf)



## How to build?
```shell
git clone https://github.com/Houvven/OplusUpdater-Android.git
cd OplusUpdater-Android/OplusUpdater
go get golang.org/x/mobile/bind
gomobile init
gomobile bind -target=android -androidapi 26 -v ./pkg/updater
cd ..
./gradlew assemble
```
if you not install gomobile, you can install it by:
```shell
go install golang.org/x/mobile/cmd/gomobile@latest
```

## Credits
- [miuix](https://github.com/miuix-kotlin-multiplatform/miuix)
- [go-mobile](https://github.com/golang/mobile)
- https://downval.csy.tcdnos.com/aclos/release/2.13.1.393/VALORANT_CN_installer_v2.13.1.393.exe?mkey=lego_ztc&f=00&sche_type=7&cip=123.8.116.191&proto=https&tx_domain=down.val.qq.com&tx_path=%2Faclos%2F&tx_id=6c9382a8c8
