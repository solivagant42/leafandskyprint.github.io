Leaf & Skyprint
A digital archive for an amateur naturalist's solitary walks in nature, featuring observations, sketches, and reflections. The site includes a full-width header image, sticky navigation, a gallery, occasions section, and a commenting system.
Features

Monochromatic Design: Uses white (#FFFFFF), black (#000000), and dark slate gray (#2F4F4F) for a soothing aesthetic.
Parallax Header: Full-width nature image with a parallax effect.
Sticky Navigation: Easy access to Home, Archive, About, Gallery, Occasions, and Contact sections.
Gallery: Grid-based display of nature photos with hover effects.
Occasions: Card-based section for events like birdwatching or workshops.
Commenting: Formspree-powered comment form for user feedback via email.

Setup Instructions

Create a GitHub Repository:

Create a new repository on GitHub (e.g., leaf-and-skyprint).
Clone it to your local machine or use the GitHub web interface to upload files.


Upload Files:

Upload index.html to the root directory.
Upload styles.css to the assets/css/ folder (create the folder if needed).
Upload README.md and .gitignore to the root directory.


Set Up Formspree for Comments:

Sign up at https://formspree.io and create a form.
Copy your form ID and replace your-form-id in the index.html form's action attribute (https://formspree.io/f/your-form-id).
Comments will be sent to the email associated with your Formspree account.


Enable GitHub Pages:

Go to your repository's Settings > Pages.
Set the source to the main branch and root directory.
Save, and your site will be live at https://<username>.github.io/<repository-name>.


Customize Content:

Replace the header image URL in index.html with your own (upload images to assets/images/ or use an external host like ImgBB).
Update text in the "Recent Walks," "Latest Observations," "Occasions," and "Contact" sections.
Add more gallery images or occasion cards by copying the respective HTML blocks.



Optional Enhancements

Add Images: Create an assets/images/ folder and upload your nature photos, updating URLs in index.html.

Fonts: Add Google Fonts (e.g., Roboto) by including in index.html:
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">

Update styles.css: font-family: 'Roboto', sans-serif;.

Jekyll for Dynamic Posts: To use Jekyll for blog posts, follow GitHub’s documentation (https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll).


Resources

HTML/CSS Tutorials: https://www.w3schools.com
Formspree: https://formspree.io
GitHub Pages: https://docs.github.com/en/pages

