prowl
=====

Main Container Repository for Prowl

[![Build Status](https://api.shippable.com/projects/53f9b27ccaca7d3b06a0f3ae/badge/beta)](https://www.shippable.com/projects/53f9b27ccaca7d3b06a0f3ae)

Commit Message Format:
type(scope): Description

Line Items

Footer
Tickets

type can be one of:
- feat
- fix
- docs
- style
- refactor
- test
- chore

scope should be what part of the code base the change is in

Line items are a descriptions of the individual changes and how it contrasts with previous behavior

Footer Must include all breaking changes i.e.
Breaking Changes: You now must include an auth token for all api requests before some endpoints didn't require it

Tickets should be on a separate line after the footer and should be in the format
[Delivers #12345] - this is for delivers
[Fixes #13494] - this is for fixes
[#94820] - this is for references
Closes #93023 - this is for after they have been accepted and closed and will almost always be in the merges and simply
adds a reference to the changelog

Possible Integrations:
Swagger - This is for documenting the API
codereviewhub - For code review workflow
docker - For running the code in a static environment
email - For notifications and alerts
hipchat - For notifications and alerts
text messages - For notifications and alerts
pivotal tracker - Issue tracking and agile project management
trello - this will take a custom integration but it's a hell of a lot better than working with pivotal
shippable.com - Continuous Integration / Deployment
vagrant - To ensure the development environments match the server environments

Output default should be hal+json
