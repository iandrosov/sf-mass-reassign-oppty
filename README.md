# sf-mass-reassign-oppty
Salesforce mass reassign opportunities without Modify-All data permission on user. Intended for ANT deployment and includes `build.xml` and all required Unit tests and code coverage.

This utility provide simple UI app in VisualForce and APEX to allow users to mass reassign opportunities. Support paginations and mass count of selected oppty.

Lightning and several packages now support mass reassign feature out of the box. However, users doing this require super powers of Admin access or min View and Modify All Data permission. This is not ideal or possible in many ORG use cases.

Example is ORG where say managers in call center cannt have View/Modify All data, it is resticted. But need to reassign Opportunities in mass to other agents or even outside their team in case person left or on long vacation.

This utility provide this feature.
