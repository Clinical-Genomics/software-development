---
layout: page
title: GitHub
permalink: /version-control/github/
---

## Introduction
First of all; GitHub is pretty simple. This 5 minute [interactive introduction][intro] will guide you through the basics. It won't take long, but it will set you up with some very powerful tools that will take you farther than you think.

![GitHub Flow Introduction]({{ site.baseurl }}/img/github-flow.png)


## GitHub Flow
[GitHub Flow][original] is how [GitHub uses GitHub to build GitHub][video]. It works especially well for projects that are continously developed and deployed. Imagine that you and your team make constant and small iterative changes to the code base, updating the production code multiple times a day.

Something more complex like [GitFlow][gitflow] could be a better fit for a project that makes less frequent, larger updates. In GitHub Flow, a "hotfix" can essentially be handled just the same way as a regular push to master in.

Don't take my word for it, though. Read the [original article][original], watch the rather entertaining [extended brief][video] by one of the GitHub engineers, or the [summary][summary] on the official GitHub blog. And remember the [introduction to GitHub][intro] mentioned above? That's in fact a pretty spot on description of the workflow in under 5 minutes. That simple.

Another benefit of adoting a simpler workflow is the potential of opening up for collaboration from non-technical colleagues.


[intro]: https://guides.github.com/introduction/flow/index.html
[original]: http://scottchacon.com/2011/08/31/github-flow.html
[video]: http://zachholman.com/talk/how-github-uses-github-to-build-github/
[gitflow]: http://nvie.com/posts/a-successful-git-branching-model/
[summary]: https://github.com/blog/1557-github-flow-in-the-browser