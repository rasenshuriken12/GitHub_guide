# GitHub_guide

<br> ![Author: Deviprasad Shetty](https://img.shields.io/badge/Author-💫_Deviprasad%20Shetty-000000?style=for-the-badge&labelColor=white)
<br> 

| [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5?style=for-the-badge&logo=LinkedIn&logoColor=white)](https://linkedin.com/in/deviprasad-shetty-4bba49313) | [![My_Portfolio](https://img.shields.io/badge/My_Portfolio-indigo?style=for-the-badge&logo=firefox&logoColor=white)](https://yourwebsite.com/) | [![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=GitHub&logoColor=white)](https://github.com/DeviprasadShetty9833/DeviprasadShetty9833)  |
|---|---|---|

---

# Hosting a website on GitHub using GitHub Pages:

```html
• Create a New Repository: 
	• Navigate to your GitHub dashboard and click the "New" button to create a new repository. 
	• For a personal or organization site: Name the repository exactly your-username.github.io (replace your-username with your actual GitHub username) or your-organization.github.io. 
	• For a project site: Name the repository after your project (e.g., my-project). 
	• Ensure the repository is set to Public. 
```

```html
• Upload Your Website Files: 
	• Clone the repository to your local machine using Git, or upload files directly through the GitHub web interface. 
	• Place all your website files (HTML, CSS, JavaScript, images, etc.) in the root directory of this repository. 
	• Ensure there is an index.html file, as this will be the default landing page. 

• Commit and Push Changes: 
	• If using Git locally, commit your changes and push them to the GitHub repository. 
	• If uploading via the web interface, commit the changes after uploading the files. 
```

```html
• Configure GitHub Pages: 
	• Navigate to your repository on GitHub and click on the Settings tab. 
	• In the left sidebar, click on Pages. 
	• Under "Build and deployment," ensure the "Source" is set to "Deploy from a branch." 
	• Under "Branch," select the branch containing your website files (typically main or master) and choose the root directory (/). 
	• Click Save. 
```

```html
• Access Your Website: 
	- GitHub Pages will now build and deploy your website. This process may take a few minutes. 
	- Once deployed, the URL for your website will be displayed in the "Pages" section of your repository settings. 
	- For a personal or organization site, the URL will be your-username.github.io. 
	- For a project site, the URL will be your-username.github.io/repository-name. 
```

Your website is now live and accessible via the provided URL. You can also configure a custom domain if desired within the GitHub Pages settings. 

### 🔗 Links & References:
- [1] https://www.youtube.com/watch?v=e5AwNU3Y2es
- [2] https://www.youtube.com/watch?v=ZwG9jwit2Ho
- [3] https://www.geeksforgeeks.org/git/how-to-host-a-website-on-github-for-free/

---

# Host your own quote API on GitHub (free) and use the same image style

You will create a Fork of the original project → replace its quotes with your 2 quotes → deploy → then use your custom URL.


✅ Step-by-step — Only 2 minutes

Step 1 — Fork the repository

Go to:

👉 https://github.com/PiyushSuthar/github-readme-quotes

Click Fork.


Step 2 — Find the quotes file

In your fork, open:

src/quotes.json

Replace everything with ONLY your 2 quotes:

[
  {
    "text": "The quieter you become, the more you can hear.",
    "author": "Unknown"
  },
  {
    "text": "Strength grows in the moments when you think you can’t go on.",
    "author": "Unknown"
  }
]

Commit changes.


Step 3 — Deploy using Vercel

Go to:

👉 https://vercel.com/new

Select your forked repository
→ Deploy.

Vercel will give you a custom URL like:

https://your-app-name.vercel.app


Step 4 — Use your custom quote generator in your README

Replace the original with your Vercel URL:

![Quote](https://your-app-name.vercel.app/api?type=horizontal&theme=radical&border=true)

Now it will show only your two quotes, rotating forever.


🎉 Done!

Your GitHub README will now display your own 2 quotes exactly like the original generator — same style, same animation, same features.

# Releasing Versions

```

```
