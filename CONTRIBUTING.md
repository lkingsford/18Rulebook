Contributing to 18Rulebook
==========================

# General

All contributions of code and documentation must be licensed as per the
[License File](./LICENSE.md) to be accepted. This means that documentation in
the rulebook needs to be under the Creative Commons Attribution license, and
code is under the MIT License.

If you would like your attribution to be noted, please add your name to the
[Attribution List](./ATTRIBUTIONS.md)

I have the general attitude that whilst I prefer contributions to follow the
rules set out here, I stand by PEP 8 where it says ['A Foolish Consistency is
the Hobgoblin of Little Minds'](https://www.python.org/dev/peps/pep-0008/#a-foolish-consistency-is-the-hobgoblin-of-little-minds).
Where sticking to these rules is going to make it harder, don't stick to them.

We do use GitHub to manage this project. Make changes to this project by making
a Pull Request on [https://github.com/lkingsford/18Rulebook/].

There is no taboo against discussing these rules. They are not unchangeable,
and I may be wrong.

# Commits and Pull Requests

- A commit should only have a set of changes to the rules to achieve one thing,
  or fix one problem.

- A pull request should only have related changes. Separate changes should be
  in another pull request.

# Documentation

## Relevance

- In order for a rule addition to be accepted, in must be in use by at least
  one game that has been published or is in development. Please provide the
  name of the game as part of the pull request.

## Format

- We use (GitHub Markdown)[https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet]
  for all documentation.

- Please keep lines under 80 characters except where broken by a URL.

- The template language is defined in [TEMPLATE.md]. It must be used.

## Language

- The `TEMPLATE` folder is to be in US English. Other languages should be in
  `TEMPLATE_{Language code}` (For instance, `TEMPLATE_FR`).

- Please keep language simple where possible. This is not the place to show off
  your vocabulary.

- Semicolons are to be avoided. Consider carefully if two shorter sentences
  could make the rule more clear.

- To be of maximum utility, avoid using things that may convey a particular
  tone. This should be the rules to play, useful examples, and little else.
  Flavor text is the domain of the eventual final author who is making their
  game with this tool.

## Templates

- File names of templates must be in lowercase, with underscores instead of
  spaces, and the extension `.md.template`.

- Variable names must be universal where different templates rely on the same
  variable.

- Variable names must be in lowercase, using `.` to separate categories.

## Example games

- Example games must be in lowercase, with underscores instead of spaces, and
  the extension `.rules`.

# Code

- All code must be compatible with Python 3.6.

- All code must abide by [PEP 8](https://www.python.org/dev/peps/pep-0008/#a-foolish-consistency-is-the-hobgoblin-of-little-minds).