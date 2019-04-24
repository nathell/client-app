# Client app

In order to contribute to this open source repository, ensure the following:

1. Fork this repository
2. Add this repository as `upstream` with `git remote add upstream git@github.com:test-org-integration/client-app.git`
2. In your fork, ensure that your local master branch is **always** up to date with this repository master branch.
This comes for free when you fork the repository. If not, give 

   ```git fetch upstream && git checkout master && git reset --hard upstream/master```

3. Checkout a new branch and add your commits there.
4. When you are ready, open a PR in this repository.
4. When you are changes are deemed ok, a maintainer will comment the PR with `OK TO MERGE`. That will trigger out automated pipelines and your commit will make it upstream to our private server.
5. When your changes are merged, you will receive a comment in your PR. After that ensure that your `master` branch is up to date with the master of this repo, by repeating step 2.
