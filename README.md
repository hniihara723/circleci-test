# circleci-demo

# settings
Running Jobs Locally CircleCI 2.1

# build

```
Circle ci local では2.1 対応していない　下記手段で回避
https://qiita.com/keiichi4e/items/433b613f592e7869ca9b
$ circleci config process .circleci/config.yml > process.yml
$ circleci local execute -c process.yml
```
