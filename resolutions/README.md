# TODO Group Resolution Process

This process is designed to allow members of the TODO Group to propose actions to be
considered by the Steering Committee, for the Steering Committe to review and discuss
them, and for actions taken by the Steering Committee to be documented.

## Proposing a resolution

### Summary

1. Update [numbers.md](numbers.md)
1. Copy [resolution template](template/standard) into `proposed`
1. Send PR (or add to existing PR if applicable)

### Details

Fork this repository, and copy the [resolution template](template/standard.md) into a new
file in the `proposed` directory. The name of this file should be the next resolution number
in sequence in the current year, based on the [list](numbers.md). Add a line to that file
assigning the number to the new file, and link to it as the existing files are linked.

Edit the new file's header, subject, and `text of proposal` sections to document your proposal.
When your proposal is ready, send a Pull Request to the governance repository. This will notify
the Steering Committee members of your proposal, and it will be added to the agenda for the
next meeting when the Pull Request is merged.

## Approving a resolution

### Summary

1. Update proposal w/votes, date, and optionally rationale
1. Move proposal to `approved`
1. Push to update the PR
1. Merge the PR

### Details

If the Steering Committee votes to approve a resolution, then:

* The resolution document will be moved from the `proposed` directory to the `approved`
directory.

* The resolution document will be updated to reflect the date of the meeting where it was
approved, the voting results, and the status will be changed from 'Proposed' to 'Approved'.

## Declining a resolution

### Summary

1. Update proposal w/votes, date, rationale
1. Move proposal to `declined`
1. Push to update the PR
1. Merge the PR

### Details

If the Steering Committee votes to decline a resolution, then:

* The resolution document will be moved from the `proposed` directory to the `declined`
directory.

* The resolution document will be updated to reflect the date of the meeting where it was
declined, the voting results, and the status will be changed from 'Proposed' to 'Declined'.

## Deferring a resolution

### Summary

1. Update `Status:` header line in proposal, changing date & status
1. Add `Deferred to:` header line
1. Email program manager to ensure proposal review gets onto the agenda for the appropriate date
1. Push to update the PR
1. Leave PR open

### Details

If the Steering Committe is unable to reach a consensus on a resolution, this will
be communicated to the proposer; if the committee requires additional information or
work from the proposer, and the time required to provide this information or work
will extend past the agenda deadline for the next Steering Committee meeting, the
committee may elect to 'defer' the resolution until a future meeting.

If this occurs the resolution document will have its status changed from 'Proposed' to
'Deferred', and will include the date that the deferment will expire.
