# Frontend Group Project Requirements
## February 2, 2021 - February 13, 2021

## TEAMS

- Team One: Ernie
- Team Two: Athena & Dee

## Learning Objectives

By now, you should have most of the skills necessary to understand much of the world of web development (HTML, CSS, JavaScript). The intent with these requirements is for each student in the group to use these skills to learn something new and use it in a "real world" way. Searching for external resources and being able to understand and apply documentation is a big part of software development. Whether it is an API, a new JavaScript library, deployment, testing, etc. Go learn something new and put those web development skills to work!

Another goal of this project is polish / thoroughness. A thorough `README.md`, deploying to a public web server, thoughtful commit messages, following a PR review process, good code organization, etc are all signals of quality software development. The end result of this project should be a portfolio piece that you are excited to put on your resume and share with friends and family: "Hey - look at this cool thing I built!" Look for opportunities to polish and show the world what you can do!

## Project Description

You will be using the front-end skills you have developed throughout the frontend phase:
* HTML
* CSS
* JavaScript
* AJAX
* APIs

## Technical Requirements

Your application **must**:

- Use at least one JavaScript library that is not jQuery. Examples:
  - [Moment.js](https://momentjs.com/)
  - [Marked](https://marked.js.org/)
  - [jQuery UI](https://jqueryui.com/)
  - [chessboard.js](http://chessboardjs.com/)
  - [Additional List](./additional-libraries.md)

- Be styled with CSS. Examples:
  - [Bootstrap](http://getbootstrap.com/)
  - [Bulma](https://bulma.io/)
  - [Foundation](https://foundation.zurb.com/)

- Access at least two remote APIs *using AJAX*. Examples:
  - [TheCatAPI](https://thecatapi.com/)
  - [DogCEO](https://dog.ceo/dog-api/)
  - [API List - n0shake/Public-APIs](https://github.com/n0shake/Public-APIs)
  - [API List - public-apis](https://github.com/public-apis/public-apis)
  - Note that loading a JavaScript or CSS library from a CDN does not fulfill this requirement.
    You must use AJAX.

- Have a `README.md` file written using [Markdown] with at least the following:
  - Explanation of what the project is / what it does.
  - What technologies you used.
  - Screenshots of your project.
  - List of team members.

- Be deployed online and publicly accessible. Examples:
  - [Netlify](https://www.netlify.com/)
  - [Amazon S3](https://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteHosting.html)
  - [Google Cloud](https://cloud.google.com/storage/docs/hosting-static-website)
  - [Surge](https://surge.sh/)
  - [Vercel](https://vercel.com)
  > Note: You do not need to purchase a domain name for your project.

- Code must follow some organization scheme.
  - Everything cannot be in one super long file.
  - Break different parts of the code into different files / modules.
  - Good variable names
  - Good comments
  - Optional: Consider using a build system with [npm scripts], [browserify], or [webpack]

[Markdown]:https://guides.github.com/features/mastering-markdown/
[StandardJS]:https://standardjs.com/
[npm scripts]:https://deliciousbrains.com/npm-build-script/
[browserify]:http://browserify.org/
[webpack]:https://webpack.js.org/

## Workflow Requirements

- Teams will be groups of 3-5 students and assigned by instructors.

- Create one GitHub repo and add all group members as collaborators.

- Collaborate using Pull Requests (PRs):
  - No one should commit to the master branch directly.
  - Every PR should be reviewed and approved by at least one team member (not the person who originated the PR).
  - PRs should not be merged by the person who opened it (no self-merging).
  - See below for [suggested PR rejection criteria](#suggested-pr-rejection-criteria)

- Project features and bugs must be tracked using a [scrum]-like system:
  - Every PR should be associated with a GitHub Issue (or similar).
  - Consider using a tool like [GitHub Project Board] or [Trello].
  - Every class day teams will have a "stand up meeting" with a TA or Instructor.

[scrum]:https://en.wikipedia.org/wiki/Scrum_(software_development)
[GitHub Project Board]:https://help.github.com/articles/about-project-boards/
[Trello]:https://trello.com/

## Suggested PR Rejection Criteria

It's ok to reject a PR or have a PR rejected - that is what the PR process is
for! Remember if your PR is rejected that doesn't mean you are a bad person and
stink at life. It just means that your teammate(s) see something that could be
improved. The PR process is more about sharing knowledge than "you did something
wrong".

Any of the following are valid reasons to reject a PR:

- Does not fulfill feature (i.e. if the feature it doesn't work correctly or at all)
- Breaks other feature (i.e. make sure existing features still work)
- Does not follow team coding style / standards (i.e. if you use prettier or ESLint, make sure you all have the same settings)
- Too much to review / large code diff (i.e. should be broken up into smaller PRs)
- Code in the PR does not match up with commit message (i.e. if it contains work other than that which the task requires)
- Commit message is vague (i.e. 'please work' is not a good commit message)

# DAY 1: February 2, 2021

Review the technical requirements, and focus on making commits on day 1 that only serve to check boxes on the requirements. Your initial git should include:

- base source files - index.html, scripts folder, css folder, images folder
- choose a css library and get it installed (bulma/foundation/bootstrap)
- when you have found your APIs, add a couple of fetch requests to your main script that just perform the requests and store the response in a variable
- bring in a supporting javascript library and install it into your html
- slap HELLO WORLD into your index.html
- add a README.md that gives an outline of your project

At this point, commit, and then focus on the rest of day 1 and 2 on deploying it. As soon as you can see your "HELLO WORLD" page deployed, turn right back around and actually build the thing.

I can count on one hand the number of students who heed the "check the boxes, deploy early" advice, but i still stand by it. Knowing you've ticked the boxes and can focus on building something unique is a huge relief and frees you up for stretch goals without worrying about how you're going to deploy.

