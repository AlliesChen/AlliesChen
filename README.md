# Yu-Pang

<!--
**AlliesChen/AlliesChen** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

Hi, 我是位前端工程師，非資訊本科生，做過企劃、PM，最後發現自己喜歡寫程式。想方設法地大量攝取技術知識，也努力補齊基礎學科知識；像透過哈佛的 CS50 課程，在課程中用了 C、Python、SQL，和實作了演算法、後端和網頁。

📝 我會把學習到的知識寫成文章：

- [Linkedin](https://www.linkedin.com/in/ypchen-1057a5137/)：大概一周寫一篇技術的筆記貼文，或是轉貼文章加上閱讀心得。
- [個人部落格](https://allieschen.github.io/)：用 Hugo 做的，放在GitHub上，怎麼做的也寫了文章放裡面；文章大多放我實作某個項目時遇到的問題和心得。
- [Dev.to](https://dev.to/allieschen)：練習純英文寫作。

👋 我也參加了 2022 iThome 鐵人賽 (自我挑戰組)：[從前端角度看30天學Python](https://ithelp.ithome.com.tw/users/20151651/ironman/5346)

## Languages and Tools

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Vue.js](https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)
![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=allieschen&layout=compact&theme=tokyonight)

## Side Project

目前多是小型應用，著重練習特定的技術，像使用 socket.io、SCSS、TypeScript，或是練習 JS 框架像 React、Vue 等。部份專案有參考的教學，但我會再增加自己的想法去改動，比如 React 換 Vue， Bootstrap 換 Tailwind，讓自己不被框架侷限，專注在想法的實現。

### [MERN-stack](https://github.com/AlliesChen/MERN-stack) (no live demo)

練習撰寫全端網頁應用，這個 web app 功能是讓使用者紀錄健身的項目與資訊。

- [後端](https://github.com/AlliesChen/MERN-stack/tree/main/backend)
  - 使用 Node.js 搭配 Express 框架簡化撰寫複雜度。
  - 以 JWT 驗證使用者身份，並設定 id 以 cookie 傳遞，加入 `httpOnly` 和 `sameSite` 設定期望能對 XSS 與 CSRF 有比較好的防禦效果。我也寫了一篇文章記錄 - [JWT簡介 - 使用Node.js](https://allieschen.github.io/posts/jwt_with_node_js/)
  - 資料庫透過 `mongoose` 套件使用 MongoDB。
- [前端](https://github.com/AlliesChen/MERN-stack/tree/main/frontend)使用 Preact 製作，以 vite 建立。使用 preact-router、context API 與 useReducer，再佐以 JSDoc (和一些 .d.ts檔)加入型別註解。

## [vue-chatroom](https://github.com/AlliesChen/vue-chatroom)

[Live demo](https://vue-chatroom.fly.dev/)

為練習使用 socket.io 做的簡易聊天室，自訂一個使用者名稱及房間名稱即可在視窗間互傳資訊，沒有使用資料庫，所以訊息不會留存下來。

- 後端使用 Node.js + express
- 前端以 Vite 建立，使用 Vue 3 composition API 搭配 TypeScript。
  - 樣式部份使用 scss，透過 [@mixin、@for](https://github.com/AlliesChen/vue-chatroom/blob/main/client/src/styles/_utilities.scss) 做出像是 Tailwind CSS 那樣，基於 Atomic CSS 概念，高複用性的 class。也使用 CSS 原生的 @layer，分開基底的樣式與前述的組件樣式([這個檔案](https://github.com/AlliesChen/vue-chatroom/blob/main/client/src/styles/_base.scss))。
  - 使用 scrollIntoView 這個 Web API 讓收到訊息時對話框會自動捲到底。

## Photo book (no live demo)

入職時主管出的題目，先使用 Vanilla JS 製作一次，再改用 Vue 2 做，並繼續增加功能。

[photo-gallery](https://github.com/AlliesChen/photo-gallery)：結構上以 script.js 這支檔案為入口，當時想以元件化的概念去寫，所以將畫面有關的程式碼放在 [views](https://github.com/AlliesChen/photo-gallery/tree/main/static/views) 資料夾，操作的邏輯放在 [controls](https://github.com/AlliesChen/photo-gallery/tree/main/static/controls) 資料夾。

\**後來才知道有 web component 這個技術 😅*

[photo-vue](https://github.com/AlliesChen/photo-vue)：顧名思義，使用 vue-cli 建立 Vue 2 並重新撰寫 photo-gallery 的功能，搭配套件 vuex、vue-router，樣式使用 scss 並以 Atomic CSS 的概念去寫 class。
- 邏輯上我將與畫面有關的元件放在 [views](https://github.com/AlliesChen/photo-vue/tree/main/src/views) 資料夾，會與後端溝通的元件放在 [components](https://github.com/AlliesChen/photo-vue/tree/main/src/components) 資料夾，目的是做關注點分離。
- 另外我也有實驗狀態管理的套件 - pinia 用在 Vue 2 會是什麼樣子(在 [branch - pinia](https://github.com/AlliesChen/photo-vue/blob/pinia/src/store/status_cp.js))。

## React 搭配 TypeScript

[react-shopping-cart](https://github.com/AlliesChen/react-shopping-cart)：練習搭配 Tailwind CSS，加入 RWD。

[simple-resume-react](https://github.com/AlliesChen/simple-resume-react)：使用 Chakra UI 元件建立。

[next-list](https://github.com/AlliesChen/next-list)：單純想玩玩看 Next.js。

## Vanilla JavaScript

[todolist](https://github.com/AlliesChen/todolist)：一個待辦清單的 web app，使用 webpack 打包，透過 `MiniCssExtractPlugin` 獨立出 CSS 檔案到打包後的 html 檔裡，以及 `HtmlWebpackPlugin` 讓每次打包後重新生成亂數名稱的檔案到 dist 資料夾，避免瀏覽器快取到舊的。

[weather-app](https://github.com/AlliesChen/weather-app)：練習 API 串接，使用 OpenWeather API，可以透過瀏覽器定位提供使用者所在城市的天氣資訊，或是輸入城市名稱查詢天氣。

[calculator](https://github.com/AlliesChen/calculator)：最一開始學習 JS 做的計算機，支援鍵盤輸入，在浮點數計算、數字溢位，和除以零等狀況做了處理；浮點數會先轉成整數，計算完再除回去，避免因 IEEE-754 而有的 $0.1 + 0.2 \neq 0.3$。

## 小遊戲系列 have fun!

[quizzical-trivia](https://github.com/AlliesChen/quizzical-trivia)：使用 React 做的豆知識問答集，串接 Trivia API。

[tenzies-game](https://github.com/AlliesChen/tenzies-game)：React 做的骰子遊戲，所有骰子的點數都一樣就勝利了。

[tic-tac-toe](https://github.com/AlliesChen/tic-tac-toe)：純 JS 寫的井字棋(圈圈叉叉)遊戲，困難模式下用 minMax 演算法的概念，讓電腦不會輸。

## 其他：

[flask-api](https://github.com/AlliesChen/flask-api)：我在 2022 iThome鐵人賽中的一篇文章教學所做，旨在透過 `pymongo` 套件應用 MongoDB 的建立 API server。

[leetcode-practices](https://github.com/AlliesChen/leetcode-practices)：練習解 Leetcode。
