<!--
  Niche Engage Release PR Template

  Don't forget to tag your PR with everyone who needs to review the commits they've added to this release.
-->

## [INSERT TITLE]

<!-- Does this PR depend on other PRs (same service, other services, libraries)? If so, link them here. If this PR is branched from another PR, change the base branch for ease of review. -->

### Pre Release Action Items

<!-- List out any steps required before this release can be merged and deployed to production.
    Ex: pre-release requirements, testing specific regressions, adding env vars to aws, etc.
 -->

### Post Release Action Items

<!-- List out any steps required before this release can be merged and deployed to production.
    Ex: Customer/stakeholder updates, FTs getting switched on/off, migrations to run, etc.
 -->

### Commits in this Release

<!-- Generate a list of each of the commits included in this PR alongside the corresponding
      PR's that generated them + their JIRA tickets, if applicable -->

<!-- To generate this log, run the following command with the release branch checked out:
       git log origin/production..$(git rev-parse --abbrev-ref HEAD) --format='%h - %ad - %s %aN' --date=format:'%b %d %Y' | tac | sed 's/^/- /'
-->

### Versioning

<!-- Indicate whether this is a Major, Minor, or Patch bump and explain why. -->

### AI Usage

<!-- Describe to what extent, if any, AI was used in the creation of this PR. This might include planning, e.g. "I asked Claude for advice", or direct input, e.g. "This function was written by Cursor". Remember, you're attaching *your* name to this PR -- if *you* don't understand what you're submitting, you're passing the burden of knowledge onto those reviewing (or debugging) in the future instead. -->