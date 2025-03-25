# Explain CSS Specificity

If an HTML element is styled using multiple selectors, the style with the highest specificity will be applied.

## Example css Specificity

### [GitHub link](https://github.com/alifrayhan1/cssassignment/blob/main/Question4/answer.md)

### [live link](https://phenomenal-daffodil-653ef6.netlify.app/)

CSS specificity basically works using a point system. When multiple CSS rules are applied to a particular element, the browser calculates the specificity score to decide which rule will be applied.


| Example                           | Specificity Score |
| --------------------------------- | ----------------- |
| `<h1 style="color: red;">`        | 1000              |
| `#myId`                           | 100               |
| `.myClass, [type="text"], :hover` | 10                |
| `h1, ::before`                    | 1                 |
| ` * `                             | 0                 |
| ` user agent stylesheet `         | score < 0         |
