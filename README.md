# Awesome Job Hunting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of tools and resources that help people find jobs and manage their applications.

## Contents

- [Job search and application management](#job-search-and-application-management)
- [Data sources](#data-sources)
- [Standards and protocols](#standards-and-protocols)

## Job search and application management

- [JobOps](https://github.com/DaKheera47/job-ops) - Self-hosted job search and application tracker that searches multiple boards, helps tailor CVs, and tracks replies. Useful for managing the search through to follow-up while submitting applications yourself.
- [freehire](https://freehire.me) - Open-source job search engine that aggregates postings from job boards and company ATS boards into one deduplicated catalogue, then derives structured filters from the posting text — seniority, remote policy, skills, visa sponsorship, relocation, security clearance — so hard eligibility can be filtered on instead of read out of each description. Search, company data and the documented REST API work without an account. Useful for ruling out ineligible roles before applying, and as a free job data API; it is also an OJCP provider, so agents can reach the same catalogue through that standard.

## Data sources

- [ATS Company Directory sample](https://github.com/neorhapsody/ats-company-directory-sample) - Free CSV of 50 companies mapped to their Greenhouse, Lever, Ashby, Workable or Recruitee job board, with each board's public JSON jobs endpoint, open and remote job counts, and whether it publishes salary ranges. Useful for checking employers' own job boards directly and building your own new-job alerts. CC BY 4.0; the full 7,977-company directory is paid.

## Standards and protocols

- [OJCP (Open Job Context Protocol)](https://ojcp.dev) - An open standard for agent-consumable job data, built on the Model Context Protocol. Lets AI agents discover jobs, read employer context, and submit applications through one uniform interface instead of scraping each site, with optional verifiable agent identity so providers can tell a real agent from a scraper. Useful for developers building job-search agents and for job boards or employers that want their listings reachable by them.

## Contributing

Suggestions are welcome. See [the contribution guidelines](CONTRIBUTING.md) for the scope and submission criteria.

This list is currently maintained by the creator of JobOps, its first entry. Entries are assessed for usefulness and fit regardless of affiliation.
