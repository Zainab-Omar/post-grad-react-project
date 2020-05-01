# Upgrade Your React Project

## Introduction

Being able to build applications in React is a skill currently in high demand.
Your final project plays a crucial roll in showing potential employers that you
have this skill. Below are some suggestions for what you can do to upgrade your
React project.

> **Note:** If there are any lessons or labs you were not able to get to in the
> React and Redux sections of the software engineering course, we recommend
> taking time to complete them now!

## Refactor

As your final project, your React app should be a shining example of your
programming skills. Refactoring your app will not only help you review what
you've learned, but allows you to show that you are thoughtful about structure
and readability. One specific challenge for React - components. Components are
flexible enough that we could theoretically build our whole app in a single one.
It is also possible to go to the opposite extreme and have tons of small
components. Refactoring provides an opportunity to find a happy medium:
configuring components so they follow logical and readable design patterns. The
official React documentation provides [a guide on thinking in React][] that
might help in identifying what to refactor in your project. Also, keep
the following questions in mind while refactoring:

- **Is the code DRY? Is there any redundant content that could be reduced or
  abstracted?** Sometimes, it is easier to duplicate code in multiple components
  than reorganizing the hierarchy of components. Take some time to clean up any
  repetitive patterns in your code. You might discover a better, more
  understandble structure for your components that reduces the need for extra code.
- **Can you spot and unnecessary or overly complicated code?** Along similar
  lines, the component structure can sometimes lead to convoluted code as we try
  to get features to work. Occasionally, we try things until something sticks.
  Sometimes, the moment a piece of code works, we move on to the next task
  without reconsidering what we've written. Now is the time to look back and
  find examples of this in your project.
- **Are there new approaches to achieving what your project does?** React is
  constantly evolving. Using your existing project is a great way to keep
  learning about new features by trying to implement them in place of existing
  code. For instance, you may currently be more comfortable using class
  components and lifecycle methods. If so, try implement functional components
  and [hooks][] instead. [Context][] is another new React feature that might be
  useful in cleaning up some of your components.

[hooks]: https://reactjs.org/docs/hooks-intro.html
[Context]: https://reactjs.org/docs/context.html

[a guide on thinking in React]: https://reactjs.org/docs/thinking-in-react.html

Remember that refactoring shouldn't change functionality.

## Finish and Add Features

Your project may meet all the requirements that were laid out at the time and be
slightly past the MVP stage. However, this does not mean it is fully developed.

Think about what features you can add to bring it to the next level. A few
suggestions specific to your React project:

- You should have some basic communication between your backend and frontend for
  CRUD functionality already. What else can be added? Are there any backend
  calls you weren't able to implement? If you were not able to implement user
  authentication using JWT, try implementing it now.
- Are there any external APIs that could be used to boost your project's
  functionality?

For your CSS:

- Establish a consistent theme across your app. CSS is often the last
  thing students work on during their final project, but it can also make
  your app more visually appealing. Non-technical visitors to the site may not
  grasp how complicated the code behind it is, but they can definitely recognize
  if it is well-designed.
- Make your app responsive. Using [media queries][], design your
  project so that it looks good regardless of whichever device it is being viewed on.

[media queries]: https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries

## Make Your App Accessible

Another vital addition you should consider for your React project is
accessibility. The internet is an essential resource for millions of people, but
many websites lack accessibility options, making them difficult or impossible to
use for many people.

For more information on web accessibility and why it is important, check out the
World Wide Web Consortium's [Introduction to Web Accessibility][access]. For
specific ideas on how you can make _your project_ more accessible,
[read through this checklist to help guide you][checklist].

[access]: https://www.w3.org/WAI/fundamentals/accessibility-intro/
[checklist]: https://dev.to/sylwiavargas/checklist-web-accessibility-3abl

## Turn Your App into a Progressive Web App

[Progressive Web Apps][] follow specific standards for making a web app function
in a similar way to applications built to natively on a particular operating
system. Among other things, this includes building an application that is
functional even if a user is offline or on a poor internet connection.

If you used [Create React App][] to start your project, some PWA functionality
is already provided and ready to implement. To learn more about how to convert
your app into a Progressive Web App, [check out this guide][pwa guide].

Google also provides a tool that can help you implement your PWA called
[Lighthouse][]. Lighthouse audits your project for performance and
accessibility.

[Progressive Web Apps]: https://en.wikipedia.org/wiki/Progressive_web_application
[Create React App]: https://github.com/facebook/create-react-app
[pwa guide]: https://web.dev/progressive-web-apps/
[Lighthouse]: https://developers.google.com/web/tools/lighthouse/

## Deploy Your Project

If you haven't deployed your React project, make sure to do so! As your final
project, it is expected to be the most developed project you completed during
the software engineering course. Deploying allows you to show off what you've
built.

We recommend deploying your frontend to [GitHub Pages][], but you are free to
choose what you think is best.
[Check out this tutorial for how to do it][deploy to gh-pages]. Alternatively,
[Firebase][] provides free hosting and command-line tools that also work well
for this purpose.

For the Rails backend, as with all Rails apps, we recommend
[Heroku](https://www.heroku.com/). Heroku has a free hosting tier that many students
have utilized over the years. They also
[provide a detailed tutorial on how to get your Rails app deployed][heroku deploy].

> **Recommended:** Once you've deployed your project, make sure to do some
> quality assurance testing:
>
> - **Test every route on your backend**. Make sure your frontend and backend
>   are communicating properly.
> - **Click every link**. Make sure there are no bad links on your frontend.
> - **Navigate around your app in different ways**. If a visitor does something
>   slightly unexpected, can your app handle it?
> - **Open your app using a variety of devices and browsers**.
> - **Share the app with some friends and ask them to play around with it**. You
>   might know how things are supposed to work, but giving your app to someone
>   else can identify unexpected user behaviors. Better your friends find
>   bugs than a potential employer.
>
> Deploying your app is a big plus for building your online presence, but
> **deploying a broken app can be worse than not deploying anything!**

[GitHub Pages]: https://pages.github.com/
[deploy to gh-pages]: https://github.com/gitname/react-gh-pages
[Firebase]: https://firebase.google.com/
[heroku deploy](https://devcenter.heroku.com/articles/getting-started-with-rails5)

## Record a Demo Video

When your project is fully functioning and looking great, consider recording a
demonstration of how your app works. Recording a demo allows you to showcase
features you're particularly proud of. It also means you can provide context to
your application that may not be apparent from just looking at the app itself.

A demo recording should go through the essential parts of your application. One
bonus that comes from doing this - during interviews, you will often need to
talk about your projects. If you have a project listed on your resume, assume
that you may need to explain what the project is, as well as the challenges you
faced during development. A demonstration video will force you to practice this
pitch so you'll be more comfortable when you have to do it live.

A demo recording also acts as an excellent way to introduce yourself. You can
use it to show off a bit of your personality. It also shows your ability to
communicate complex topics - a critical skill on all tech related teams.

## Conclusion

There are many directions you can go in when upgrading your React project.
Having a well-polished React project is a great capstone proving what you've
achieved while learning to code. With React in high demand for web development
roles, any time you invest in improving this project will be beneficial to your
job search.