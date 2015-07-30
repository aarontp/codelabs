codelabs
========

**VERY IMPORTANT DISCLAIMER**
The codelabs are ATM **WIP** and have not yet been upgraded to work with the latest
version of plaso (version 1.3). This disclaimer will be removed once they are
working again.

Placeholder for all codelabs used for plaso development.

There will be more text here describing how the codelabs work. Things like:

* How to get started.
* What this is all about.
* Get this to work.

Essentially this repo contains codelabs for people that want to learn
how to develop code for [plaso](https://github.com/log2timeline/plaso), whether
those are plugins or parsers.

One good source of information is the [API documentation](http://plaso-api.readthedocs.org)
that can help people understand the required API before developing your own modules.
However it can be quite daunting trying to get through all the API documentation and thus
we created these iPython based codelabs, allowing future developers to see how the API
works interactively and play with getting things to work.

### Getting Started

The simple way to get started is just to download the codelabs and start working on them.

To do that, simply run:

```
$ git clone https://github.com/log2timeline/codelabs.git
$ cd codelabs
$ ipython notebook
```

Open up your web browser and start working. The codelabs should be fully self-explanatory.

If there are questions, send them to the [developers mailing list](https://groups.google.com/forum/?fromgroups#!forum/log2timeline-dev)

### Why Codelabs?

It can be a daunting task to just start developing code for the plaso project.
There are certain [rules](https://github.com/log2timeline/plaso/wiki/Style-guide) to follow,
[code reviews](https://github.com/log2timeline/plaso/wiki/Codereview) to go through and
[API's](http://plaso-api.readthedocs.org/en/latest/) to read over and understand.

However in order to lower the barrier of entry into the wonderful world of contributing
code to the plaso project we decided to create few codelabs that demonstrate how the API
works in a simple to follow IPython notebook. That gives the developer a more thorough
explanation of the inner details of plaso, how to write a parser and why things are the
way they are. It also gives the developer an easy way to change piece of code and re-run it
and instantly the results of their labor, something we hope can serve as an enocuragement
to start contributing code.

### Things are not working, what gives?

The plaso codebase can sometimes be moving relatively fast, which means that sometimes things
in these codelabs may break from time to time. There may also be other issues, such as
issues with installed dependencies, etc.

First thing to try out is:
 + does plaso work, that is can you parse a disk image or some files you've got lying around
 + what does the python utils/check_dependencies.py script give back? Are there any errors

If you still have issues after consulting the appropriate development release installation guideline
([Ubuntu](https://github.com/log2timeline/plaso/wiki/Development-release-Ubuntu), [Fedora](https://github.com/log2timeline/plaso/wiki/Development-release-Fedora-Core), 
[Mac OS X](https://github.com/log2timeline/plaso/wiki/Development-release-Mac-OS-X) or [Windows](https://github.com/log2timeline/plaso/wiki/Development-release-Windows))
and the check dependency script indicates all dependencies are up-to-date send an email to the
[development mailing list](https://groups.google.com/forum/?fromgroups#!forum/log2timeline-dev).
