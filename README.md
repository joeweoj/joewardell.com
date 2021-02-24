# joewardell.com

## prerequisites

1. Install [Hugo](https://gohugo.io/getting-started/quick-start/)
1. Clone this repo `git clone --recurse-submodules`
1. `cd joewardell.com/joewardell`

## build

1. `hugo -D`

## deploy

1. `aws s3 cp public s3://joewardell.com --recursive --acl public-read`
