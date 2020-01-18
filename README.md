# MP 0: The Basics
### Due: Wednesday, Sep 08, 11:59PM

## Table of Contents
1. [Assignment](#assignment)
2. [Environment Setup](#environment-setup)
3. [Grading Breakdown](#grading-breakdown)
4. [Rules](#rules)
5. [Submission Details](#submission-details)

## Assignment
This assignment designed to help you set up your development environment. You will build a simple card using only HTML/CSS. The card will look like [this example](http://i.imgur.com/aeKrEga.png) except with your own details.

#### Requirements
1. The webpage should mirror the layout shown in the example.
2. Elements: You should use at least one of all the following: image (`<img>`), link (`<a>`), paragraph (`<p>`), heading (`<h1>, <h2>, ...`).
3. Layout: The image, heading, and link must all be horizontally centered. The biography text can be either left-aligned or horizontally centered.
4. Styling: All styling must lie within the CSS file. (No inline styling!)
5. The image should have a height and width of 150px.

#### Optional
If you'd like to get some hands-on experience with Javascript before the next MP, you may attempt to recreate [this example](https://uiuc-web-programming.gitlab.io/fa21/images/mp0.gif). Although this will not be graded, understanding this early-on will make your life significantly easier for the next MP! :)

To get started, follow the [environment setup](#environment-setup).

## Environment Setup
1. Make sure you have [Node.js](https://nodejs.org/en/) and [git](https://git-scm.com/) installed.
2. Create an account on [GitLab](https://gitlab.com/)
3. Clone this repository:
`git clone https://gitlab.com/uiuc-web-programming/mp0 mp0`, then `cd mp0`
4. Install dependencies:
`npm install`
5. Start the dev server:
`npm start`

If the web browser does not open automatically, go to `http://localhost:8080/` to view your page. Note that if for some reason your port 8080 is occupied, it will default to 8081. If you can see "Hello World!", then you are all set!

You should now be able to edit the files in the `src` folder and see the changes in your browser.

## Grading Breakdown
This assignment is worth 5% of your final grade. Breakdown is as follows:
1. Correct HTML tags and content (2%)
2. Correct CSS styling (%2)
3. Correct Deployment and submission (%1)

## Rules
- This is an individual assignment. No collaboration is permitted.
- It is not permitted to copy/paste code that is not your own. You are, however, free to look at different code sources for inspiration and clarity. All sources (code as well as reading material) that you reference to complete this assignment must be declared in the submission.
- There must be no use of any library.
- There should be no use of inline styling.
- No inline script tags should be used.
- HTML tables cannot be used for layout.
- If you think something you’re doing might not be acceptable, please ask on Piazza.

## Submission Details
Here's what you will need to submit:
1. Create a private repository on GitLab. Make sure "Initialize this repository with a README" is **not** checked.
2. Change the remote url for the mp0 directory to the url of the new private repository you created.
```
git remote rename origin old-origin
git remote add origin git@gitlab.com:<your-gitlab-username>/mp0.git
```
3. Commit and push your local changes to this new repository.
4. `.gitlab-ci.yml` file automatically makes a Gitlab CI pipeline run to deploy your code. After the pipeline finishes, your site should be live at `https://<your-gitlab-username>.gitlab.io/mp0`. **It may take up to 10-30 minutes for the site to go live after the first deployment.**
5. Invite `uiucwp` as a collaborator. This should be as a **reporter**, not as a *guest*, otherwise we can't see your code.
6. Fill out and submit the form [here](https://forms.gle/MScXPxA2TThLNco76).
