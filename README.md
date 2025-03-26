# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

.navbar {
display: flex;
padding: 20px 6%;
position: fixed;
width: 100%;
z-index: 1;
justify-content: space-between;
font-size: 14px;
color: #e5e5e5;
background-image: linear-gradient(
180deg,
rgba(0, 0, 0, 0.7) 10%,
transparent
);
}

.navbar-left {
display: flex;
align-items: center;
gap: 50px;
}
.navbar-left img {
width: 90px;
}
.navbar-left ul {
display: flex;
gap: 20px;
list-style: none;
}
.navbar-left ul li {
cursor: pointer;
}
.navbar-right {
display: flex;
align-items: center;
gap: 20px;
}
.navbar-right .icons {
width: 20px;
cursor: pointer;
}
.navbar-right .profile {
width: 35px;

border-radius: 4px;
}
.navbar-profile {
display: flex;
align-items: center;
gap: 10px;
cursor: pointer;
position: relative;
}
.navbar .dropdown {
position: absolute;
top: 100%;
right: 0;
width: max-content;
background: #191919;
padding: 18px 22px;
border-radius: 2px;
z-index: 1;
text-decoration: underline;
display: none;
}

.navbar .dropdown p {
font-size: 13px;

cursor: pointer;
}

.navbar-profile:hover .dropdown {
display: block;
}
.nav-dark {
background: #141414;
}

@media (max-width: 800px) {
.navbar {
padding: 20px 4%;
}
.navbar img {
height: 25px;
}

.navbar-left ul {
display: none;
}
}
@media (max-width: 500px) {
.navbar img {
height: 20px;
}

.navbar-right {
gap: 10px;
}
}

.navbar-right .dark {
width: 25px;
cursor: pointer;
}

<TitleCards title={"Blockbuster Movies"} category={"top_rated}"} />
