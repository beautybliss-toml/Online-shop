<div id='top' align="center">

![ZiShop](public/images/logo.png)

An E-commerce site template, implemented with [Next.js](https://nextjs.org/) and [TypeScript](https://www.typescriptlang.org/). Styled with [TailwindCSS](https://tailwindcss.com/). This is one of my portfolios, but I would be pleased if these codes helped others, so I published it as an open-source project. feel free to explore it, and if you need help, ask me. I would respond as soon as possible.
<p>To support me, please create <strong>Pull request</strong> and give <strong>star⭐</strong> to this repository.<br/>
   I appreciate your support in advance. ❤</p>

<p>

</p>

<p>

[Technologies](#technologies) •
[Features](#features) •
[Pages](#pages) •
[Getting started](#getting-started) •
[Contributing](#contributing) •
[Contact Me](#contact-me)
  
</p>
<img src="/public/images/zishopBanner.png"/>
</div>

## 🔧Technologies
![React](https://img.shields.io/badge/-React-05122A?style=for-the-badge&logo=react)&nbsp;
![TypeScript](https://img.shields.io/badge/-TypeScript-05122A?style=for-the-badge&logo=typescript)&nbsp;
![Next.js](https://img.shields.io/badge/-Next.js-05122A?style=for-the-badge&logo=next.js)&nbsp;
![Redux](https://img.shields.io/badge/-Redux-05122A?style=for-the-badge&logo=redux&logoColor=764ABC)&nbsp;
![Tailwind CSS](https://img.shields.io/badge/-TailwindCSS-05122A?style=for-the-badge&logo=tailwindCSS&logoColor=06B6D4)


## 🔥Features
* Using Redux toolkit as state manager
* Using [Sanity.io](https://www.sanity.io/) as database
* Fully responsive
* Multi-language (EN-FA)
* Multi-theme (Dark/Light)

## 📃Pages
* Main (index)
* Login/SignUp
* Products List
* Product Details
* Cart
* Favorites
* About
<p align="right">(<a href="#top">BACK TO TOP 🔝</a>)</p>

## 🚀Getting Started
1. Sign up in [sanity.io](https://www.sanity.io/) and get `projectId` and `token`

> **Warning**&nbsp;
> To work with sanity, people who live in Iran should use a `VPN`.

2. Clone the project
  ```bash
  git clone https://github.com/beautybliss-toml/online-shop.git
  ```
3. Install project dependencies
  ```bash
  npm install
  #or
  yarn add
  ```
4. Enter your `projectId` into `lib/client.ts`
5. Add `.env` file to root project, and enter your `token` into `.env`
  ```js
  NEXT_PUBLIC_SANITY_TOKEN= [ENTER YOUR TOKEN]
  ```
6. Go to sanity_onlineshop folder and open new terminal in this path, then
  ```bash
  sanity start
  ```
open `http://localhost:3333` and enter products.
 
7. Run the development server in project root path:

  ```bash
  npm run dev
  # or
  yarn dev
  ```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

## 🤝Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



