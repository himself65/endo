# Snapshot report for `test/test-policy.js`

The actual snapshot is saved in `test-policy.js.snap`.

Generated by [AVA](https://avajs.dev).

## policy - insufficient policy detected early / loadLocation

> Snapshot 1

    'Package "alice>carol" is allowed for "alice" to import but its policy is not defined. Please add a policy for "alice>carol"'

## policy - insufficient policy detected early / importLocation

> Snapshot 1

    'Package "alice>carol" is allowed for "alice" to import but its policy is not defined. Please add a policy for "alice>carol"'

## policy - insufficient policy detected early / makeArchive / parseArchive

> Snapshot 1

    'Package "alice>carol" is allowed for "alice" to import but its policy is not defined. Please add a policy for "alice>carol"'

## policy - insufficient policy detected early / makeArchive / parseArchive with a prefix

> Snapshot 1

    'Package "alice>carol" is allowed for "alice" to import but its policy is not defined. Please add a policy for "alice>carol"'

## policy - insufficient policy detected early / writeArchive / loadArchive

> Snapshot 1

    'Package "alice>carol" is allowed for "alice" to import but its policy is not defined. Please add a policy for "alice>carol"'

## policy - insufficient policy detected early / writeArchive / importArchive

> Snapshot 1

    'Package "alice>carol" is allowed for "alice" to import but its policy is not defined. Please add a policy for "alice>carol"'

## policy - malfunction resulting in missing compartment / loadLocation

> Snapshot 1

    'Failed to load module "./index.js" in package "file://.../compartment-mapper/test/fixtures-policy/node_modules/app/" (1 underlying failures: Cannot import from missing compartment "file://.../compartment-mapper/test/fixtures-policy/node_modules/alice/node_modules/carol/" (Package "carol" is missing. Are you sure there is an entry in policy resources specified for it?)'

## policy - malfunction resulting in missing compartment / importLocation

> Snapshot 1

    'Failed to load module "./index.js" in package "file://.../compartment-mapper/test/fixtures-policy/node_modules/app/" (1 underlying failures: Cannot import from missing compartment "file://.../compartment-mapper/test/fixtures-policy/node_modules/alice/node_modules/carol/" (Package "carol" is missing. Are you sure there is an entry in policy resources specified for it?)'

## policy - malfunction resulting in missing compartment / makeArchive / parseArchive

> Snapshot 1

    'Failed to load module "./index.js" in package "file://.../compartment-mapper/test/fixtures-policy/node_modules/app/" (1 underlying failures: Cannot import from missing compartment "file://.../compartment-mapper/test/fixtures-policy/node_modules/alice/node_modules/carol/" (Package "carol" is missing. Are you sure there is an entry in policy resources specified for it?)'

## policy - malfunction resulting in missing compartment / makeArchive / parseArchive with a prefix

> Snapshot 1

    'Failed to load module "./index.js" in package "file://.../compartment-mapper/test/fixtures-policy/node_modules/app/" (1 underlying failures: Cannot import from missing compartment "file://.../compartment-mapper/test/fixtures-policy/node_modules/alice/node_modules/carol/" (Package "carol" is missing. Are you sure there is an entry in policy resources specified for it?)'

## policy - malfunction resulting in missing compartment / writeArchive / loadArchive

> Snapshot 1

    'Failed to load module "./index.js" in package "file://.../compartment-mapper/test/fixtures-policy/node_modules/app/" (1 underlying failures: Cannot import from missing compartment "file://.../compartment-mapper/test/fixtures-policy/node_modules/alice/node_modules/carol/" (Package "carol" is missing. Are you sure there is an entry in policy resources specified for it?)'

## policy - malfunction resulting in missing compartment / writeArchive / importArchive

> Snapshot 1

    'Failed to load module "./index.js" in package "file://.../compartment-mapper/test/fixtures-policy/node_modules/app/" (1 underlying failures: Cannot import from missing compartment "file://.../compartment-mapper/test/fixtures-policy/node_modules/alice/node_modules/carol/" (Package "carol" is missing. Are you sure there is an entry in policy resources specified for it?)'

## policy - attack - browser alias / loadLocation

> Snapshot 1

    'Failed to load module "./attack.js" in package "file://.../compartment-mapper/test/fixtures-policy/node_modules/app/" (1 underlying failures: Cannot import from missing compartment "file://.../compartment-mapper/test/fixtures-policy/node_modules/hackity/" (Package "dan" resolves to "." in "file://.../compartment-mapper/test/fixtures-policy/node_modules/hackity/" which seems disallowed by policy. There is likely an override defined that causes another package to be imported as "dan".)'

## policy - attack - browser alias / importLocation

> Snapshot 1

    'Failed to load module "./attack.js" in package "file://.../compartment-mapper/test/fixtures-policy/node_modules/app/" (1 underlying failures: Cannot import from missing compartment "file://.../compartment-mapper/test/fixtures-policy/node_modules/hackity/" (Package "dan" resolves to "." in "file://.../compartment-mapper/test/fixtures-policy/node_modules/hackity/" which seems disallowed by policy. There is likely an override defined that causes another package to be imported as "dan".)'

## policy - attack - browser alias / makeArchive / parseArchive

> Snapshot 1

    'Failed to load module "./attack.js" in package "file://.../compartment-mapper/test/fixtures-policy/node_modules/app/" (1 underlying failures: Cannot import from missing compartment "file://.../compartment-mapper/test/fixtures-policy/node_modules/hackity/" (Package "dan" resolves to "." in "file://.../compartment-mapper/test/fixtures-policy/node_modules/hackity/" which seems disallowed by policy. There is likely an override defined that causes another package to be imported as "dan".)'

## policy - attack - browser alias / makeArchive / parseArchive with a prefix

> Snapshot 1

    'Failed to load module "./attack.js" in package "file://.../compartment-mapper/test/fixtures-policy/node_modules/app/" (1 underlying failures: Cannot import from missing compartment "file://.../compartment-mapper/test/fixtures-policy/node_modules/hackity/" (Package "dan" resolves to "." in "file://.../compartment-mapper/test/fixtures-policy/node_modules/hackity/" which seems disallowed by policy. There is likely an override defined that causes another package to be imported as "dan".)'

## policy - attack - browser alias / writeArchive / loadArchive

> Snapshot 1

    'Failed to load module "./attack.js" in package "file://.../compartment-mapper/test/fixtures-policy/node_modules/app/" (1 underlying failures: Cannot import from missing compartment "file://.../compartment-mapper/test/fixtures-policy/node_modules/hackity/" (Package "dan" resolves to "." in "file://.../compartment-mapper/test/fixtures-policy/node_modules/hackity/" which seems disallowed by policy. There is likely an override defined that causes another package to be imported as "dan".)'

## policy - attack - browser alias / writeArchive / importArchive

> Snapshot 1

    'Failed to load module "./attack.js" in package "file://.../compartment-mapper/test/fixtures-policy/node_modules/app/" (1 underlying failures: Cannot import from missing compartment "file://.../compartment-mapper/test/fixtures-policy/node_modules/hackity/" (Package "dan" resolves to "." in "file://.../compartment-mapper/test/fixtures-policy/node_modules/hackity/" which seems disallowed by policy. There is likely an override defined that causes another package to be imported as "dan".)'

## policy - attenuator error aggregation / loadLocation

> Snapshot 1

    'Globals attenuation errors: Error while attenuating globals for "alice" with "myattenuator": "I attenuate, I throw.", Error while attenuating globals for "carol" with "myattenuator": "I attenuate, I throw.", Error while attenuating globals for "app" with "myattenuator": "I attenuate, I throw."'

## policy - attenuator error aggregation / importLocation

> Snapshot 1

    'Globals attenuation errors: Error while attenuating globals for "alice" with "myattenuator": "I attenuate, I throw.", Error while attenuating globals for "carol" with "myattenuator": "I attenuate, I throw.", Error while attenuating globals for "app" with "myattenuator": "I attenuate, I throw."'

## policy - attenuator error aggregation / makeArchive / parseArchive

> Snapshot 1

    'Globals attenuation errors: Error while attenuating globals for "alice" with "myattenuator": "I attenuate, I throw.", Error while attenuating globals for "app" with "myattenuator": "I attenuate, I throw.", Error while attenuating globals for "carol" with "myattenuator": "I attenuate, I throw."'

## policy - attenuator error aggregation / makeArchive / parseArchive with a prefix

> Snapshot 1

    'Globals attenuation errors: Error while attenuating globals for "alice" with "myattenuator": "I attenuate, I throw.", Error while attenuating globals for "app" with "myattenuator": "I attenuate, I throw.", Error while attenuating globals for "carol" with "myattenuator": "I attenuate, I throw."'

## policy - attenuator error aggregation / writeArchive / loadArchive

> Snapshot 1

    'Globals attenuation errors: Error while attenuating globals for "alice" with "myattenuator": "I attenuate, I throw.", Error while attenuating globals for "app" with "myattenuator": "I attenuate, I throw.", Error while attenuating globals for "carol" with "myattenuator": "I attenuate, I throw."'

## policy - attenuator error aggregation / writeArchive / importArchive

> Snapshot 1

    'Globals attenuation errors: Error while attenuating globals for "alice" with "myattenuator": "I attenuate, I throw.", Error while attenuating globals for "app" with "myattenuator": "I attenuate, I throw.", Error while attenuating globals for "carol" with "myattenuator": "I attenuate, I throw."'
