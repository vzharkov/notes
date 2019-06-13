# Replace in one text with other in current directory

```bash
find . -type f -print0| xargs -0 sed -i 's/FactoryGirl/FactoryBot/g'
```
