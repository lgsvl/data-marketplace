# Contribution guide
The data marketplace team accepts contributions from any interested parties using GitHub pull requests on each service repository.
Pushing to master is not allowed in any of the repositories. Any direct push to master might interfere with our CI process.

If you want to make a change, create your own branch out of `dev` branch of the service repository you want to change , make your changes. Once you are done, submit a pull request to the `dev` branch. When accepted, the changes will make their way into `master` after we merge it.

Verify your changes before submitting a pull request by running the unit, integration and acceptance tests of the service when available. See the testing section for details in each repository. In addition, make sure that your changes are covered by existing or new unit testing.

# Build prerequisites and testing steps
The build prerequesites, build steps and test steps are described in each repository that are part of the data marketplace project.

# Squash and merge

Upon the merge (by either you or your reviewer), all commits on the review branch must represent meaningful milestones or units of work. Use commit message to detail the development and review process.
Before merging a PR, squash any fix review feedback, typo, and rebased sorts of commits.