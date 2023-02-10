# arminms.github.io
This is a repository that generates my personal web page.

## Prerequisites
- Go language 1.18 or higher (require for hugo modules)
- Node version v18.x or later and npm 8.x or later
- Hugo Version 0.109.0 (extended) or higher

## Setup
```
git clone git@github.com:arminms/arminms.github.io.git
cd arminms.github.io
hugo mod init --config config.init.toml github.com/arminms/arminms.github.io
hugo mod tidy
hugo mod npm pack
npm install
hugo server -w
```
