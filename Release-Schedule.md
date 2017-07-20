# Schedule
**First Saturday of each month**: Release branch gets created. Push the release branch onto a test server.
Features merged into `develop` after this date will only go out in the following release.

**Between first and second Saturday of each month**: The release team will focus on testing and bug fixes. By Tuesday, testing should be completed by two members of the team. By Saturday, any bugfixes should be done.

**Second Sunday of each month**: The release will be made and an update will be pushed to the live site.

# Instructions for fixing release bugs
1. Make a branch off of `develop`, and fix the bug.
1. Apply the label [PR: for current release](https://github.com/oppia/oppia/labels/PR%3A%20for%20current%20release) to PRs containing bugfixes that need to go into the current release.
1. When the PR has been cherry-picked onto the release branch, apply the label [PR: released](https://github.com/oppia/oppia/labels/PR%3A%20released). (Xinyu will do this step.)

# Release team members and responsibilities
**Jacob**
- Test new features in the release
- Additional ad-hoc testing

**Arunabh**
- Test core UI elements
- Fix bugs found in the testing process, or decide to file them as issues.

**Xinyu**
- 1 week before the release, make the release branch, and create the changelog and send it to the rest of the release team
- 1 week before the release, deploy the release branch to the test server. Re-deploy if bug fixes happen on the release branch.
- Deploy the release to production.
- Test migrations and other release-specific things.
- Make sure all the testing feedback is either fixed or filed as issues.
- Fix bugs that arise in the release testing process. 