# **TechMentor**
I decided to develop an educational website where new but also established developers can find useful courses and tutorials for the latest trends of software development.

## **Development Steps**

### 1. Preliminary Installations

* Hugo
* Go language
* Git VCS client
* PostCSS

### 2. Launching a New Hugo Site

For the creaton of the site I used the **Docsy**, a Hugo theme module for technical documentation sites, providing easy site navigation and structure. Detailed theme instructions are accesible in the [Docsy](https://www.docsy.dev/docs/)

### 3. Customising the site

To become familiar with the Hugo site I customised it by altering several parts. For example, I changed the cover image, the navigation bar, background colours and icons. I also kept three main pages from the original template: home, about and blog.

## 4. Hosting the Site
The site is hosting at the [GitHub](https://github.com/ilianafaka/hugo.git) repository and it can be viewed on Netlify at  https://hugotraining.netlify.app

### 5. Difficulties

* It is not clear for me how the style applied to the elements by the use of bootstrap. In some cases I used in-line style instead using the external file.
* I had difficulties adding a contact page (static html) to the menu. 
* Couldn't find how to remove the right column from the blog page.

### 6. Further tasks

* Learn about each file's purpose.
* Understand the site's styles in depth.
* Add more pages align to the company's needs.
* Improve search engine ranking by implementing best practises.
* Personalise the site further.

## **Answers to open questions**

### 1. Website optimisation for search engines
To optimize my website for search engines I started by setting up a google search console and connecting it with the site. I should also implement the following steps:

* Index each page individually.
* Submit a sitemap to Google Search Console.
* Ensure all content has appropriate metadata, as described in [Hugo's documentation](https://gohugo.io/content-management/front-matter/).
* Review [Google Search documentation](https://developers.google.com/search/docs) for further SEO improvements like:
   * Following URL structure best practices.
   * Compressing images and add descriptive alt text.
   * Adopting internal linking to direct users to related content within the site.
* Implement analytics to monitor site performance and user interactions.

### 2. Website optimisation for search engines
Since Hugo is a static site generator, it doesn't have a backend to handle form submissions. I will use the Netlify, that provides a simple solution for managing forms. 