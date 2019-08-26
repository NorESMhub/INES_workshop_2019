---
title: "Introduction"
teaching: 0
exercises: 0
questions:
- "What do we need to be able to contribute?"
- "What contribution is welcome?"
objectives:
- "Understand what access is required to contribute to NorESM"
- "Understand what contribution is welcome"
keypoints:
- "NorESM ecosystem"
- "Software and tools required for contributing"
---

# Accessing to NorESM 

## NorESM webpage

The latest NorESM documentation is openly available on ReadTheDocs at [https://noresm-docs.readthedocs.io/en/latest/](https://noresm-docs.readthedocs.io/en/latest/). 

For accessing the documentation, a modern web browser is requested. If you wish to update the documentation, you would need a [Github account](https://github.com/). This will be discussed in depth in the next episode.

## NorESM source code

The NorESM source code is **not openly available** and access to the source code needs to be requested. If you do not have access to NorESM source code,  make sure to [obtain a copy of the model (using git)](https://noresm-docs.readthedocs.io/en/latest/gitbestpractice.html#gitbestpractice) before going further into the lesson.

There are two github repositories for NorESM (both private github repositories):

- [NorESM stable version](https://github.com/metno/noresm). Currently, it holds NorESM 1.2.0 (based on CESM 1.2.0)
- [NorESM development version](https://github.com/metno/noresm-dev). Currently, it holds the latest NorESM 2 versions that are based on CESM 2.*.

The NorESM team does not consistently create releases and it is usually impossible to guess which branch to use to run a NorESM simulation. Therefore, you would need to ask (for instance when you request access to NorESM github repository) which repository and what branch to use.

# Contribute to NorESM

> ## Remark:
>
> To contribute to NorESM, you would need (at least) a Github account. 
> If you do not have one yet, join Github [here](https://github.com/join).
> For more information, read [setup](../setup.html) instructions.
{: .callout}

There are many ways to contribute to NorESM and in this lesson, we will mostly discuss how to contribute to the [NorESM documentation](https://noresm-docs.readthedocs.io/en/latest/) and to the [NorESM source code](https://github.com/metno/noresm).

## Contributor Agreement

By contributing, you agree that we may redistribute your work; the license agreement depends on where you contribute. 
The [NorESM documentation](https://noresm-docs.readthedocs.io/en/latest/) is distributed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). 

**There is no license agreement for NorESM**: NorESM does not have a license and is not an open and publicly available software.

In all cases, we will try to address your issues and/or assess your change proposal as promptly as we can, acknowledge
your contributions.

Everyone involved in Norwegian Earth System Modeling hub agrees to abide by our [code of conduct](../CODE_OF_CONDUCT).

## How to Contribute

The easiest way to get started is to file an issue to tell us about a spelling mistake,
some awkward wording,
or a factual error.
This is a good way to introduce yourself
and to meet some of our community members.


1.  If you have a [GitHub][github] account,
    or are willing to [create one][github-join],
    but do not know how to use Git,
    you can report problems or suggest improvements by [creating an issue][issues].
    This allows us to assign the item to someone
    and to respond to it in a threaded discussion.

2.  If you are comfortable with Git,
    and would like to add or change material,
    you can browse the list of existing issues (see [below](#where-to-contribute))
	and submit a pull request (PR).
    Instructions for doing this are [included below](#using-github).

## Where to Contribute

1.  If you wish to change this repository,
    please work in <https://github.com/NorESMhub/INES_workshop_2019>,
    which can be viewed at <https://noresmhub.github.io/INES_workshop_2019/>.

2.  If you wish to change another repository in the [NorESMhub organization](https://github.com/NorESMhub),
    please review CONTRIBUTING.md guideline of the corresponding repository. In the 
	[section below](#what-to-contribute), we list priority areas but these are mostly
	to help you to find where to contribute.

3.  If you wish to add a new repository in the NorESMhub organization, 
    create a [new issue](https://github.com/NorESMhub/INES/issues/new)
	in this repository. Do not forget to mention the purpose of your issue.

## What to Contribute

There are many ways to contribute,
from writing new tools and improving existing ones
to updating or filling in the documentation
and submitting [bug reports][issues]
about things that don't work, aren't clear, or are missing.
If you are looking for ideas, please see the 'Issues' tab for
a list of issues associated with each repository.

Comments on issues and reviews of pull requests are just as welcome:
we are smarter together than we are on our own.
Reviews from novices and newcomers are particularly valuable:
it's easy for people who have been using these lessons for a while
to forget how impenetrable some of this material can be,
so fresh eyes are always welcome.

### Priorities

Here is a non-exhaustive list of repositories for which we need your help:

- [NorESM documentation](https://github.com/NorESMhub/NorESM-docs) which you can view [here](https://noresm-docs.readthedocs.io/en/latest/).
- [Galaxy Climate tools](https://github.com/NordicESMhub/galaxy-tools). See [issues](https://github.com/NordicESMhub/galaxy-tools/issues) to know what we need in priority. Have a look to the list of [projects](https://github.com/NordicESMhub/galaxy-tools/projects) that are aiming to demonstrate the use of climate data for multidisciplinary studies.

## Using GitHub

If you choose to contribute via GitHub, you may want to look at
[How to Contribute to an Open Source Project on GitHub][how-contribute].
To manage changes, we follow [GitHub flow][github-flow].

Each issues and pull requests are reviewed by volunteers and we also encourage you to do so.
The repository owners have final say over what gets merged into the lesson so it is often good practice to discuss your plans in an issue
before you implement anything.

To use the web interface for contributing to a lesson:

1.  Fork the originating repository to your GitHub profile.
2.  Within your version of the forked repository, move to the `master` branch and
create a new branch for each significant change being made.
3.  Navigate to the file(s) you wish to change within the new branches and make revisions as required.
4.  Commit all changed files within the appropriate branches.
5.  Create individual pull requests from each of your changed branches
to the `master` branch within the originating repository.
6.  If you receive feedback, make changes using your issue-specific branches of the forked
repository and the pull requests will update automatically.
7.  Repeat as needed until all feedback has been addressed.

When starting work, please make sure your clone of the originating `master` branch is up-to-date
before creating your own revision-specific branch(es) from there.
Additionally, please only work from your newly-created branch(es) and *not*
your clone of the originating `master` branch.


## Other Resources

General discussion of [Nordic Earth System Modeling hub][nordicesmhub-site]
happens on the [Nordic ESM hub zulip][nordicesmhub-zulip],
which everyone is welcome to join.

[nordicesmhub-zulip]: https://nordicesmhub.zulipchat.com/
[nordicesmhub-site]: https://nordicesmhub.github.io/
[github]: https://github.com
[github-flow]: https://guides.github.com/introduction/flow/
[github-join]: https://github.com/join
[how-contribute]: https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github
[issues]: https://guides.github.com/features/issues/


{% include links.md %}

