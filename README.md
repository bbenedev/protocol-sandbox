# protocol-sandbox

Demo repository for [PRotocol](https://github.com/bbenedev/PRotocol). The default branch requires
a check named `test`, which fails when `result.txt` contains the word `fail`. Each open pull
request shows one situation:

| Pull request | Situation |
|---|---|
| `demo/passing` | The required check passed on the current commit |
| `demo/failing` | The required check failed |
| `demo/stale` | The check passed on an earlier commit; the latest push has no result |
| `demo/draft` | Draft pull request |

Try it: `protocol list -R bbenedev/protocol-sandbox`
