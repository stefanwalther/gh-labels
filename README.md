# gh-labels

> Central repository for GitHub labels

---

## Purpose

This repository acts as a central repository to provide definitions for GitHub labels, which then can be loaded by a GitHub action to apply the same set of labels to one or more repositories.

Labels are managed in the various branches of this repo.

This works perfectly in combination with the [gh-labels-action](https://github.com/julbme/gh-action-manage-label) GitHub action (or similar ones).

## Color Schema

Below are charts describing all of the common labels and colors and some guidance how they should be used.

Color | Hex | Description
--- | --- | ---
![](https://dummyimage.com/100x20/000000&amp;text=+)<br/>![](https://dummyimage.com/100x20/555555&amp;text=+)<br/>![](https://dummyimage.com/100x20/aaaaaa&amp;text=+) | `#000000`<br/>`#555555`<br/>`#aaaaaa` | Releases.
![](https://dummyimage.com/100x20/ee0701&amp;text=+)<br/>![](https://dummyimage.com/100x20/f3514da&amp;text=+)<br/>![](https://dummyimage.com/100x20/f56969&amp;text=+) | `#ee0701`<br/>`#f3514da`<br/>`#f56969` | Bugs at different criticality levels: "bug", "bug/sporadic test failure"
![](https://dummyimage.com/100x20/0e8a16&amp;text=+)<br/>![](https://dummyimage.com/100x20/28a745&amp;text=+)<br/>![](https://dummyimage.com/100x20/34d058&amp;text=+) | `#0e8a16`<br/>`#28a745`<br/>`#34d058` | Positive statuses: "help wanted", "verified"
![](https://dummyimage.com/100x20/eeeeee&amp;text=+) | `#eeeeee` | Negative statuses: "duplicate", "notabug", "stale", "unmergeable", "wip", "wontfix"
![](https://dummyimage.com/100x20/cc317c&amp;text=+) | `#cc317c` | Questions and discussions: "question"
![](https://dummyimage.com/100x20/fef2c0&amp;text=+)<br/>![](https://dummyimage.com/100x20/e99695&amp;text=+) <br/>![](https://dummyimage.com/100x20/fbca04&amp;text=+)<br/>![](https://dummyimage.com/100x20/ff7619&amp;text=+) | `#fef2c0`<br/>`#e99695`<br/>`#fbca04`<br/>`#ff7619` | Other: "cleanup", "performance", "refactoring", "technical debt"
![](https://dummyimage.com/100x20/bfe5bf&amp;text=+)<br/>![](https://dummyimage.com/100x20/bcf5db&amp;text=+) | `#bfe5bf`<br/>`#bcf5db` | Testing and tools: "test", "developer", "tools"
![](https://dummyimage.com/100x20/009688&amp;text=+)<br/>![](https://dummyimage.com/100x20/33a69a&amp;text=+)<br/>![](https://dummyimage.com/100x20/66c6ac&amp;text=+) | `#009688`<br/>`#33a69a`<br/>`#66c6ac` | Types
![](https://dummyimage.com/100x20/5a8cbf&amp;text=+)<br/>![](https://dummyimage.com/100x20/6fa1d4&amp;text=+)<br/>![](https://dummyimage.com/100x20/84b6eb&amp;text=+) | `#5a8cbf`<br/>`#6fa1d4`<br/>`#84b6eb` | Scope - Set 1
![](https://dummyimage.com/100x20/6e5d9a&amp;text=+)<br/>![](https://dummyimage.com/100x20/8f7bb3&amp;text=+)<br/>![](https://dummyimage.com/100x20/b4a8d1&amp;text=+) | `#6e5d9a`<br/>`#8f7bb3`<br/>`#b4a8d1` | Scope - Set 2

### References

Thanks for the inspiration to the following resources:

- https://github.com/apache/pulsar/issues/21883
- https://github.com/ManageIQ/guides/blob/master/labels.md

## About

### Author
**Stefan Walther**

* [github.com/stefanwalther](http://github.com/stefanwalther) 
* [LinkedIn](https://www.linkedin.com/in/stefanwalther/) 

### License
MIT

***

_This file was generated by [verb-generate-readme](https://github.com/verbose/verb-generate-readme), v0.8.0, on November 22, 2024._

