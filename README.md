# amplify-react-graphql
Build a Full-Stack React Application

**Implementation**
The easiest way to create a React application is by using the command create-react-app. Install this package using the following command in your command prompt or terminal:

npx create-react-app amplifyapp
cd amplifyapp
npm start

**Initalize Github Repo**
In this step, you will create a GitHub repository and commit your code to the repository. You will need a GitHub account to complete this step—if you do not have an account, sign up here.

a. Create a new GitHub repo for your app.

b. Using create-react-app will automatically initialize the git repo and make an initial commit. If you are trying to deploy an existing React application where git has not been initialized, make sure to input the following commands before continuing:

git init
git add .
git commit -m "initial commit"
c. Push the application to the new GitHub repo by executing the following commands in your command line interface:

git remote add origin git@github.com:username/reponame.git
git branch -M main
git push -u origin main

**Log in to AWS management Console**
Open the AWS Management Console in a new browser window, so you can keep this step-by-step guide open. When the screen loads, enter your user name and password to get started. Then enter Amplify in the search bar and select AWS Amplify to open the service console.

**Deploy your app with AWS Amplify**
In this step, you will connect the GitHub repository you just created to the AWS Amplify service. This will enable you to build, deploy, and host your app on AWS.

a. In the AWS Amplify service console, select Get Started under Amplify Hosting.

b. Select GitHub as the repository service and select Continue.


c. Authenticate with GitHub and return to the Amplify console. Choose the repository and main branch you created earlier, then select Next.

d. Accept the default build settings and select Next.


e. Review the final details and choose Save and deploy.

f. AWS Amplify will now build your source code and deploy your app at https://...amplifyapp.com.

g. Once the build completes, select the thumbnail to see your web app up and running live. 

**Conclusion**
You have deployed a React application in the AWS Cloud by integrating with GitHub and using AWS Amplify. With AWS Amplify, you can continuously deploy your application in the cloud and host it on a globally available CDN.

Next, we will create a local version of the app to continue development and add new features.

