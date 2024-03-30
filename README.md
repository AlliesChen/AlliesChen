# Yu-Pung

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

Hi, 我是位網頁應用開發，持續透過 MooC 來補足基礎學科知識中，目前做過：

- [UCB cs61a fa21](https://github.com/AlliesChen/cs61a_fa21)
- 哈佛 cs50

正在挑戰：

- [UCB cs61b sp21](https://github.com/AlliesChen/cs61b-sp21)

寫過一些小知識文章：

- [個人部落格](https://allieschen.github.io/)：用 Hugo 做的，放在GitHub上，怎麼做的也寫了文章放裡面；文章大多放我實作某個項目時遇到的問題和心得。
- [Dev.to](https://dev.to/allieschen)：用英文撰寫的文章會往這邊丟。
- 2022 iThome 鐵人賽 (自我挑戰組)：[從前端角度看30天學Python](https://ithelp.ithome.com.tw/users/20151651/ironman/5346)

## Languages and Tools

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Vue.js](https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)
![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=allieschen&layout=compact&theme=tokyonight)

## 轉職期間做的小專案

### Simple Resume

[Live demo](https://allieschen.github.io/simple-resume-react/) | [Repo](https://github.com/AlliesChen/simple-resume-react)

使用 React 搭配 TypeScript 以及 Chakra UI 建立，資料單純存在 `localStorage` 沒有搭配後端。

### TODO List

[Live demo](https://allieschen.github.io/todolist/) | [Repo](https://github.com/AlliesChen/todolist)：

使用 webpack 打包，透過 `MiniCssExtractPlugin` 獨立出 CSS 檔案到打包後的 html 檔裡，以及 `HtmlWebpackPlugin` 讓每次打包後重新生成亂數名稱的檔案到 dist 資料夾，避免瀏覽器快取到舊的。

### Calculator

[Live demo](https://allieschen.github.io/calculator/) | [Repo](https://github.com/AlliesChen/calculator)

簡易計算機，支援鍵盤輸入，在浮點數計算、數字溢位，和除以零等狀況做了處理；浮點數會先轉成整數，計算完再除回去，避免因 IEEE-754 而有的 $0.1 + 0.2 \neq 0.3$。

### Tic Tac Toe

[Live demo](https://allieschen.github.io/tic-tac-toe/) | [Repo](https://github.com/AlliesChen/tic-tac-toe)

井字棋(圈圈叉叉)遊戲，困難模式下用 minMax 演算法的概念，讓電腦不會輸。

## 其他：

[flask-api](https://github.com/AlliesChen/flask-api)：我在 2022 iThome鐵人賽中的一篇文章教學所做，旨在透過 `pymongo` 套件應用 MongoDB 的建立 API server。

[leetcode-practices](https://github.com/AlliesChen/leetcode-practices)：練習解 Leetcode。
