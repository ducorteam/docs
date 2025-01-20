#  Welcome To Omnivus - IT solutions, digital services, and business agencies theme 
Firstly, a huge thanks for purchasing this theme, your support is truly appreciated!

This document covers the installation and use of this theme and often reveals answers to common problems and issues - read this document thoroughly if you are experiencing any difficulties. If you have any questions that are beyond the scope of this document, feel free to email at [suppot@ducor.net](mailto:__EMAIL__) Thank you so much!
## Basic
1.  After unzip the download pack, you'll found a Template Folder with all the files.
2.  You can view this Template in any browser, you can display or edit the Template without an internet connection.(May not wotrk fonts and google map).
3.  This section that will not work is the Contact Section
- **Omnivus Template**: An installable Next.js template zip file.
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
   cd omnivus-nextjs
   ``` 
3.  Run the following commands to set up the project:
  Yarn is an established open-source package manager used to manage dependencies in JavaScript projects. It assists with the process of 
  installing, updating, configuring, and removing packages dependencies, eventually helping you reach your objectives faster with fewer 
  distractions.
 > **Note**: Unlike most other package managers, which typically defer to npm for non-install-related commands, Yarn reimplements all 
 commands, so as to have full control over our developer experience and stability. 
 **Install Dependencies:**
 ```bash
  yarn
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
#### Change Site Title 
To change the site title, open the project in your editor and edit the `next.config.js` file or use the `Head` component in the pages where needed:
##### Method 1: Global Title
 Modify the Site Title in `next.config.js`
1. Open the project in your editor.
2. Edit the `next.config.js` file.
3. Update the `title` property inside the `head` configuration.
Example:
```js
// next.config.js
module.exports = {
  head: {
    title: 'My Awesome Site',  // Set the global title here
    meta: [
      {
        name: 'description',
        content: 'This is an awesome Next.js site!'  // Optional description
      },
    ],
  },
};
```
##### Method 2: Individual Pages
If you want to set a specific title for individual pages, you can use the `Head` component from `next/head`:
1. Open or create the page where you want to change the title (e.g., `pages/index.js`).
2. Import the `Head` component from `next/head`.
3. Add a `<title>` tag inside the `Head` component for each page.
Example:
```jsx
// pages/index.js
import Head from 'next/head';

export default function Home() {
  return (
    <div>
      <Head>
        <title>Home - My Awesome Site</title>  {/* Page-specific title */}
        <meta name="description" content="Welcome to the homepage of My Awesome Site!" />
      </Head>
      <h1>Welcome to My Awesome Site!</h1>
    </div>
  );
}
```
#### Update the Favicon
To update the favicon for your site, follow these steps:
1. Replace the `favicon.ico` file in the `public/` directory with your desired favicon file.
2. Next.js automatically serves the favicon from the `public/` directory, and it will be used across all pages.
File Structure:
```plaintext
public/
  favicon.ico  // Your updated favicon file
```
####  Home 1 
For **Home 1**, you can customize the following sections:
- **Banner Image**: Modify `_banner.scss` located in `public\assets\scss\`.
  ![image](./banner-imgs.png)
- **Services Section**: Edit `Index.jsx` in `components/LatestServicesPart/`.
  ![image](./service.png)
- **Team Member Section**: Edit `Index.jsx` in `components/teamMemberPart/`.
  ![image](./team-member.png)

- **Latest News Section**: Edit `Index.jsx` in `components/latestNewsPart/`.
  ![image](./news-blog.png)

####  Home 2 
For **Home 2**, you can modify:
- **Banner Image**: Edit `Index2.jsx` in `components/banner/`.
  ![image](./banner-img-2.png)
- **Services Section**: Edit `Index.jsx` in `components/whatWeDoPart/`.
  ![image](./service-2.png)
- **FAQ Section**: Edit `Index.jsx` in `components/answersPart/`.
  ![image](./faq-home-2.png)
- **Latest News Section**: Edit `Index.jsx` in `components/latestNewsPart/`.
  ![image](./news-blog.png)

####  Service 
On the **Service Page**, you can customize:
- **Service Item Section**: Edit `Index.jsx` in `components/servicesItemPart/`.
  ![image](./service-item.png)
- **Service Plans Section**: Edit `ServicesPlansPart.jsx` in `components/servicesPart/`.
  ![image](./service-plan.png)

####  Case Study 
To edit the **Case Study Page**, update `page.js` located in `src\app\(pages)\(others)\case-study/`.
![image](./case-stydy.png)

####  Team
To edit the **Team Page**, update `page.js` located in `src\app\(pages)\(others)\team`.
![image](./team-page.png)

####  blog-standard
- **Blog**: Edit `BlogSideBar.jsx` in `src\app\componets\blog\`. 
![image](./blog.png)
- **Popular-feed**: Edit `BlogSideBar.jsx` in `src\app\componets\blog\`. 
![image](./popular-feed.png)
- **Categories**: Edit `BlogSideBar.jsx` in `src\app\componets\blog\`.  
![image](./categories.png)
- **Tags**: Edit `BlogSideBar.jsx` in `src\app\componets\blog\`. 
![image](./tags.png)

####  blog-grid
- **Blogs**: Edit `page.js` in `src\app\(pages)\(others)\(blog)\blog-grid\`.
![image](./blogs.png)

####  Shop
- **Shop**: Edit `page.js` in `src\app\(pages)\(others)\shop\`. 
![image](./products.png)

####  Product
- **Product**: Edit `page.js` in `src\app\(pages)\(others)\products\`.  
![image](./product.png)

### 🏗️ Build for Production
To prepare the project for production, you need to build it. This process optimizes the code, bundles the assets, and prepares everything for deployment. Use the following command:
```bash
yarn run build
```
 #### Deployment
After running yarn run build, deploy the contents of the `/dist` folder to any static hosting provider, such as:
*   [Netlify](https://www.netlify.com/)
*   [Vercel](https://vercel.com/)
*   [AWS S3](https://aws.amazon.com/s3/)
*   [GitHub Pages](https://pages.github.com/)
*   
#### Source and Credit
- [@fortawesome](https://fontawesome.com/)  
- [Animate.css](https://github.com/animate-css/animate.css)  
- [Axios](https://github.com/axios/axios)  
- [Bootstrap](https://getbootstrap.com/)  
- [React Bootstrap](https://react-bootstrap.github.io/)  
- [Desandro Matches Selector](https://github.com/desandro/matches-selector)  
- [Next.js](https://nextjs.org/)  
- [React](https://reactjs.org/)  
- [React Icons](https://github.com/react-icons/react-icons)  
- [React Modal Video](https://github.com/appleple/react-modal-video)  
- [React Slick](https://github.com/akiran/react-slick)  
- [React Toastify](https://github.com/fkhadra/react-toastify) 
### 📧 Support  
  
Thank you for choosing Fixed-Piug-React! We hope this theme meets your expectations and enhances your project. If you need further assistance, don't hesitate to reach out to us. Happy coding! [Please Rate Us](https://themeforest.net/user/ducor). 😊 
