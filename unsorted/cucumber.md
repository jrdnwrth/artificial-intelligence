Cucumber (AKA Examples)
=======================

Cucumber is a ruby gem to help write tests.

Each test is composed of these simple sections:

1. Given (Some state)
1. When (Some action (AKA "Cause"))
1. Then (Some result (AKA "Effect"))

For Examples

```
Given user is "admin" AND page is "Permissions"
When user clicks "Save"
Then page result == "Save Successful"
```