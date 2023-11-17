![Header](./assets/images/webp/11.webp)

hi, I'm Muhammad Avicena. I am delighted to present my latest project—a beautifully designed fashion shop that exudes simplicity and elegance. From its stylish layout to the carefully curated collection of clothing and accessories. With a focus on customer satisfaction, a knowledgeable staff, and a commitment to sustainability, this fashion shop offers a wide range of fashionable products while maintaining a high standard of quality and style. I hope you like it !

I am committed to staying up-to-date with industry trends and using the latest tools to develop innovative solutions that surpass expectations.
Interested to have collaboration ? Find me on:d

## MY SOCIAL MEDIA

<h3 align="left"><a href="https://www.linkedin.com/in/muhammad-avicena/"><img src="./assets/images/svg/linkedin.svg" width="30px" height="30px" /> @raiwirawan</a></h3>

<h3 align="left"><a href="https://www.instagram.com/raiwirawann/"><img src="./assets/images/svg/instagram.svg" width="30px" height="30px" /> @raiwirawann</a></h3>

## STRUCTURE 📰

### MAIN PAGE

- MAIN
  - Video Background
  - Introduction

### PORTFOLIO PAGE

- Header
  - Navbar
- Main
  - Porfolio section 1
  - Porfolio section 2
  - Porfolio section 3
  - Contact Us section
- Footer

## INGREDIENTS THAT I'M USING 📜

- HTML
- CSS
- JavaScript
- Internal Source
  - Icon
  - Image

## HOW TO SET UP 📰

You will need a github account to clone this repository, make sure you're connected to github.

1. Clone this repository

```
git clone https://github.com/revou-fsse-3/milestone-1-raiwirawan.git
```

2. Create a new branch named "develop", in this repository we would like to develop the website with personal information.

```
git branch -b "develop"
```

3. Once it's created, checkout to a new branch

```
git checkout -b "develop"
```

4. Develop & modify the website with your personal information, once it's done you will need to push it.

```
git add .
git commit -m "update message" // make sure to give details commit message to get better logs
git push origin develop
```

5. Once you're done, you can merge into main/master branch for production build.

```
git checkout main
git pull origin main // pull the latest version before commit merge
git merge develop // if there are any conflicts, you should resolve them manually
git commit -m "Merge develop into main"
git push origin main
```

## DEPLOYMENT ⚙️

The project has been successfully deployed using Netlify. You can access the production version of the website by following this link: [https://luxury-shop.avicena.dev](https://luxury-shop.avicena.dev) or [this link](https://www.luxury-shop.avicena.dev).

### Deployment status :

[![Netlify Status](https://api.netlify.com/api/v1/badges/fd84e054-64dc-46b4-967d-198778bd6c8a/deploy-status)](https://app.netlify.com/sites/avicena-week5/deploys)

1. Connect your account to Netlify !

The first step to deploy in Netlify is creating a new account or use existing account. As a beginner progammer, I would prefer using GitHub account instead.

After you successfully login, you will be redirected to dashboard of Netlify app. In this scenario, you will need to import your existing project from github to netlify. Add new site -> Import existing project -> Connect via GitHub

![Alt text](readme-images/2.png)

2. Auto Deploy with Netlify !

One of the benefit using your GitHub account connected to Netlify is that you don't have to worry about re-deploying your project manually, once there are changes that have been pushed in your repository, it will automatically re-deployed by Netlify within second.

![Alt text](readme-images/3.png)

3. Domain Registrar with NiagaHoster & Cloudfire !

Go to [https://niagahoster.co.id](https://niagahoster.co.id) and log in or create a new account. Check available domain that you wanted and make it yours.

After that, go to [https://dash.cloudflare.com/](https://dash.cloudflare.com/) and log in or create a new account. You will be redirected to dashboard, add the domain that you have bought previously.

![Alt text](readme-images/4.png)

4. Modify your project with favorite customize domain !

You're on the final step to bringing live your project with custom domain. Go to dashboard Cloudfire -> DNS Records -> CloudFire NameServer. You will see the information of Nameserver that is given to you.

```
Type  Value
NS    andronicus.ns.cloudflare.com
NS    paislee.ns.cloudflare.com
```

Copy these nameserver and jump into dashboard overview of NiagaHoster. You should replace it with NameServer of CloudFire.

After that, go to Netlify Dashboard -> open your project -> Custom domain -> Add domain that you have set previously. In thise case, you will see they're awaiting for external DNS. You will get some information such as IPv4 and domain name that you should input it to CloudFire.

Use subdomain :

```
Type  Value           Content Name
CNAME luxury-shop     avicena-week5.netlify.com
```

Final step, go to Dashboard Cloudfire -> DNS Records -> Add record domain -> set them accordingly.

![Alt text](readme-images/5.png)

5. Congratulations, You're done !

You should wait within 1x24 hours to let the NiagaHoster and Cloudfire setting up the DNS, it could be faster or slower depending on the provider internet that you're using.

Feel free to explore the website and try out the different features. I appreciate any feedback and suggestions to further improve the user experience.

Happy browsing!

## PREVIEW : https://wiraonetech.site
