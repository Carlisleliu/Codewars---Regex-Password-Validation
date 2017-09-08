# Codewars---Regex-Password-Validation

```
function validate(password) {
  return /^\w*(?=.{6,})(?=\w*[a-z])(?=\w*[A-Z])(?=\w*\d)\w*$/.test(password);
}
```
