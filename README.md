# Linear History Example

Example of force linear history setting in GitHub. In a GitOps setup, this is useful to prevent merge commits from being added to the history.

![Linear History](./images/requireLinearHistory.png)

When you create a PR from lab to dev you want the _dev_ branch rebased on top of _lab_. Unfortunatley fast forwarding is not possible in regular GH PRs. This is where the _fast forward_ GH action comes in.