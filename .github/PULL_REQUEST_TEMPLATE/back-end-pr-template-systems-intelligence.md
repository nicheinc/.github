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

### QA Handoff Checklist

<!-- Set of steps to take to verify that this PR is in fact ready to hand off to QA. -->

- [ ] Acceptance Criteria are correct
- [ ] Acceptance Criteria are being met
  - [ ] AC1
  - [ ] AC2
  - [ ] ...
- [ ] Pull Request is linked to Asana task
- [ ] Other teams who might be affected by the changes have been notified and
      offered a chance to CR
- [ ] All appropriate automated Github checks pass
- [ ] All the relevant `api-proctor` suites pass
- [ ] Any new features requiring automation coverage are either
  - [ ] covered in an `api-proctor` PR here:
  - [ ] documented on the
        [Indigo Automation Backlog](https://app.asana.com/0/1204031336473161/list)
  - [ ] documented on the
        [SEIT Backlog](https://app.asana.com/0/1202082245735211/list)
  - [ ] PR contains no new features
- [ ] There are no oustanding merge conflicts with dev

### Deployment

<!-- Any deployment considerations for this PR, including dependencies, necessary order of operations, etc. -->

<!-- Does this PR represent a new back-end component that has never been deployed before? Consult the Production Readiness Checklist: https://docs.google.com/document/d/1MUjrz0m-zbTc4wmvxdmbCm6B2ML8fAluU7u9CqLSG9g/edit -->

<!-- If assistance is required from infrastructure (e.g. deploying a new service) consider submitting a Reliability Request: https://nicheinc.atlassian.net/servicedesk/customer/portal/2/group/6/create/18 -->

### Versioning

<!-- Indicate whether this is a Major, Minor, or Patch bump and explain why. -->
