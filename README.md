In this project, the class is going to break into groups and build an "About Me" website. 

Each group will consist of 2-5 students and every member will be tasked with creating their own web page that displays some fun information about themselves.
If you feel uncomfortable with creating an "About Me" page, then you are free to create a web page about a topic of your interest. Please make sure the topic does not violate any university student guidelines. 

The purpose of this project is not so much to create some beautiful website, but to familiarize yourself with using git and GitHub in a group setting. This project will force you to learn common git commands that will be used to collaborate with your team. You will also be tasked with learning how to create a simple static webpage using HTML, CSS, and some JavaScript. 

Every group will have the autonomy to decide what technologies they would like to use for styling their webpage. You can use simple CSS or choose to import any other styling library like Styled Components, Tailwind CSS or MUI. 

GOALS:

-	Become comfortable working with other developers in a group setting.
-	learn how to use basic git commands i.e. create branches or make pull and push requests. 
-	Create a static website utilizing HTML, CSS and JavaScript. 


Steps to getting this project started:

1. Each team will create a new github organization. An organization will be a shared github account that each team member can access.

Follow the directions provided in this link. Please sign up for the free personal account.

- https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/creating-a-new-organization-from-scratch

Make sure to invite all team members to the new organizaion. 

2. Create an empty public repository in the organization. 

One team member will clone the repository.

git clone https://github.com/wangalec/website-template.git

cd website-template




back in you terminal 

git remote set-url origin https://github.com/your-account/newly-created-github-repository.git

check if the remote repository has been linked

git remote -v 

you should see a 

origin	https://github.com/your-account/newly-created-github-repository.git (fetch)
origin	https://github.com/your-account/newly-created-github-repository.git (push)

git branch -M main
git push -u origin main

You should now see the newly cloned project in the organization's repository. 

Now the rest of the team can fork that repository
git a