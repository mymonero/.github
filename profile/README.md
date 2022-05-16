
<p align="center">
  <img alt="MyMonero" src="https://user-images.githubusercontent.com/1645428/146000939-b06f8fd3-9ed2-4a5e-bdd6-3981281dde9c.png">
</p>

# About MyMonero


The simplest way to use the next-generation private digital currency Monero, at the sweet spot between security, convenience, and features

---

MyMonero has created a number of open source wallets and libraries that support the Monero light wallet interface.

If you are looking for one of our wallets to download here are the links to the correct repositories:

* [MyMonero Desktop](https://github.com/mymonero/mymonero-app-js): Desktop wallets for MacOs, Linux and Windows.
* [MyMonero Mobile](https://github.com/mymonero/mymonero-mobile): Mobile apps for both Android and iOS.
* [MyMonero Web](https://github.com/mymonero/mymonero-web-js): Web wallet accessible from any device that supports a standard web browser with js support.

Our open source libraries are contained within our [mono-repo](https://github.com/mymonero/mymonero-utils). This contains all our shared code used within our apps as well as 3 noticible packages used within our enterprise SDK these are:

* [lws-client](https://github.com/mymonero/mymonero-utils/tree/master/packages/mymonero-lws-client): handles communication with a light wallet server
* [monero-client](https://github.com/mymonero/mymonero-utils/tree/master/packages/mymonero-monero-client): handling the connector to the monero client for key imaging, creating transactions as well as generating new wallets.
* [wallet-manager](https://github.com/mymonero/mymonero-utils/tree/master/packages/mymonero-wallet-manager): MyMonero sdk for building wallets. Has a number of classes that will speedup development or server as examples.

