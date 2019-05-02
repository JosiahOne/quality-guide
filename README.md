# quality-guide
While working on personal projects (and some work projects), I generally find myself in a predicament: I know testing, consistent code style guidelines, etc. are important, but I don't have any authorities of which to delegate these policies. Instead, I just "pick something".

This is perfectly fine, but consistency is a desirable property to me. To this end, I have created this document which describes *a* set of rules so I don't have to think about them anymore. The guide is broken down by language and in each section I try to define:

1. What code style guideline to follow
2. What kind of quality testing is expected, and what tools should be used
3. What kind of security testing is expected, and what tools should be used

## Javascript

### Code Style
Just use StandardJS: https://standardjs.com/

Tip: You can add `/* global VarName */` to define a variable that is expected to be imported.

Tip: You can add `// eslint-disable-line no-unused-vars` to lines that define classes to be used externally.
