# Objetivo

Esse projeto foi criado para compreender as estruturas dos arquivos. Removendo vários componentes, mantendo a página de login com dois tipos diferentes de layouts (admin e auth) e alguns componentes para organização e formatação.

## Estrutura dos arquivos

Dentro de LoginPage-React encontrará os seguintes arquivos.
```
LoginPage-React
│
├── public
│   ├──apple-icon.png
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
└── src
    ├── index.js
    ├── routes.js
    ├── assets
    │   ├── img
    │   │   ├── faces
    │   │   ├── flags
    │   ├── jss
    │   │   ├── material-dashboard-pro-react
    │   │   │   ├── components
    │   │   │   ├── layouts
    │   │   │   └── views
    │   │   └── material-dashboard-pro-react.jsx
    │   └── scss
    │       ├── material-dashboard-pro-react
    │       │   ├── mixins
    │       │   └── plugins
    │       └── material-dashboard-pro-react.scss
    ├── components
    │   ├── Card
    │   │   ├── Card.jsx
    │   │   ├── CardBody.jsx
    │   │   ├── CardFooter.jsx
    │   │   └── CardHeader.jsx
    │   ├── CustomButtons
    │   │   └── Button.jsx
    │   ├── CustomInput
    │   │   └── CustomInput.jsx
    │   ├── Footer
    │   │   └── Footer.jsx
    │   ├── Grid
    │   │   ├── GridContainer.jsx
    │   │   └── GridItem.jsx
    │   ├── Navbars
    │   │   └── AuthVavbar.jsx
    │   ├── Sidebar
    │   │   └── Sidebar.jsx
    ├── layouts
    │   ├── Admin.jsx
    │   ├── Auth.jsx
    │   └── RTL.jsx
    └── views
        ├── Pages
        │   ├── LoginPage.jsx
```