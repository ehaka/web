# ehaka.github.io

Code and content for a personal academic website.
The academic theme for Hugo is courtesy of [George Cushen](https://georgecushen.com).

## Setup
### Go
https://go.dev/dl/

### Hugo
```bash
git clone https://github.com/gohugoio/hugo.git
cd hugo
go install
```

### Repos
Check github ssh keys
```bash
git clone git@github.com:ehaka/web.git
cd web
git submodule init
git submodule update
```

#### If public submodule breaks
```bash
git clone git@github.com:ehaka/ehaka.github.io.git public
```

### Build/test
```bash
hugo server
```

### Update
Edit markdown files in content, add documents such as .pdf to static.
Publish with deploy script. 
