Hosting our code
----

1. All our projects are hosted on [GitHub](https://github.com/Piletilevi).  
2. Developers are welcome to mirror the code, if its covered by non-disclosure agreement. However, all commits must reach our repositories in real-time.
3. All in-house or third-party issue/bug-tracking mechanisms used by our development partners must be real-time linked to our repository.
4. Best practices for versioning have to be enforced as described by [SemVer 2.0.0](http://semver.org/spec/v2.0.0.html)
5. Best practices of branching have to be enforced as described by [Vincent Driessen, 2010](http://nvie.com/posts/a-successful-git-branching-model/);
    Please have the [mental model](./Git-branching-model.pdf) printed out and stick it on your developer's favorite vending machine.
6. Everybody in development cycle - from developer to QA to tester to customer - should have access to automatically built deployment that is software-identical to production. Be it [Ansible](http://www.ansible.com/), [Chef](http://www.getchef.com/), [Docker](https://www.docker.io/), ...
7. First solution is not the best one unless alternatives are discarded as inferior.
8. It's important to decide whether a method or practice is right for your company based on business needs — not on IT limitations.

Cool Words
----
- [Continuous Integration](https://www.thoughtworks.com/continuous-integration) is a development practice that requires developers to integrate code into a shared repository several times a day. Each check-in is then verified by an automated build, allowing teams to detect problems early.  
  Most cited [landmark article](http://www.martinfowler.com/articles/continuousIntegration.html) by Martin Fowle, 2006.
- [Continuous delivery](https://www.thoughtworks.com/continuous-delivery) is the process of having your development flow steadily creating a deployable version of the system. Where and when (and even if) you deploy that package depends on your situation, but the key point is to keep your code in an always-deployable state.  
  Continuous Delivery aims to make releases boring, so we can deliver frequently and get fast feedback on what users care about.

References
----

- [JIRA integration](https://help.github.com/articles/integrating-jira-with-your-projects/)
- [MantisBT](https://www.mantisbt.org)
	- [SourceGithub Configuration](https://github.com/mantisbt-plugins/source-integration/blob/master/docs/CONFIGURING.SourceGithub.md) plugin requires Mantis 1.2.16. Latest stable as of _Feb 17 2016_ is [release-1.2.19](https://github.com/mantisbt/mantisbt/releases/tag/release-1.2.19)
	- [Upgrading MantisBT](https://github.com/mantisbt/mantisbt/blob/master/readme.md#upgrading)
	- [Outdated (2009) article](https://noswap.com/projects/source-integration) about Mantis integration with different source controls.


---
[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)  
Piletilevi Coding Standards by [Mihkel Putrinš](https://github.com/mitselek)
is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
