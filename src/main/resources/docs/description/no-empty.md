Empty statements usually occur due to refactoring that wasn't completed, such as:
Empty block statements such as this are usually an indicator of an error, or at the very least, an indicator that some refactoring is likely needed.
This rule is aimed at eliminating empty block statements. While not technically an error, empty block statements can be a source of confusion when reading code. A block will not be considered a warning if it contains a comment line.

```
if (foo) {
}

```

[Source](http://eslint.org/docs/rules/no-empty)