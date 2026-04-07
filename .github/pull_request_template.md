<!-- Niche Back-End PR Template -->

<!-- CC relevant team members -->

### Dependencies

<!-- Does this PR depend on other PRs (same service, other services, libraries)? If so, link them here. If this PR is branched from another PR, change the base branch for ease of review. -->

### Documentation

<!-- Link(s) to documentation relevant to the work, such as issues, Jira work items, etc. -->

### Description

<!-- A plain-English overview of the work involved in this PR. -->

### Testing Considerations

<!-- Any specific testing considerations for this PR: dependencies, sample UUIDs, test data etc. -->

### SQL Migrations

<!-- Does this PR add PII to a new table? Consult Data Privacy Compliance: https://nicheinc.atlassian.net/wiki/spaces/tech/pages/347930667/Data+Privacy+Compliance -->

<!-- If this PR contains a schema migration that needs to be reflected in Snowflake, please submit a PDO Service Desk request (https://nicheinc.atlassian.net/servicedesk/customer/portal/3/group/7/create/332). Be sure to include a link to your PR and schema migration files, along with a description of the schema changes. -->

### Deployment

<!-- Any deployment considerations for this PR, including dependencies, necessary order of operations, etc. -->

<!-- Does this PR represent a new back-end component that has never been deployed before? Consult the Production Readiness Checklist: https://docs.google.com/document/d/1MUjrz0m-zbTc4wmvxdmbCm6B2ML8fAluU7u9CqLSG9g/edit -->

<!-- If assistance is required from infrastructure (e.g. deploying a new service) consider submitting a Reliability Request: https://nicheinc.atlassian.net/servicedesk/customer/portal/2/group/6/create/18 -->

<!-- If no more manual testing is required before deployment, you may add the deploy-automatically label to run API Proctor tests in stage and deploy to production if all tests pass. -->

### Versioning

<!-- Indicate whether this is a Major, Minor, or Patch bump and explain why. -->

### AI Usage

<!-- Describe to what extent, if any, AI was used in the creation of this PR. This might include planning, e.g. "I asked Claude for advice", or direct input, e.g. "This function was written by Cursor". Remember, you're attaching *your* name to this PR -- if *you* don't understand what you're submitting, you're passing the burden of knowledge onto those reviewing (or debugging) in the future instead.-->