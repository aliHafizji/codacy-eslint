When it comes to naming variables, styleguides generally fall into one of two camps: camelcase (variableName) and underscores (variable_name). This rule focuses on using the camelcase approach. If your styleguide calls for camelcasing your variable names, then this rule is for you!
This rule looks for any underscores (_) located within the source code. It ignores leading and trailing underscores and only checks those in the middle of a variable name. If ESLint decides that the variable is a constant (all uppercase), then no warning will be thrown. Otherwise, a warning will be thrown. This rule only flags definitions and assignments but not function calls.
This rule accepts a single options argument with the following defaults:

```
http://eslint.org/docs/rules/camelcase
```

[Source](http://eslint.org/docs/rules/camelcase)