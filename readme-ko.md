[english](https://github.com/TinkeringBase/chargemaster-500)
# TinkeringBase Chargemaster 500
![preview](https://github.com/TinkeringBase/chargemaster-500/blob/main/3dpreview.png?raw=true)\
TP4057을 기반으로 한 배터리 충전 모듈입니다. 500mA 속도로 리튬이온/리튬폴리머 배터리를 충전할 수 있습니다. 시스템 패스와 과충전 방지 기능을 가지고 있습니다. 내장 MOSFET을 이용해 전원이 연결되면 자동으로 배터리와 출력 연결을 끊습니다.
## 커넥터
MOLEX 51021 RB 타입 커넥터를 사용합니다. 국내에서 판매하는 DTP사와 TW사의 배터리가 호환됩니다. 연결하기 전 항상 극성을 확인하십시오.\
![adsf](https://github.com/TinkeringBase/chargemaster-500/assets/47267045/8cbb29fd-9ee4-4e2c-87f2-7d67e7da962e)
### 보호
일반적인 TP4056 모듈과는 다르게, 이 모듈은 과방전 방지와 과전류 방지를 제공하지 않습니다. 때문에 보호 회로가 내장된 배터리 팩을 사용하거나, 추가적인 배터리 보호 회로를 사용해야 합니다.
