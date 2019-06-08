# Quickly build Event Website Template

快速搭建一個 Event base 的 Website

簡單說就個 web build 好之後，可以透過 web 上簡單的操作設地活動內容、票價、地點...等基本資訊

至於像整個網頁細節的部分則需要從 code 修改，之後再除新 build 和 deploy

這樣的好處是方便特定團體或組織辦活動，透過 web 上簡單操作快速發布活動資訊

## SOP Step

主要是 follow source code 的說明

- Source code README **Getting Started 1-9**

  - 第九點的說明是在 **src/environments** 資料夾

- Source Code README **Managing Data/Site Setup**

  - 設定 web authentication (google 帳號)

  - 設定 web database (Realtime) admins (google 帳號)

- ng serve 可以在 local 叫出 web

- Build (ng build)

- Deploy (np deploy)

  - 應該是 deploy 到 gcp

最後成品[在這裡](https://wtm-event-web.firebaseapp.com/home)

## Reference

- [meetup web](https://wtm-taipei-lighting-talk-0.firebaseapp.com/home)

- [Source code](https://github.com/gdg-x/DeLorean-v2)