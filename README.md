# ITT

| Short | Explainer |
| :---- | :-------- |
| I =   | Issue     |
| T =   | Template  |
| T =   | Testing   |

The issue templates located in .github/ISSUE_TEMPLATE are in design for
https://github.com/mitchellkrogza/Phishing.Database


Remember to replace 

https://github.com/spirillen/ITT with
https://github.com/mitchellkrogza/Phishing.Database in 
`.github/ISSUE_TEMPLATE/falsepositive.yml`


```shell
sed -i 's/mitchellkrogza\/Phishing\.Database/spirillen\/ITT/g' \
    .github/ISSUE_TEMPLATE/falsepositive.yml
```
