# gzhu-jdsd-helper

How to easily earn 1 credit of yours? -- 广州大学经典棒读

## How to use

First, you should get `key` from the request to WeChat MiniProgram 广州大学经典诵读 by using fiddler.

Then, if you run locally, you should put your key in file `./src/config.ts` and execute command `yarn start`

Or if you run with GitHub Action, you should just set a secret named `jdsd_key` with your `key` as its value. (The workflow runs **every day at 7:00 CST**)

## Todo

- [x] ~~Daily sign-in~~
- [x] ~~Daily practice~~
- [x] ~~Daily reading~~
- [ ] Error handling
- [ ] PVP
