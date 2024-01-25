# profile-pages
why next.js:
Next.js is well known for its file system-based routing
https://blog.logrocket.com/next-js-13-app-router/
my profile page/s in next.js
1. installing next.js in my profile-pages project. Creating a file called: nextjs-profile.
This is the options i chosen when installing/creating this next.js project:

npx create-next-app@latest nextjs-profile       
Need to install the following packages:
create-next-app@14.1.0
Ok to proceed? (y) y
√ Would you like to use TypeScript? ... No / Yes
√ Would you like to use ESLint? ... No / Yes
√ Would you like to use Tailwind CSS? ... No / Yes
√ Would you like to use `src/` directory? ... No / Yes
√ Would you like to use App Router? (recommended) ... No / Yes
√ Would you like to customize the default import alias (@/*)? ... No / Yes
Creating a new Next.js app in C:\Users\kveta\Documents\CODing\PORTFOLIO page\profile-pages\nextjs-profile.
typescript-NO, ESLint - NO, TailwindCSS - NO, src/directory - NO, App Router - YES, import alias - NO. 
----------------------------
Initializing project with template: app 

Installing dependencies:
- react
- react-dom
- next

added 20 packages, and audited 21 packages in 18s

3 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities

Success! Created nextjs-profile at C:\Users\kveta\Documents\CODing\PORTFOLIO page\profile-pages\nextjs-profile

PS C:\Users\kveta\Documents\CODing\PORTFOLIO page\profile-pages> ^C
PS C:\Users\kveta\Documents\CODing\PORTFOLIO page\profile-pages> cd nextjs-profile
PS C:\Users\kveta\Documents\CODing\PORTFOLIO page\profile-pages\nextjs-profile> 
-------------------------------------------------------------------
2. npm run dev command run in terminal
running npm run dev was succesfull:
PS C:\Users\kveta\Documents\CODing\PORTFOLIO page\profile-pages\nextjs-profile> npm run dev

> nextjs-profile@0.1.0 dev
> next dev

   ▲ Next.js 14.1.0
   - Local:        http://localhost:3000

 ✓ Ready in 8s
 --------------------------------------------
 3. Saved everything using terminal (Commnad line), git add. , git commit -m"....", git push while being in side my nextjs-profile folder. 
 warning: in the working copy of 'nextjs-profile/.gitignore', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'nextjs-profile/README.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'nextjs-profile/app/globals.css', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'nextjs-profile/app/layout.js', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'nextjs-profile/app/page.js', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'nextjs-profile/app/page.module.css', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'nextjs-profile/jsconfig.json', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'nextjs-profile/next.config.mjs', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'nextjs-profile/package-lock.json', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'nextjs-profile/package.json', LF will be replaced by CRLF the next time Git touches it
PS C:\Users\kveta\Documents\CODing\PORTFOLIO page\profile-pages\nextjs-profile> git commit -m"setting up rep with next.js instalation"
[main b457d6f] setting up rep with next.js instalation
 13 files changed, 939 insertions(+)
 create mode 100644 nextjs-profile/.gitignore
 create mode 100644 nextjs-profile/README.md
 create mode 100644 nextjs-profile/app/favicon.ico
 create mode 100644 nextjs-profile/app/globals.css
 create mode 100644 nextjs-profile/app/layout.js
 create mode 100644 nextjs-profile/app/page.js
 create mode 100644 nextjs-profile/app/page.module.css
 create mode 100644 nextjs-profile/jsconfig.json
 create mode 100644 nextjs-profile/next.config.mjs
 create mode 100644 nextjs-profile/package-lock.json
 create mode 100644 nextjs-profile/package.json
 create mode 100644 nextjs-profile/public/next.svg
 create mode 100644 nextjs-profile/public/vercel.svg
PS C:\Users\kveta\Documents\CODing\PORTFOLIO page\profile-pages\nextjs-profile> git push
Enumerating objects: 19, done.
Counting objects: 100% (19/19), done.
Delta compression using up to 8 threads
Compressing objects: 100% (18/18), done.
Writing objects: 100% (18/18), 18.52 KiB | 2.65 MiB/s, done.
ges\nextjs-profile> cd ..
PS C:\Users\kveta\Documents\CODing\PORTFOLIO page\profile-pages> git add .
PS C:\Users\kveta\Documents\CODing\PORTFOLIO page\profile-pages> git commit -m"saving README file"
[main 153b534] saving README file
 1 file changed, 50 insertions(+)
PS C:\Users\kveta\Documents\CODing\PORTFOLIO page\profile-pages> git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.10 KiB | 1.10 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/selfcoder-gazell/profile-pages.git
   b457d6f..153b534  main -> main
PS C:\Users\kveta\Documents\CODing\PORTFOLIO page\profile-pages>
--------------------------------
4. using this link to learn about next.js and the App Router course
https://nextjs.org/learn I am now leaving this repo and going to open another one using the link i just inserted above - to help me understand the principles of next.js (using typescript and perhaps even prisma because prisma which automatically generates types based on my database schema)
5. Deploying on Vercel now; After i changed one word in the app/page.js file

