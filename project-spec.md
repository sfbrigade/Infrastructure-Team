# Code for San Francisco Technical Project Spec

This document describes a spec that all projcets within the Code for SF
Infrastructure team must adhere by and that we encourage all Code for SF
brigade projects to also adhere by.

## Technical Spec

Adhere to all clauses of the [OSS Manifesto](http://ossmanifesto.org/). These
are repeated below for convenience (and to add clarity to each component).
Those clauses which we added are demarked with "(added)".

You can and should advertise that your repo meets these minimum requirements
for an accessible repo with a badge in your README!

Display ![https://github.com/sfbrigade/Infrastructure-Team/blob/master/project-spec.md](https://img.shields.io/badge/sfbrigade-project%20spec-brightgreen.svg) by including the following:

```
![https://github.com/sfbrigade/Infrastructure-Team/blob/master/project-spec.md](https://img.shields.io/badge/sfbrigade-project%20spec-brightgreen.svg)
```

### Have a readme file

The project should have a README file that clearly describes:

- The objective of the project
- Any dependencies of the project
- How to run the project (or how to use it if the project is a library)
- How to run the tests for the project
- Core team members (see below)

### Have a contributing file

Have a CONTRIBUTING.md file that describes how to:

- File issues
- Contribute code back

It may also include:

- Any branch name strategies
- Expected commit format
- Pointers to any mediums that project uses to communicate (e.g. Slack or IRC)
- Anything else a user wishing to contribute code back to the project should
  know

### List all core team members in the readme file

List all core team members somewhere in the README.

### Have a contributors file (added)

Have a CONTRIBUTORS file that lists all of the contributors in alphabetical order.

### Have a license file

Have a LICENSE file that describes how the code can be used. See
[choosealicense](http://choosealicense.com/) if you aren't sure which license
to apply to your project.

### Have a changelog

Have a CHANGELOG file that describes the changes in between each release of the
software (and also keeps a running list of unreleased changes). This should not
just be a dump of `git` commit messages, see
[keepachangelog](http://keepachangelog.com/) for a description of a well
formatted CHANGELOG.

### Follow semantic versioning

Follow [semantic versioning](http://semver.org/) when releasing new versions of
your project. This will help users of the project know what to expect when
upgrading.

### Tag all major releases

Tag all releases with a `git` (or equivalent in your VCS of choice) `tag`. This
well help users easily check out the project at specific revisions.

### Provide documentation

Most of this falls under "Have a readme file", but you should ensure that your
project is well documented. You can also consider using the
[Wiki](https://help.github.com/articles/about-github-wikis/) feature if your
project is on Github for user documentation.

If your project's language or stack has a common way to document, using this
will make it the easiest for users coming from that background (e.g. if your
project is a Ruby library, you may want to use `YARD` to document it). This
will help users looking at the project quickly get up to speed in using your
project (and be able to contribute back).
