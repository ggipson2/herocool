Based on: https://www.youtube.com/watch?v=zhJLVFR3pE8
Code: https://github.com/beaucarnes/herocool 

[Pulumi docs](https://www.pulumi.com/docs/?_gl=1*12pljzh*_ga*MjAwMTU1NjkxLjE2NTUyMjk1NDg.*_ga_FQHG5CVY2D*MTY1NTIzNjU5Ny4yLjEuMTY1NTIzNzcwMi42MA..&_ga=2.265266439.944888450.1655229548-200155691.1655229548#documentation)

## Setup

```
export AWS_PROFILE=ggipson2

brew install pulumi
pulumi new --force

venv/bin/pip install flask requests
venv/bin/flask run
```