# [My personal website](https://www.nahuelcosta.com/)

This project contains the source code of my personal website, developed with Hugo (using the [Hugo Academic Resumé Template](https://academic-demo.netlify.app/)) and deployed using [Netlify](https://www.netlify.com/).

The following sections explain in detail how this website was developed and deployed 🚀.


# 1. Choose a template, create the Github repository and deploy it

[Wowchemy](https://wowchemy.com/templates/) has some pretty cool website templates. Choose one and press "Start with _template_name_". After that you will be prompted to a new page, press "Connect to Github" and Netlify will automatically create a new repository on your account and clone the template chosen. [Here](https://wowchemy.com/docs/getting-started/hugo-github-quickstart/) you can see the process step by step.

**Alternatively**, you can do this on your own. Just create a new repository and clone the template into it. You can choose to deploy the site either with [Github pages](https://pages.github.com/) or [Netlify](https://www.netlify.com/) (both are great options). 
- If you choose Github: the name of your repository must be as follows: your-account-name.github.io. That´s it, just open your-account-name.github.io and the template will be deployed.
- If you choose Netlify: you have to connect Netlify to your Github account and in "Site settings" connect your site to your Github repo.


# 2. Modify the website content and preview it locally
[Here](https://wowchemy.com/docs/getting-started/install-hugo-extended/) you can check how to do it. I did it in windows, the steps are pretty straightforward:

- In Powershell download the scoop package manager:

      Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
      Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
  
- Download the necessary packages to run the site:

      scoop install git go hugo-extended nodejs
  
- Go to your repository folder and execute Hugo:

      hugo server

Once you have done this you can normally access the website locally at http://localhost:port/ where "port" depends on whether you have any other services running locally. After running "hugo server" you can check the port where the site is being displayed.

Now you can modify the contents directly from your repo and all the changes made will be dynamically updated in the browser. However, for some changes you might need to force refresh your web browser to clear cached content such as images.


# 3. Commit and push the source code
Now you can see all the updates you made locally on your website!
