<!--
  Niche Back-End PR Template

  Don't forget to tag your PR with the BACK_END label.
-->

<!-- CC relevant team members -->

### Dependencies

<!-- Does this PR depend on other PRs (same service, other services, libraries)? If so, link them here.
  If this PR is branched from another PR, change the base branch for ease of review. -->

### Documentation

<!-- Link(s) to documentation relevant to the work, such as issues, Jira work items, etc. -->

### Description

<!-- A plain-English overview of the work involved in this PR. -->

### Testing Considerations

<!-- Any specific testing considerations for this PR: dependencies, sample UUIDs, test data etc. -->

<!-- If this PR will not be tested by a QE, remember to add the "NO QA" label. -->

### SQL Migrations

<!-- Does this PR add PII to a new table? Consult Data Privacy Compliance: https://bookstack.niche.team/books/back-end-patterns-practices/page/data-privacy-compliance -->

<!-- Uncomment and fill in this section if both of the following are true:

  1. This PR adds a new table or a new column with a default value
  2. Your team or another team needs these schema changes to be reflected in Snowflake

Migration script: <link to migration script file>

Description: <a description of the schema changes made by this migration script>

Notice for the Data Engineering team: @nicheinc/data-engineering
-->

### Deployment

<!-- Any deployment considerations for this PR, including dependencies, necessary order of operations, etc. -->

<!-- Does this PR represent a new back-end component that has never been deployed before? Consult the Production Readiness Checklist: https://docs.google.com/document/d/1MUjrz0m-zbTc4wmvxdmbCm6B2ML8fAluU7u9CqLSG9g/edit -->

<!-- If assistance is required from infrastructure (e.g. deploying a new service) consider submitting a Reliability Request: https://nicheinc.atlassian.net/servicedesk/customer/portal/2/group/6/create/18 -->

<!-- Only check the following box after verifying that this PR requires no additional manual testing before deployment and that any deployment dependencies have already been resolved. -->

- [ ] Deploy to production automatically upon successful API Proctor tests

### Versioning

<!-- Indicate whether this is a Major, Minor, or Patch bump and explain why. -->
