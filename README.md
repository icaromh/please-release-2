# release-test

```sh
release-please bootstrap \
  --token=$GH_TOKEN \
  --repo-url=icaromh/release-test \
  --release-type=node \
  --changelog-type=github \
  --label=""
```


```
release-please github-release \
  --token=$GITHUB_TOKEN
  --repo-url=<owner>/<repo> [extra options]

```