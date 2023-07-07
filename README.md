# Deploy Your Website with Netlify, GitHub, and a Custom Domain

Hello, friend! 👋 This is your step-by-step guide to showcase your amazing website to the world using Netlify, GitHub, and your very own custom domain. Let's do this!


## FINAL PRODUCT: [Next Dot Jobs](http://nextdotjobs.site)
<img width="1410" alt="Screen Shot 2023-07-07 at 23 52 07" src="https://github.com/RevoU-FSSE-2/week-4-audiprevio/assets/126348614/8637a735-bbf0-4c4e-bea1-fd20f7354429">
<br>
<img width="1330" alt="Screen Shot 2023-07-07 at 23 52 29" src="https://github.com/RevoU-FSSE-2/week-4-audiprevio/assets/126348614/491b5917-46a1-4b6b-81f3-b1deae2a558b">







<br>



## 🚀 Getting Started

### Step 1: Sign Up on Netlify

Go to the [Netlify website](https://www.netlify.com/) and sign up for a free account.

### Step 2: Connect Your GitHub Project to Netlify
<br>
1. Log into Netlify and click on "New site from Git"<br>
<br>
<img width="948" alt="Screen Shot 2023-07-07 at 23 27 18" src="https://github.com/RevoU-FSSE-2/week-4-audiprevio/assets/126348614/bcc7a697-69a1-4363-9b80-e54aaeb11482"><br>
<br>
<br>
2. Select GitHub as the Source<br>
<br>
<img width="948" alt="Screen Shot 2023-07-07 at 23 28 26" src="https://github.com/RevoU-FSSE-2/week-4-audiprevio/assets/126348614/2061ac82-bb45-46cd-91c9-e43ec3b196d1"><br>
<br>
<br>
3. Deploy your website from the Main Branch<br>
<br>
<img width="947" alt="Screen Shot 2023-07-07 at 23 29 05" src="https://github.com/RevoU-FSSE-2/week-4-audiprevio/assets/126348614/b0743f83-09b7-4c08-a7da-58e3e0ccfdd4"><br>
<br>
<br>
4. Ta-da your website has been deployed!<br>
<br>
<img width="949" alt="Screen Shot 2023-07-07 at 23 29 51" src="https://github.com/RevoU-FSSE-2/week-4-audiprevio/assets/126348614/74b45e81-b265-47fc-87f7-29f07246ff04"><br>
<br>
<br>
5. You can change the name of the website now, or not. Since we are going to use custom domain at the end of the day anyway<br>
<br>
<br>

### Step 3: Set Up Automatic Deployments

With Netlify and GitHub connected, your site on Netlify will automatically update whenever you push changes to your GitHub repository. But this time we want to do CI/CD using Branch and Pull Request.

1. Git clone your respository that you use to deploy your site on Netlify, You can use Terminal, 3rd Party CLI, or VS Code. In this case we use Hyper.is<br>
<br>
<img width="807" alt="Screen Shot 2023-07-07 at 23 37 45" src="https://github.com/RevoU-FSSE-2/week-4-audiprevio/assets/126348614/467f3851-10ef-4dcf-80b8-84187684aeac"><br>
<br>
<br>

2. Add the files that you want to have into the folder above 👆🏻 or you can edit the codes directly in VS Code then save<br>
<br>

3. Push the file into your branch

Once you have made the changes you want locally, the next step is to push those changes to your remote branch on GitHub. Below are the steps to do that.

First, navigate to your project directory using the terminal.

`cd your-project-directory`

Use git add to stage your changes. This tells Git that you want to include the updates from these files in the next commit. To add all the files in the directory, use:

`git add .`

Now you commit the changes. A commit is like a snapshot of your code at this point in time. Include a descriptive message with your commit summarizing what changes were made.

`git commit -m "Your descriptive message here"`

Now you're ready to send your changes to GitHub! If you're working on a branch named IMPROVEMENT1, push your changes like so:

`git push origin UI-UX-improvement-1.0`


After running this command, your changes are now in the IMPROVEMENT1 branch on GitHub.


Remember, it's important to make sure that your local branch and your remote branch are in sync before you start making changes. Use git pull origin BRANCHNAME to update your local branch with the latest changes from the remote before you start making your own changes.


### Step 3A: GIT PULL REQUEST

1. Open Git and Find Request for Pull Request and Click. This Screen should appear. Create the Pull Request and write relevant message
<img width="942" alt="Screen Shot 2023-07-07 at 23 45 59" src="https://github.com/RevoU-FSSE-2/week-4-audiprevio/assets/126348614/feaf34b4-7f83-4707-82e4-4effc1ba3bf8">


2. Approve the Pull Request
<img width="807" alt="Screen Shot 2023-07-07 at 23 46 12" src="https://github.com/RevoU-FSSE-2/week-4-audiprevio/assets/126348614/6f7880d8-0405-43e9-af90-9bb1c54b1d98">

3. Check if the Pull Request is successful
<img width="940" alt="Screen Shot 2023-07-07 at 23 46 25" src="https://github.com/RevoU-FSSE-2/week-4-audiprevio/assets/126348614/ff1af2bb-41b8-419d-b6f2-4222a9fb08e5">

### Step 4: Buy Custom Domain
Different sites have different pathway to buy a domain. Most of the flows are the same though. This is how Hostinger does it:
<img width="945" alt="Screen Shot 2023-07-07 at 23 48 55" src="https://github.com/RevoU-FSSE-2/week-4-audiprevio/assets/126348614/e49f2c79-bde6-4054-8c70-3bff8a03a511">



<img width="937" alt="Screen Shot 2023-07-07 at 23 49 07" src="https://github.com/RevoU-FSSE-2/week-4-audiprevio/assets/126348614/15e02b43-d20a-4445-b93f-106dd0b9127c">



<img width="944" alt="Screen Shot 2023-07-07 at 23 49 20" src="https://github.com/RevoU-FSSE-2/week-4-audiprevio/assets/126348614/e030a71b-df17-4bb2-96cc-8f409ef2b774">



<img width="948" alt="Screen Shot 2023-07-07 at 23 49 32" src="https://github.com/RevoU-FSSE-2/week-4-audiprevio/assets/126348614/ea25c541-862a-4510-acdb-86698bb7378e">



### Step 5: Connect Your Custom Domain

1. In your Netlify dashboard, go to "Domain settings" for your website.
2. Click "Add custom domain" and enter your domain name.
<img width="941" alt="Screen Shot 2023-07-07 at 23 49 43" src="https://github.com/RevoU-FSSE-2/week-4-audiprevio/assets/126348614/9b0b9d95-c75e-40b0-bf04-a7236f25f881">

### Step 6: Update Your Domain's DNS Settings with CloudFlare

1. Go to your domain registrar's dashboard and follow this CloudFlare instruction
<img width="940" alt="Screen Shot 2023-07-07 at 23 50 04" src="https://github.com/RevoU-FSSE-2/week-4-audiprevio/assets/126348614/345b1229-f2eb-4c36-9bab-ec52ac205b86">

2. Update the DNS settings to point to Netlify's servers (Netlify will provide the necessary details).
<img width="946" alt="Screen Shot 2023-07-07 at 23 50 35" src="https://github.com/RevoU-FSSE-2/week-4-audiprevio/assets/126348614/05056aac-d485-4190-bf7d-22d3f56e1483">



And voila! Your website is now live on the internet at your custom domain and will automatically update with changes from your GitHub repository. Enjoy!

## 📚 Further Reading

- [Netlify Documentation](https://docs.netlify.com/)
- [GitHub Documentation](https://docs.github.com/en)

Have fun deploying! 🎉
