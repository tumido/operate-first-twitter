# operate-first-twitter

This repository will be used to publish tweets using the [twitter-together](https://github.com/gr2m/twitter-together) GitHub Action to the Operate First Twitter [Account](https://twitter.com/OperateFirst). Using this GitHub repository and pull request reviews as a workflow, we can collaboratively tweet from the shared twitter account.

## How to Tweet?

To create a new tweet send a PR to the repo with a new tweet.

<kbd>[Create new tweet](../../new/main/?filename=tweets/<your-path>.tweet)</kbd>

Create a new file in `tweets/hello-world.tweet` with the content

> Hello, world!

Name the tweet as `short-tweet-name.tweet` and add it to the monthly directory such as `2021-04` in the `tweets` folder,
e.g. `tweets/2021-04/yt-espresso.tweet`.

Once the Pull Request is Merged, a Github Action should be triggered which will publish the tweet.

For more information on the tweeting process go [here](tweets/README.md).
