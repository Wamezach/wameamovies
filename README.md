


STEP 1: How to Create account and get Api Key in TMDB(The Movie Database)
1.) Create account here: TMDB Signup
2.) Upon Signup, an Activation link will be sent to your email.
3.) After Activation done. Click to your Profile(top right) and select "Api Subscription"
4.) Click "Access your API key details here." to get your own Api Key.
5.) Save your Api Key, we will use it to fetch movie & series details.


STEP 2: How to create account and host your Website in GitHub
1.) First is to download website files here: Files here!
2.) Next is to extract rar file
3.) Create account here: Github Signup
4.) Upon Signup, Go to Dashboard.
5.) Click "Create repository"
6.) Fill up "Repository name*" with whatever name you want (example flixmovies)
7.) Then Click "Create Repository".
8.) Find and click "uploading an existing file".
9.) Go to your extracted file and drag the folder to upload
10.) After uploading, click "Commit Changes"
11.) Wait files to be uploaded atleast 5mins and your done.


STEP 3: How to deploy website to Cloudflare using GitHub
1.) Create account here: Cloudflare Signup
2.) After signing up, Click "+" sign(top right)
3.) Select and click "Pages"
4.) Select "Connect to Git"
5.) Select "Connect to GitHub"
6.) Next is Click "Install & Authorize"
7.) You will be directed to GitHub, below Repository access, select "Only select repositories", then select your created repository (example flixmovies)
8.) Click "Save"
9.) You will be redirected back to Cloudflare, Under "Select a repository", select your created repository (example flixmovies) then click "Begin setup"
10.) You will be transferred to "Set up builds and deployments", under "Build output directory", input the folder name from GitHub (my-website)
11.) Click "Save and Deploy"
12.) You will be transferred to "Building and deploying", Wait for the website to be deployed within a minute. If you see "Success! Your project is deployed to Region: Earth". You can now preview your project. click the link. (example movieflix.pages.dev)
13.) Upon clicking the link, wait 5 mins for the cloudflare to be totally deploying your website. Enjoy!


STEP 4: Use your own TMB API Key
1.) Go to your github account, select your own created repository (example flixmovies)
2.) Click "my-website" folder, open "js" folder and click "home.js"
3.) Click "Edit this file(pencil style)" to edit your home.js
4.) Find this line: const API_KEY = 'a1e72fd93ed59f56e6332813bxxxxxxx'; change a1e72fd93ed59f56e6332813bxxxxxxx to your own API KEY which you get from TMDB.
5.) Upon changing, Click "Commit Changes" to save.
