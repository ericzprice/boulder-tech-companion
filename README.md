Boulder Tech Companion — website
A single-page site for the tech-help-for-seniors business, ready to publish for free with GitHub Pages.
What is in this folder
-	index.html — the whole site (one file, no build step)
Before you publish
Phone number and email are already filled in (720-340-8441 and ericzprice@gmail.com). Double check these are correct, and swap the email for a professional eric@bouldertechcompanion.com address once you've registered the domain and set up email forwarding.

The testimonial links (GigSalad, The Bash, LinkedIn) are also already in place — verify they still point where you want them if you update your profiles later.
Publish it with GitHub Pages, step by step
1.	Create a free GitHub account at github.com if you do not already have one.
2.	Click the plus icon in the top right, then New repository.
3.	Name it something like boulder-tech-companion. Set it to Public. Do not add a README (you already have one).
4.	On the new repository page, click uploading an existing file, then drag in index.html and README.md from this folder. Commit the changes.
5.	Go to the repository Settings tab, then Pages in the left sidebar.
6.	Under Build and deployment, set Source to Deploy from a branch. Set Branch to main and folder to / (root). Save.
7.	GitHub will give you a live URL after a minute or two, usually: https://YOUR-USERNAME.github.io/boulder-tech-companion/
Using your own domain later
If you buy a domain (for example bouldertechcompanion.com):

1.	At your domain registrar, add a CNAME record pointing to YOUR-USERNAME.github.io
2.	In the repository Settings > Pages > Custom domain, enter your domain and save.
3.	GitHub will add a CNAME file to the repo automatically and issue an HTTPS certificate within a few minutes to a few hours.
Making changes later
Any time you want to update text, prices, or your phone number: edit index.html directly in the GitHub web interface (click the pencil icon on the file), or use Claude Code / GitHub Desktop if you want a smoother local editing workflow. Every save automatically republishes the live site within a minute.

