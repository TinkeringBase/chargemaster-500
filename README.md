[한국어](https://github.com/TinkeringBase/chargemaster-500/blob/main/readme-ko.md)
# TinkeringBase Chargemaster 500
![preview](https://github.com/TinkeringBase/chargemaster-500/blob/main/3dpreview.png?raw=true)\
Battery charger based on TP4057. It can charge lithium ion/polymer batteries at up to 500mA speed. Provides overcharge protection, system pass. It automatically disconnects the battery from system load via onboard MOSFET.
## Connector
It accepts MOLEX 51021 RB type connector. Always check the polarity before connecting.\
![adsf](https://github.com/TinkeringBase/chargemaster-500/assets/47267045/8cbb29fd-9ee4-4e2c-87f2-7d67e7da962e)
### Protection
Unlike generic TP4056 module, this module does not provide overcurrent protection and overdischarge protection. You need to use protected battery pack or add external protection board.
