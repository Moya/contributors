### Moya Community Continuity Guidelines v2.0.0
##### Background

Moya started out as a project in Artsy under the ownership of [Ash Furrow](https://github.com/ashfurrow) and [Orta Therox](https://github.com/orta). Over time, developers from the community began using Moya and it became a community-driven project.

After watching [The Social Coding Contract](http://blog.testdouble.com/posts/2014-12-02-the-social-coding-contract.html) we looked to find ways to make [the project](https://github.com/Moya/Moya/issues/135) more welcoming to external contributors.

Because of this, we created the [v1 Moya Community document](https://github.com/Moya/contributors/blob/0d5e80682b2377bdca72585eda9ce83467bee3c4/README.md) - over time the ideas have spread to more projects. This eventually lead to the creation of a more easily applicable template.

This repo contains a document [Contributing.md](Contributing.md) which is a template for others to help foster their own communities. Think of it as a code of conduct for the continuity of your community.

---------

### I want to apply these guidelines

Great! So, this is not quite another file to copy & paste into your project. It's slightly more involved. 

It's not too many steps though, and the majority of them are common sense things you would do anyway.

- [ ] Copy the file `Contributing.md` into your repo.
- [ ] Change the bottom paragraph to show how people can contact organizers privately
- [ ] Ensure that it makes sense when the guidelines talk about the project not being continuously deployed. If it doesn't make sense, remove it.
  - For example, in a library, you have to deploy to a package manager. This means there is always a chance for cleanup and final reviews before a release.

- [ ] [Lock the master branch](https://help.github.com/articles/configuring-protected-branches/), to ensure code review as the way to get code in. Even for admins. Everyone plays by the rules.

- [ ] Ensure there is a label for people to find easy issues with. We strongly recommend you use a [label name from one of this set](https://github.com/Charlotteis/libraries.io/blob/6afea1a3354aef4672d9b3a9fc4cc308d60020c8/app/models/github_issue.rb#L8-L14) in order to be involved with the larger ecosystem.

And you're good. 

In our opinion, you're also welcome to add some flourish at the top about why you want to work this way. This is not a legal document, and doesn't aim to be, offering insight into why you choose to work this way can make the document a nicer read.

### Useful Bits of information for project owners

- [Danger](https://github.com/danger/danger) is a project that can be used during CI that can check to see [if someone is inside an organization](https://github.com/danger/danger/blob/93f4f1e92f9748ab04a148b6c60c431a0247efcc/Dangerfile#L7-L15), making it possible to ask if they would like to be invited.
- We believe so firmly in these community guidelines that [we have automated them](https://github.com/Moya/Aeryn).

##### Other references

* The [Jekyll Project](https://github.com/jekyll/jekyll) has some great documentation around [being a maintainer, and avoiding burnout](https://github.com/jekyll/jekyll/pull/5011/files).
* The Jekyll's maintainer documentation is based on [Homebrew's](https://github.com/Homebrew/brew/blob/master/share/doc/homebrew/Maintainers-Avoiding-Burnout.md).
* CocoaPods has a [Communication & Design Rules](https://github.com/CocoaPods/CocoaPods/wiki/Communication-&-Design-Rules) which provides advice for project maintainers.

### I want to improve the Community Continuity Guidelines

Great, so do we. Feedback in issues is a great way to work, as is pull requests  improving our wording. This is an evolving document, so we'll be trying to apply [Semantic Versioning](http://semver.org) to it.

We consider extra guidelines as being major releases, tweaks to existing rules as minors, and depending on other wording changes - patches. We'll be using our best judgement as we can.

### This Repo

We use a [Code of Conduct](Code%20of%20Conduct.md), which is adapted from the [Contributor Covenant](http://contributor-covenant.org), version 1.3.0, available at [http://contributor-covenant.org/version/1/3/0/](http://contributor-covenant.org/version/1/3/0/). The CoC is taken seriously by the project owners.

#### What about if you have questions that cannot be put into a public issue?

Both [Ash Furrow](https://github.com/ashfurrow) and [Orta Therox](https://github.com/orta) have contactable emails on their GitHub profiles, and are happy to talk about any problems.
