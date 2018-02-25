# Travis CI Lab

## Run the Console App
Try out the console app, see if you can break it and where the weaknesses in the code are.

## Set up Travis CI to build the Console App


## Implement the Power method
Once Travis CI is up and running, it should rebuild every time you push a change. Go ahead and implement the `Power` method found in `Program.cs`.
Run the app to test it out your change.
Commit and push the change to a different branch.
Open a new pull request.
See if Travis CI started building your pull request.
Once the build completes, merge your pull request with master.
See if Travis CI started building master.

## Set up Travis CI to run Unit Tests


## Implement the other unit tests
Follow the same format at the addition unit tests, and implement the other operations, including the power method you implemented before.
Run the tests locally, and intentionally make one fail.
Commit and push the changes to a different branch.
Open a new pull request.
See if Travis CI will detect the failed test.
Push a change on the same branch to fix the test.
See if the build completes successfully.
Merge the pull request if it does, fix it otherwise.