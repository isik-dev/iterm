> A toy iterm conf

```bash
# 1. cd into conf
cd /Users/yourname/.config

# 2. clone the repo 
git clone https://github.com/isik-dev/iterm.git

# 3. update with your username
cd iterm && sed -i '' 's|/Users/[^/]*|/Users/yourname|g' itermconf.json
```
