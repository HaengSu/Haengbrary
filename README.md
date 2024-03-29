# HaengBrary
  - The Happiness Library is a collection of features that everyone can use when building Android apps.

-- 

## Quick Start
    1. import haengbrary
    implementation 'com.haeng.haengbrary:utils:1.0.0'
    implementation 'com.haeng.haengbrary:appinitialize:1.0.0'

    2. use haengbrary
    //permission
    HPermission(this).requestPermission()

---

## Appinitialize
- version : 1.0.0   (2024/03/28)
- 앱 초기화(첫 시작)시에 사용해야 하는 기능이 있는 라이브러리 
- 항목
  - Permission
  - internet check
  - network check
    - 현재 네트워크에 연결이 되었는지 확인하는 예시코드
      ```kotlin
      NetworkManager(this).checkNetworkConnection(NetworkType.WIFI)
      ```
   
    - 현재 인터넷이 사용가능한지 확인하는 예시코드
      ```kotlin
      InternetManager().isConnectedToInternet()
      ```

    - 권한 요청
      ```kotlin
       HPermission(this).requestPermission()
      ```
 
---

## Utils
- version : 1.0.0   (2024/03/29)
- 앱 사용중 필요한 utils를 모아둔 라이브러리

- 항목
  - ClearEdittext
    ```xml
    <com.haeng.haegnbrary.utils.ClearEditText
    .../>
    ```
