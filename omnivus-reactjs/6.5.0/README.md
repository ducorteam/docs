#  Welcome To Omnivus - IT solutions, digital services, and business agencies theme 

Firstly, a huge thanks for purchasing this theme, your support is truly appreciated!

This document covers the installation and use of this theme and often reveals answers to common problems and issues - read this document thoroughly if you are experiencing any difficulties. If you have any questions that are beyond the scope of this document, feel free to email at [suppot@ducor.net](mailto:__EMAIL__) Thank you so much!

## Basic

1.  After unzip the download pack, you'll found a Template Folder with all the files.
2.  You can view this Template in any browser, you can display or edit the Template without an internet connection.(May not wotrk fonts and google map).
3.  This section that will not work is the Contact Section

- **Omnivus Template**: An installable React.js template zip file.
- **Documentation Folder**: Contains this documentation you are reading now.

Here’s an overview of the included files:

![image](./fils.png)  

#### ⚛️ Project Installation 
Ensure that you have Node.js (v16 or higher) installed on your system. To verify your Node.js version, run the following command:
```bash
node -v
```
You also need Yarn installed globally. If you do not have Yarn, install it using the following command:
```bash
npm install -g yarn
```
Verify Yarn installation with:
```bash
yarn -v
```
1.  Open your terminal or command prompt.
2.  Navigate to the project folder.
   ```bash
   cd omnivus-reactjs
   ``` 
3.  Run the following commands to set up the project:

  Yarn is an established open-source package manager used to manage dependencies in JavaScript projects. It assists with the process of 
  installing, updating, configuring, and removing packages dependencies, eventually helping you reach your objectives faster with fewer 
  distractions.

 > **Note**: Unlike most other package managers, which typically defer to npm for non-install-related commands, Yarn reimplements all 
 commands, so as to have full control over our developer experience and stability. 
 **Install Dependencies:**
 ```bash
  yarn install
 ```
 **Start Development Server:** This command starts the development server, enabling you to preview changes live in your browser. By 
     default, the server runs at `http://localhost:3000/`.
 ```bash
    yarn run dev
  ```
**Key Features of** `**yarn run dev**`**:**
    
 *   Watches for file changes and updates the browser in real-time.      
 *   Provides detailed error messages during development.
 *   Optimized for fast feedback and iteration.

### 🛠️ Customization  

### Title and Favicon  

To change the site title, open the project in your editor and follow this screenshot:  

![image](./title.png)  

To update the favicon, replace the `favicon.ico` file in the `public/` directory as shown:  

![image](./icon.png)  

#### Home 1   

For **Home 1**, you can customize the following sections:  

- **Banner Image**: Modify `_banner.scss` located in `src/assets/scss/`.  
![image](./banner-imgs.png)  

- **Services Section**: Edit `Index.jsx` in `src/components/LatestServicesPart/`.  

  ![image](./service.png)  

- **Team Member Section**: Edit `Index.jsx` in `src/components/teamMemberPart/`.  

  ![image](./team-member.png)  

- **Latest News Section**: Edit `Index.jsx` in `src/components/latestNewsPart/`.  

  ![image](./news-blog.png)  

#### Home 2   

For **Home 2**, you can modify:  

- **Banner Image**: Edit `Index2.jsx` in `src/components/banner/`.  

  ![image](./banner-img-2.png)  

- **Services Section**: Edit `Index.jsx` in `src/components/whatWeDoPart/`.  

  ![image](./service-2.png)  

- **FAQ Section**: Edit `Index.jsx` in `src/components/answersPart/`.  

  ![image](./faq-home-2.png)  

- **Latest News Section**: Edit `Index.jsx` in `src/components/latestNewsPart/`.  

  ![image](./news-blog.png)  

#### Service   

On the **Service Page**, you can customize:  

- **Service Item Section**: Edit `Index.jsx` in `src/components/servicesItemPart/`.  

  ![image](./service-item.png)  

- **Service Plans Section**: Edit `ServicesPlansPart.jsx` in `src/components/servicesPart/`.  

  ![image](./service-plan.png)  

#### Case Study   

To edit the **Case Study Page**, update `index.jsx` located in `src/pages/case-study/`.  

![image](./case-stydy.png)  


####  Team

To edit the **Team Page**, update `Index.js` located in `src\pages\team`.
![image](./team-page.png)


####  blog-standard

- **Blog**: Edit `BlogSideBar.jsx` in `src\componets\blog\`.
  
![image](./blog.png)

- **Popular-feed**: Edit `BlogSideBar.jsx` in `src\componets\blog\`.
  
![image](./popular-feed.png)

- **Categories**: Edit `BlogSideBar.jsx` in `src\componets\blog\`.
  
![image](./categories.png)

- **Tags**: Edit `BlogSideBar.jsx` in `src\componets\blog\`.
  
![image](./tags.png)

####  blog-grid

- **Blogs**: Edit `blog-grid.jsx` in `src\pages\blog\`.
  
![image](./blogs.png)

####  Shop

- **Shop**: Edit `index.js` in `src\pages\shop\`.
  
![image](./products.png)

####  Product

- **Product**: Edit `index.js` in `src\pages\products\`.
  
![image](./product.png)


### 🏗️ Build for Production  

To build the project for production, use:  

```bash
yarn build
```

### 🧹 Clean Up  

To remove the `node_modules` folder and clean your project, run:  

```bash
yarn clean
```

### 📧 Support  

If you enjoy using our product, [Please Rate Us](https://themeforest.net/user/ducor). 😊  

#### Source and Credit

- [@fortawesome](https://fontawesome.com/)  
- [Animate.css](https://github.com/animate-css/animate.css)  
- [Axios](https://github.com/axios/axios)  
- [Bootstrap](https://getbootstrap.com/)  
- [React Bootstrap](https://react-bootstrap.github.io/)  
- [Desandro Matches Selector](https://github.com/desandro/matches-selector)  
- [React](https://reactjs.org/)  
- [React Icons](https://github.com/react-icons/react-icons)  
- [React Modal Video](https://github.com/appleple/react-modal-video)  
- [React Slick](https://github.com/akiran/react-slick)  
- [React Toastify](https://github.com/fkhadra/react-toastify)  
