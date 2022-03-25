---
tags: [carat, commerce-hub, enterprise, payment-source-types]
---

# Payment Source Types

The variable `sourceType` is used to determine the source of the transaction. Depending on the source the required variables change. 

| sourceType | Description |
| ----- | ----- |
| [GooglePay](?path=docs/Online-Mobile-Digital/Wallets-AltPayments/Google-Pay/Google-Pay.md) | **Google Pay** |
| [SamsungPay]<!---(?path=docs/Online-Mobile-Digital/Wallets-AltPayments/Samsung-Pay/Samsung-Pay.md)---> | **Samsung Pay** |
| [DecryptedWallet](?path=docs/Resources/Guides/Payment-Sources/Decrypted-Wallet.md) | **Decrypted Wallet** |
| [NetworkToken]<!--(?path=docs/Resources/Guides/Payment-Sources/Network-Token.md)--> | **Network Token** |
| [Payment3DS](?path=docs/Online-Mobile-Digital/3D-Secure/3DSecure.md) | **3-D Secure** |
<!---(?path=docs/Online-Mobile-Digital/Wallets-AltPayments/Samsung-Pay/Samsung-Pay.md)--->
---

<!-- type: tab -->

JSON string format for `additionalDataCommon`:
<!---(?path=docs/Online-Mobile-Digital/Wallets-AltPayments/Samsung-Pay/Samsung-Pay.md)--->
```json
{
   "additionalDataCommon":{
      "additionalData":{
         "baiFlag": "PERSON_TO_PERSON",
         "ecomURL":"https://www.somedomain.com",
         "requestedTestResponseCode":"NO_CONNECTION_AVAILABLE",
         "emvParameterDownloadIndicator":true
      }
   }
}
```
<!---(?path=docs/Online-Mobile-Digital/Wallets-AltPayments/Samsung-Pay/Samsung-Pay.md)--->
<!-- type: tab-end -->

---