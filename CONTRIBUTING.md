# Contributing

## Task

### Command word should be scoped to the command node

Why? the same word can be:

* a command
* or an argument

ie a command can have a command but the parser should parse only
the words not captured by the parent.

Example: `tabul app xxx` is a command but may be also an argument `tabul connection info app`

# Dev Conventions

* Boolean Setter Name (setHasValue or setIsType)
* Boolean Getter Name (hasValue or isValue)
* One test file per feature
