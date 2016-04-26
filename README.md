# Conan libraries and code wishlist

This repository is a community effort used to track requests for code and packages that users would like to have available
in conan. This Readme might contain a **summary** of the requests and status, as well as recent news. But the
main flow of information is via github issues, please read the following guide:


## Submitting a request

If you would like that a conan package existed for certain project/library/code, follow these steps:

1. A package is mainly defined by its name and version. Boost/1.59 is a different package from Boost/1.60.
2. First check that a package doesn't already exist in conan.io. If it exists, but fails for your settings, try
first to tell the package author, possibly submit an issue to that package specific repository,and try to
collaborate with them to fix the problem. 
3. If the package doesn't exist, or the existing package in conan will not support your settings (e.g. the
original author cannot provide support for your OS due to lack of testing platform), go to 
this repository "Issues", and look for it. Check it is not requested yet, even not in "closed" issues.
4. If it is not requested, **open a new issue**. Use the library name and version, (e.g. Boost/1.60),
followed by a very small description of the library as the issue title. 
Briefly describe the purpose of the library in the comments, together with some link
to URLs where to get the source code. If there exists a package in conan, say why it is not valid for
your use case. A small description of your project, intended usage, or why you need
it would be nice too. 3-4 lines is enough.
5. If there exist an **open issue**, vote for it, +1 in the comments. Add your reasons or intended usage.
You can also downvote a library, in this case, it is compulsory to add an explanation. Alternative packages
might be proposed (just cited), but please do not enter a discussion about it in the issue. Just open a new issue if you
think the alternative package is better, and explain its merit in the comments.
6. If there exist a **closed issue**, please check why it is closed. If the reason is that of
an already existing package in conan.io, note that the preferred mechanism to improve or request fixes
of existing packages, is directly to submit issues to the repositories of the package maintainers. If
they are not willing to provide support for your platform, you can propose it in this closed issue, so it may
eventually be re-opened.

## Implementing a package

If you are willing to contribute creating some package, follow these steps:

1. Check this repository "Issues", and choose the one you would like to implement. Tell so in the comments.
2. If the package you want to work on, there is already someone working on it, please talk to them. You
could possible collaborate together, testing things, trying different platforms, etc.
3. Use the issue to notify other users when you have something to try. Provide links to conan packages and
give usage instructions if necessary.


## Validating a package

If you have requested a package, package authors will post information about their progress, and ask
requesters for testing. Please, try to acknowledge their work by following their instructions and
testing things out.

1. When things work, please say so, explicitely stating your setup: OS with version, compiler, version,
architecture, libraries, build options...
2. When things do not work, also explicitely state your setup: OS with version, compiler, version,
architecture, libraries, build options, and a very brief summary (1-2 lines) of why it is failing. Please link
to the package creator repository for full bug reports and issue following.


## Code of conduct

Please note this is a community effort, and this repository is just a hint to package creators.
There are no guarantees that any request will be fulfilled, so
please be polite and patience. Also, package creators are not responsible, not obliged to provide
any type of support, maintenance, training, or user help, and in general they will provide
packages as-is, without any liability. 

