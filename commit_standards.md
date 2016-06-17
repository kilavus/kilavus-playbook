Commit Standards
================

Welcome to the commit standards page!

Our projects use some standards in order to increase the coherence among team members and help them communicate in a more unambiguous and consistent way. We strive to make life easier for everyone. And writing good commit messages hold an important place among these endeavours. Yes, it really _does_ matter.

## Descriptive Templates

You can take an example by looking at these patterns; use them when needs arise (ordered most common to least common).

##### Single line commit message referencing an issue:
```
#3 Define commit standards
```

##### Multi-line commit message with bullets:
```plain
Summarize clearly in one line what the commit is about

- A problem the commit solves
- A remark relating to the commit
- A notice about killer rabbits
```

##### Multi-line commit message with a persuasive twist:
```plain
Summarize clearly in one line what the commit is about

Describe how your commit solves the problem or how
your new feature could be used. Justify your solution
in a reasonable manner.
```

## Dos & Don'ts

### DO
- Write the summary line and description in [imperative mood](http://en.wikipedia.org/wiki/Imperative_mood). Write “fix”, “add”, “change” instead of “fixed”, “added”, “changed”.
- Write commit messages in [sentence case](https://en.wikipedia.org/wiki/Letter_case#Case_styles); not title case (do not capitalize every word of the sentence).
- Always mention relating issue numbers in the commit message.
- Always leave the second line blank if you're writing a multiple line commit message.
- Line break the commit message so it could be properly viewed on GUI clients such as ```gitk``` without having the need to scroll horizontally.

### DON'T
- Don’t end the summary line with a period.
- Don't start commit messages with a lowercase letter (```add defect``` ✘ - ```Add coolness``` ✔).
- Don't start with a lowercase letter after issue reference (```#3 add sauce``` ✘ - ```#3 Add sauce``` ✔).


## Why write good commit messages?

Writing good commit messages:
- Makes the review process __much faster__.
- Makes writing release notes __much easier__.
- Helps future maintainers understand changes in the code __much better__.

> ~~"So code reviewers don't become blind, and kittens live."~~ :cat2:
