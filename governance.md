# Main Governance Document

The official version of this document, along with a list of individuals and
institutions in the roles defined in the governance section below, is contained
in The Project Governance Repository at:

https://github.com/GenericMappingTools/oversight

## The Project

The Generic Mapping Tools (The Project) is an open source software project. The goal 
of The Project is to develop open source software and related technology for manipulating
geographic and Cartesian data sets and producing high-quality illustrations and animations.
The Software developed by The Project is released under open source licenses including
LGPL and BSD, developed openly and  hosted in public GitHub repositories under the 
GenericMappingTools GitHub organization. Examples of Project Software include the 
GMT C library and the Python (PyGMT), Julia (GMT.jl), and MATLAB (GMT/MEX) wrappers.
The Services run by The Project consist of public websites and web-services that
are hosted under the generic-mapping-tools.org domain. Examples of Project Services
include the Generic Mapping Tools website (https://www.generic-mapping-tools.org/),
the Generic Mapping Tools data servers (listed at https://www.generic-mapping-tools.org/mirrors/),
the Generic Mapping Tools Discourse Forum (https://forum.generic-mapping-tools.org/), and the
PyGMT project domain (https://www.pygmt.org).

The Project is developed by a team of distributed developers, called
Contributors. Contributors are individuals who have contributed to code, code
reviews, documentation, design, and infrastructure, or to mailing lists, chats,
community help and community building, education and outreach, or other work in
relation to one or more Project repositories. Anyone can be a Contributor.
Contributors can be affiliated with any legal entity or none. Contributors
participate in The Project by submitting, reviewing and discussing GitHub Pull
Requests and Issues and participating in open and public Project discussions on
GitHub, the Discourse Forum, and community meetings. The foundation of Project
participation is openness and transparency.

Here is a list of the current Contributors to the main GMT repository:

https://github.com/GenericMappingTools/gmt/graphs/contributors

There are also many other Contributors listed in the logs of other repositories
of the Generic Mapping Tools Project.

The collection of all Contributors to The Project and stakeholders in The
Project, including Users and Funders, is called The Community.  Contributors
work on behalf of and are responsible to the larger Project Community and we
strive to keep the barrier between Contributors and Users as low as possible.

## Governance

### The Steering Committee

The Project will have a Steering Committee that consists of Project Contributors
nominated as explained below. The Steering Committee should be composed of
a diverse array of backgrounds, viewpoints and talents. The overall role of the
Committee is to ensure, through taking input from the Community, the long-term
well-being of The Project, both technically and as a community. As The Project
draws its strength from representing the Community, it strives to avoid
fragmentation of the Community into separate projects, if possible.
The Steering Committee will maintain a minimum of three members.

During the everyday Project activities, Committee Members participate in all
discussions, code review and other Project activities as peers with all other
Contributors and the Community. In these everyday activities, Committee Members do
not have any special power or privilege through their membership on the Committee.
However, it is expected that because of the quality and quantity of their
contributions and their expert knowledge of The Project Software and Services
that Committee Members will provide useful guidance, both technical and in terms
of Project direction, to potentially less experienced Contributors.

The Steering Committee and its Members play a special role in certain situations.
In particular, the Committee may:

* Make decisions about the overall scope, vision and direction of The Project.
* Make decisions about strategic collaborations with other organizations or
  individuals.
* Make decisions about the Services that are run by The Project.
* Make decisions when regular Community discussion doesn’t produce consensus on
  an issue in a reasonable time frame.

Outcomes and decisions should be clearly communicated to the Community. This can
take three different forms:

* New challenges for The Project will be detailed as a GitHub discussion in the oversight
  repository or a topic on the GMT Forum for the Community to discuss.
* Resolved technical deadlocks will result in an explanation on the relevant
  issue and/or closure of the relevant pull request.
* Other decisions will be detailed as a narrative blog post or announcement on the website.

#### Committee Membership

To become eligible for being a Steering Committee Member an individual must be a
Project Contributor who has produced contributions that are substantial in
quality and quantity, and sustained over at least six months. Steering Committee Members should
have a GitHub account to participate in discussions and document decisions. Project contributions
can include contributions within the Generic Mapping Tools organization (e.g., GMT,
GMT wrappers, GMT services) or to closely related upstream (e.g., GDAL) or
downstream (e.g., GMTSAR, MB System) projects. After confirming the potential Committee
Member is interested and willing to serve in that capacity, Members are nominated by
Community Contributors and voted upon by the existing Committee via majority vote.

When considering potential Members, the Committee will look at candidates with a
comprehensive view of their contributions. This will include but is not limited
to code, code review, infrastructure work, mailing list and chat participation,
community help/building, education and outreach, design work, etc. We are
deliberately not setting arbitrary quantitative metrics (like “100 commits in
this repo”) to avoid encouraging behavior that plays to the metrics rather than
The Project’s overall well-being. We want to encourage a diverse array of
backgrounds, viewpoints and talents in our team, which is why we explicitly do
not define code as the sole metric on which Committee Membership will be evaluated.

There are two mechanisms by which a Committee Member may exit the Steering
Committee:

1. Committee Members may resign their posting at any time during their tenure on
   the Steering Committee. In order to maintain an active, energetic, and healthy
   Committee, Committee Members will self-facilitate membership check-ins every 6
   months to confirm that each member intends on continue their service on the
   Committee.
2. A majority of the existing Committee votes to remove a Member.

If a Committee Member becomes inactive in The Project for a period of one year,
they will be considered for removal from the Committee. Before removal, an
inactive Member will be approached by the a Committee Member to see if they plan
on returning to active participation. If not they will be removed immediately
upon a Committee vote. If they plan on returning to active participation soon,
they will be given a grace period of one year. If they don’t return to active
participation within that time period they will be removed by vote of the
Committee without further grace period.

All former Committee Members can be considered for Membership again at any time
in the future, like any other Project Contributor. Retired Committee Members
will be listed on the Project website, acknowledging the period during which
they were active in the Committee.

#### Expectations for Committee Members

Steering Committee members are expected to commit to the following activities:
- Attend a one-hour steering committee meeting every six months.
- Respond in a timely manner to steering-committee-related correspondence.
- Act as an ambassador for the project in professional contexts.

The chair of the Steering Committee is expected to arrange the regular meetings
and ensure that a report is shared with the community.

## Changing the Governance Documents

Changes to the governance documents are submitted via a GitHub pull request to
The Project's governance documents GitHub repository at
https://github.com/GenericMappingTools/oversight. The pull request is then refined in
response to public comment and review, with the goal being consensus in the
community. The period for open comment will last in proportional to the
complexity of the changes; major changes will be open for comment for no less
than two weeks. After this open period, a Steering Committee Member proposes to
the Steering Committee that the changes be ratified and the pull request merged
(accepting the proposed changes) or proposes that the pull request be closed
without merging (rejecting the proposed changes). The Member should state the
final commit hash in the pull request being proposed for acceptance or rejection
and briefly summarize the pull request. A minimum of 80% of the Steering Committee
must vote and at least 2/3 of the votes must be positive to carry out the
proposed action (fractions of a vote rounded up to the nearest integer).

## References

This governance document is based on the [Pangeo governance model](https://github.com/pangeo-data/governance).
