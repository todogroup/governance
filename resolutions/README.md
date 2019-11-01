# TODO Group Resolution Process

This process is designed to allow members of the TODO Group to propose actions to be
considered by the Steering Committee, for the Steering Committe to review and discuss
them, and for actions taken by the Steering Committee to be documented.

## Proposing a resolution

Fork this repository, and copy the [resolution template](template/standard.md) into a new
file in the `proposed` directory. The name of this file should be the next resolution number
in sequence in the current year, based on the [list](numbers.md). Add a line to that file
assigning the number to the new file, and link to it as the existing files are linked.

Edit the new file's header, subject, and `text of proposal` sections to document your proposal.
When your proposal is ready, send a Pull Request to the governance repository. This will notify
the Steering Committee members of your proposal, and it will be added to the agenda for the
next meeting when the Pull Request is merged.

## Accepting a resolution

If the Steering Committee votes to adopt a resolution, then:

* The resolution document will be moved from the `proposed` directory to the `accepted`
directory.

* The resolution document will be updated to reflect the date of the meeting where it was
accepted, the voting results, and the status will be changed from 'Proposed' to 'Accepted'.

## Declining a resolution

If the Steering Committee votes to decline a resolution, then:

* The resolution document will be moved from the `proposed` directory to the `declined`
directory.

* The resolution document will be updated to reflect the date of the meeting where it was
declined, the voting results, and the status will be changed from 'Proposed' to 'Declined'.

## Deferring a resolution

If the Steering Committe is unable to reach a consensus on a resolution, this will
be communicated to the proposer; if the committee requires additional information or
work from the proposer, and the time required to provide this information or work
will extend past the agenda deadline for the next Steering Committee meeting, the
committee may elect to 'defer' the resolution until a future meeting.

If this occurs the resolution document will have its status changed from 'Proposed' to
'Deferred', and will include the date that the deferment will expire.
