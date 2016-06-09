### Moya Community Continuity Guidelines v2.0.0
##### Background

Moya started out as a project in Artsy under the ownership of [Ash Furrow](https://github.com/ashfurrow) and [Orta Therox](https://github.com/orta). Over time, developers from the community began using Moya and it became a community-driven project.

After watching [The Social Coding Contract](http://blog.testdouble.com/posts/2014-12-02-the-social-coding-contract.html) we opted to find ways to make [the project](https://github.com/Moya/Moya/issues/135) more welcoming to external contributors.

Because of the created the [Moya Community document](https://github.com/Moya/contributors/blob/0d5e80682b2377bdca72585eda9ce83467bee3c4/README.md) - over time this has been adopted in more projects.

This repo contains a document [Community.md](Community.md) which is a template for others to help foster their own communities. Think of it as a code of conduct for the continuity of your community.

---------

### I want to apply these guidelines

Great! So, this is not quite another file to copy & paste into your project. It's slightly more involved.

It's not too many steps though, and the majority of them are common sense things you would do anyway.

- [ ] Copy the Changelog.md into your repo
  - Change [email] to your email
  - Change [org] to your organization

- [ ] Ensure that it makes sense when the guidelines talk about it not being continuously deployed. If it doesn't make sense, remove it.
  - For example, in a library, you have to deploy to a package manager. This means there is always a chance for cleanup and final reviews before a release.

- [ ] Lock the master branch, to ensure code review as the way to get code in. Even for admins. Everyone plays by the rules.

- [ ] Ensure there is a label for people to find easy issues with
  - We strongly recommend you use a [label name from one of this set](https://github.com/Charlotteis/libraries.io/blob/6afea1a3354aef4672d9b3a9fc4cc308d60020c8/app/models/github_issue.rb#L8-L14) in order to get larger appeal.

- [ ] Fill out the "What about if you have problems that cannot be put into a public issue?" section at the end.

And you're good. In our opinion, you're also welcome to add some flourish at the top about why you want to work this way. This is not legal, binding documentation, and doesn't aim to be.

### I want to improve the Community Continuity Guidelines

Great, so do we. Feedback in issues is a great way to work, as is pull requests  improving our wording. This is an evolving document, so we'll be trying to apply [Semantic Versioning](http://semver.org) to it.

We consider extra guidelines as being major releases, tweaks to existing rules as minors, and depending on other wording changes - patches. We'll be using our best judgement as we can.

### This Repo

We use a [Code of Conduct](Code of Conduct.md), which is adapted from the [Contributor Covenant](http://contributor-covenant.org), version 1.3.0, available at [http://contributor-covenant.org/version/1/3/0/](http://contributor-covenant.org/version/1/3/0/). The CoC is taken seriously by the project owners.

#### What about if you have questions that cannot be put into a public issue?

Both [Ash Furrow](https://github.com/ashfurrow) and [Orta Therox](https://github.com/orta) have contactable emails on their GitHub profiles, and are happy to talk about any problems.
