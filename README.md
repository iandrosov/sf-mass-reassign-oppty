# sf-mass-reassign-oppty
## Overview
Salesforce mass reassign opportunities without Modify-All data permission on user. Intended for ANT deployment and includes `build.xml` and all required Unit tests and code coverage.

## Lightning & VisualForce
This utility provide simple UI app in VisualForce and APEX to allow users to mass reassign opportunities. Support Lightning Design System by using `lightningStyleSheets="true"`.

## Reason for this utility
Lightning and several packages do support mass-reassign feature out of the box. However, users doing this action require super powers of Admin access or View and Modify All Data permission. This is not ideal or possible in many ORG situations.

Example is ORG where managers in call center cannot have View/Modify All data, it is resticted. But need to reassign Opportunities in mass to other agents or even outside their team in case person left or on vacation.

This utility provide this feature.

## Unit tests
Basic unit test is included in this repository. This test requires to create an opportunity and we used dev org with simplified requirement.
This may not be realistic for complex orgs with complex Oppty process, custom field requirements or reocrd types. Depending on your org Oppty complexity unit test will need ot be updated to match the ORG.
