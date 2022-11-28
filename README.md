# lab-44

## Fit Buddy Refactor - 5 whys

- Why - The conditional lines were redundant
- Why - Because we can use the @NotNull annotations for the parameter
- Why - It would have the same declaration as the deleted line
- Why - We want to indicate we must never call the method with a null if we to avoid an exception
- Why - Refactoring would make the code be more readable, maintainable and mitigate exception and syntax errors


- [FitBuddy Repo PR](https://github.com/mepox/fitbuddy/pull/162)

### Group Members

- Maximo VincenteMejia
- Mathew Torres