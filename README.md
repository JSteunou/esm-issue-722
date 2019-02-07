Simple repro repo to prove https://github.com/standard-things/esm/issues/722

```sh
git clone https://github.com/JSteunou/esm-issue-722.git
cd esm-issue-722
npm i
# fail
npm test
# success
npm start
npm i esm@3.0.84
# success
npm test
# success
npm start
```
