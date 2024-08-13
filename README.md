# Getting Started

This repository has a job that checks code.
It uses both <https://github.com/actions/checkout> and
<https://github.com/super-linter/super-linter>

The checkout checks your code for any obvious errors missed by the GitHub compiler
and the superlinter makes sure that your code conforms to the industry standard

## How to use

All you have to do is to git push or commit any changes done to a branch and the superlinter.yaml
file will run and check for any errors in your code. If there's a failure then the linter will
stop you from comitting the file. The linter will notify you by email if your code has not passed
the checkout and the superlinter.
