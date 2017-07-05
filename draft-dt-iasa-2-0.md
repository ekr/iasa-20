---
title: IASA 2.0 Design Team Recommandations
abbrev: IASA 2.0
docname: draft-dt-iasa-2-0-latest
date: 2017-07-13
category: info

ipr: trust200902
area: General
workgroup: XMPP Working Group
keyword: Internet-Draft

stand_alone: yes
pi: [toc, sortrefs, symrefs]

author:
 -
    ins: B. Haberman, Editor
    name: Brian Haberman (Editor)
    organization: Johns Hopkins University Applied Physics Lab
    email: brian@innovationslab.net
    
    ins: J. Arkko
    name: Jari Arkko
    organization: Ericsson Research
    email: jari.arkko@piuha.net

    ins: L. Daigle
    name: Leslie Daigle
    organization: Thinking Cat Enterprises LLC
    email: ldaigle@thinkingcat.com
    
    ins: J. Hall
    name: Joseph Lorenzo Hall
    organization: CDT
    email: joe@cdt.org
    
    ins: J. Livingood
    name: Jason Livingood
    organization: Comcast
    email: Jason_Livingood@comcast.com
    
    ins. E. Rescorla
    name: Eric Rescorla
    organization: RTFM, Inc.
    email: ekr@rtfm.com

normative:
  RFC2119:

informative:
  RFC4071:
  I-D.daigle-iasa-retrospective:
  I-D.hall-iasa20-workshops-report:

--- abstract

Abstract

The arrangements relating to administrative support for the IETF were created more than ten years ago. There's been considerable change in the tasks and our own expectations since then. The IETF community has discussed these changes and the problems they cause. The community has some sense of the properties they expect from future arrangements, including structural and organizational changes, changes to volunteer and staff personnel resources, and transparency changes.

This document is a product of a design team, focused on providing additional information to the community about solution options, as well as supporting analysis of the implications of those options. To be clear, the community is in charge of adopting any recommendations or making any decisions.

--- middle

Introduction
============

The arrangements relating to administrative support for the IETF (IASA [](#RFC4071)) were created more than ten years ago, when the IETF initially took charge of its own administration. The arrangements have reasonably served the IETF, but there's been considerable change in the necessary tasks, in the world around us, and our own expectations since the creation of the IASA. What administrative arrangements best support the IETF in the next ten years?

The system has experienced various challenges and frustrations along the way, for instance around meeting arrangements. There are also some bigger questions about how the organisations are structured, for instance about the division of responsibilities between IETF and ISOC.

The IETF community has discussed and continues to discuss these topics, most recently in the “IASA20” mailing list and BOF at IETF98. Alissa Cooper, the Chair of the IETF, asked a small design team to start evaluating potential options going forward. The purpose of the design team is to provide material that informs the community discussion, both in terms of providing a bit more worked through solution ideas, as well as supporting analysis of the implications of those options. This information, along with all other input provided in the discussion, hopefully helps the community and IETF leadership decide what next steps to take. To be clear, the community is in charge of adopting any recommendations or making any decisions. This draft, the output of the design team’s considerations, has no particular official standing.

As a base for this work there is a good articulation of the set of problems we are facing in {{I-D.hall-iasa20-workshops-report}} and {{I-D.daigle-iasa-retrospective}}. The community discussion seems have indicated also some of the outcome properties that are expected. The scope of the solutions explored included:

- Structural and organizational changes, both externally (with ISOC and contractors) and internally (within the IAOC and subcommittees)
- Changes to personnel resources, both volunteer and paid
- Transparency changes

Changes to the funding model are out of scope to the extent they fall outside the categories above.

The rest of the document is organised as follows. The next two sections describe the background and summarise the challenges noted in the community discussion. The two sections after that explain what categories of changes were considered, and describe the primary options for structural changes. The following section discusses other changes, followed by two sections on analysis of the different options along with a recommendation.

Background
==========

The administrative support structure intended to be responsive to the administrative needs of the IETF technical community.

RFC 4071 defines the current IETF Administrative Support Activity (IASA). It is an activity housed within the Internet Society (ISOC), as is the rest of the IETF.  RFC 4071 defines the roles and responsibilities of the IETF Administrative Oversight Committee (IAOC), the IETF Administrative Director (IAD), and ISOC in the fiscal and administrative support of the IETF standards process.  It also defines the membership and selection rules for the IAOC.

As RFC 4071 notes, IASA is distinct from IETF-related technical functions, such as the RFC Editor, the IANA, and the IETF standards process itself.  The IASA has no influence on the technical decisions of the IETF or on the technical contents of IETF work. 

Today, IASA's activities support a number of functions within the IETF system:

+ Meeting planning
+ Contracting with and overseeing the secretariat
+ Contracting with the overseeing the RFC Editor (together with IAB)
+ Contracting with and overseeing IANA (together with IAB)
+ Legal ownership of IETF materials, domain names and copyright
+ Ownership of IANA-related domain names and copyright
+ IETF website
+ IETF IT services
+ Tooling support, maintenance, and development (together with volunteers)
+ Meeting network support
+ Remote attendance support
+ Communications assistance for the IETF
+ Sponsorship and funding (together with ISOC)

Terminology
-----------

The following acronyms are used in this document:

+ IASA - IETF Administrative Support Activity - An organized activity that provides administrative support for the IETF, the IAB and the IESG.

+ IAOC - IETF Administrative Oversight Committee in the current IASA system - A largely IETF-selected committee that oversees and directs IASA.  Accountable to the IETF community.

+ IAOC committees - Recognizing the need for specialized attention for different branches of work requiring IAOC oversight, the IAOC expanded its support by creating committees. Currently, the committees do the heavy lifting on background work, while the IAOC is the one responsible for final decisions.
      
+ ISOC - The Internet Society - An organizational home of the IETF, and one that in the current IASA system assists the IETF with legal, administrative, and funding tasks.

+ IAD - IETF Administrative Director - In the current system, the sole staff member responsible for carrying out the work of the IASA.  An ISOC employee.

+ IETF Trust - In the current system the IETF Trust acquires, maintains, and licenses intellectual and other property used in connection with the administration of the IETF.  Same composition as IAOC.

Challenges
==========

Discussion leading to this document has been framed by the issues discussed on IETF mailing lists and documented elsewhere  {{draft-daigle-iasa-retrospective}}, {{draft-hall-iasa20-workshops-report), {{draft-arkko-ietf-iasa-thoughts}}.  The reader is referred to those documents and ongoing discussion on the IASA20@ietf.org mailing list for fuller details on the range of challenges facing the IETF in its handling of administrative matters.

In summary, the key areas of challenge that have shaped this work are:

+ The range of IETF administrative tasks has grown considerably; ensure we have the right structure, community involvement and level of staffing to address them effectively and efficiently.

+ The relationship and division of responsibilities between the IETF and ISOC, as both organizations have grown considerably in the last decade.

+ Alignment of community expectations of transparency of administrative actions and delivery from the administration.

+ Funding and sponsorships. Manage expectations about locations of meetings (broadening of IETF engagement, sponsor preferences), balanced against operational practicalities.  Ensure that we continue to not be influenced by funding entities on the technical work of the IETF.

Of the items above, the first two are largely to be addressed by structural updates, while the last two groups are more about discussing tradeoffs and updating documented expectations.


Considering a Change
====================

Given that a change seems necessary, what might that change include? There seems three broad categories of IETF organisation that are going to be affected:

1. Organisation within IASA itself
2. Relationship with ISOC
3. Interfaces and expectations between IASA and the rest of the IETF

The aspects are of course somewhat interconnected. For instance, how IETF defines its relationship to ISOC will have some implications for the internal organisation within IASA. A more independent, free-standing organisatorial model for IETF would imply new functions at IASA.

There are a number of choices to make within the reorganisation effort. In particular, IETF's relationship to ISOC could be arranged in a fundamentally similar manner than it is today, but improved, e.g., to make clear who is expected to control a particular part of the operation. But the relationship could also be arranged in a different way, for instance, as a subsidiary of ISOC or as a more free-standing, own organisatorial unit.

Goals
-----

The IASA redesign effort needs to address the main challenges listed above. More specifically, a chosen new organisatorial structure needs to do at least the following:

+ Define the roles of the oversight entities and staff/contractors to match the grown size of the tasks. Ensure that we have a structure that can adapt to future growth and other changes.

+ Define the roles of IETF and ISOC in a way that helps the above structure be as clear as possible, in terms of who does what, how are things accounted, and who is in charge of adjustments and control (e.g., staff resources). Propose a starting point for the financial arrangements between IETF and ISOC, either as they are now or changed in some fashion. It shall also be clear to people outside the IETF and ISOC organisation (e.g., sponsors) what the arrangements are and what their contributions affect and do not affect.

+ The new organisation needs to accommodate for strategic, operational, and execution of administrative tasks, and take into account the limited availability of IETF volunteers for performing administrative tasks. The new design needs to ensure that overload in, e.g., operational decisions does not affect the ability to drive strategic changes.

+ Set expectations and limits of those expectations on the different parts of the system. This includes, but is not limited to community expectations of transparency.

+ Ensure that future IASA organizational structure and processes preserves and protects the IETF’s unique culture of individual contribution, clear separation of financial support from technical work, as well as rough consensus and running code.

Reorganisation within IASA and IETF
===================================

The design team believes that any future organisation for IASA needs to put all resources for the IETF in the more clear and direct control of the IETF. In addition, staff resources need to increase and/or be reorganised in order to move from one director to a few more specialised roles. Finally, the role defined for community members serving in IASA needs to be set so that we can actually expect a sufficient number of volunteers.

The internal organisation of IASA is also obviously affected by what we decide to do with the relationship with ISOC. A bigger, more independent role for the IETF would require that the IASA be designed with that in mind.

But in addition to these given changes, there are a number of choices in division of responsibilities and the structure of the organisation. The key decision points are:

+ Whether the community representative or board control of IASA is at the level of individual administrative decisions (as it is today) or at a more traditional board level of control, i.e., stategic direction, budgets, and key personnel choices.
+ Whether the interface to the community is via staff or a community representative or board function.

Internal IAOC organisation
--------------------------

Two combinations of the above decision points are given here; the rest can be inferred.

### Option A -- Strategic board with empowered staff

In this option, the current IAOC is disbanded and replaced by a traditional oversight board, common in most non-profit organisations. This board, the IASA Board (IB), acts to set strategic director for IETF administrative matters, sets budgets, provides fiscal oversight, provides high-level oversight about major new projects. The board is also responsible for staffing all director level positions in the organisation.

The staff and key contractors are responsible for operating within the limits set by the board, and are accountable to the board. Including being hired and fired as needed. The staff's responsibilities include:

+ preparing for and making decisions on their agreed and budgeted areas (for example, meeting venue decisions)
+ operational execution of thos decisions
+ communicating with the community

The composition of the board needs some care. It is important to have regular IETF participants in the board, but at least some of the board members need to be well-networked ble to help make connections to raise money or provide advice about fundraising (which is pretty typical for a non-profit board).

One potential model for populating the board is a Nomcom-selection for 2/3 of the board members and selection by IETF and ISOC leadership for 1/3 of the board members with a view for more outside, well-networked members.


### Option B -- Strategic board with empowered staff helped by advisory board

In this option, there is a board and staff just like in option A, but in addition, an Advisory Council (AC) provides an interface to the community on matters that require assessing community opinion. For instance, the current polling of community feedback relating to potential future meeting locations could be one such matter.

(An advisory council canvasing and pulling for this information is probably a better approach than either freeform mailing list discussion, or the relatively opaque process that is currently used. Advisory board results could be documented in the same fashion as IESG documents documents last call results. Some IAOC site decisions have been done in this way, but not all, possibly due to lack of time.)

The advisory council would be comprised of IETF community members and selected by Nomcom, and would benefit from having either the IETF Chair or another IESG member as a liaison. The advisory council would not make decisions about how the IETF should run, but it would be available for the staff to consult whenever they needed a view from the community, and it would also be available to run community discussion processes or to get input from the community to funnel back to the staff. The advisory council would have a well-defined interface to the IESG as well.

The separation of the board and the advisory council, with some overlap between them, allows the allocation of people to tasks according to their skills. We can have experienced managers involved in hiring/firing/reviewing the director staff and overseeing the budget, while we have experienced community people giving the perspective of the community.

Staff resources
---------------

The current arrangement involves one officially designated IASA employee, but there are also many supporting employees. They are less clearly assigned for the IETF, working at contractors and at ISOC.

This document suggests a structure that involves:

+ An Executive Director. The person in this role is in charge of the overall IASA effort, but can rely on other staff members below as well as contractors. The Executive Director is accountable to the Board.
+ Operations Director. This person is responsible for meeting arrangements, IT, tools, and vendor contracts (including RFC Editor and IANA).
+ Partner Director. This person is responsible for working with IETF's sponsors and other partners, and the primary responsible for fundraising.
+ Communications Director. This person is responsible for working with IETF leadership (incl. IETF Chair, IESG, and IAB) on communications matters, assisting them in efficient communication and dealing with ongoing communications matters.
+ Legal Counsel. This person assists the IASA on legal matters as well as prepares and reviews all contracts that are needed with IETF's contractors.

The Executive Director needs to be an employee, but the other roles can also be contractors.

Structuring the IETF’s relationship with ISOC
=============================================

From Alissa’s document + more thinking ...

Analysis
========

This section provides a basic analysis of the effects of the different options. The current situation is evaluated and compared along with the different options for both IETF's relationship with ISOC and internal organisation of IASA. Note that a final proposal for changes needs to provide a model for both the ISOC relationship and internal organisation. For instance, option "3B" would signify an independent IETF organisation with a strategic board and an advisory council.

Criteria
--------

We use the following criteria based on the goals stated earlier:

+ The arrangements match the scale of the task (SCALE)
+ The arrangements are designed to evolve as situations evolve (EVOLVE)
+ Accommodates strategic tasks (STRAT TSK)
+ Accommodates operational and execution tasks (OPS TSK)
+ Avoids overload in one class of tasks preventing progress in other (OVERLOAD SEP)
+ Clarifies the relationship between IETF and ISOC (CLEAR ISOC REL)
+ Allows direct IETF control of resources (e.g., staff) working on a task (DIR CONTROL)
+ Preserves IETF culture and mode of operation (CULTURE)
+ Separates IETF technical work and administrative tasks and funding (WORK SEP)
+ Sets expectations on what can or can not be expected from IASA (IASA EXP)

Internal Organisation
---------------------

For the internal organisation, the implications of the current situation and the two options are summarised below:

```

|                | Current situation | Option A         | Option B        | 
| SCALE          |        NO         |       YES        |       YES       |
| EVOLVE         |   MAYBE (Note 1)  |   MAYBE (Note 1) |  YES (Note 1)   |
| STRAT TSK      |        NO         |   YES (Note 2)   |       YES       |
| OPS TSK        |        YES        |   YES (Note 2)   |       YES       |
| OVERLOAD SEP   |        NO         |   YES (Note 2)   |       YES       |
| CLEAR ISOC REL |        n.a.       |       n.a.       |       n.a.      |
| DIR CONTROL    |        n.a.       |       n.a.       |       n.a.      |
| CULTURE        |        YES        |       YES        |       YES       |
| WORK SEP       |        YES        |       YES        |       YES       |
| IASA EXP       |         NO        |   MAYBE (Note 3) |  MAYBE (Note 3) |

```

Note 1: Given that IASA is being reorganised, even the current system is capable of evolving. However, the operational focus and overload in the current arrangements are making this harder than is necessary. Change requires action from outside IASA, rather than being a normal task within IASA to evolve their own model. Option A maybe a bit weaker than option B in evolution, given that in Option B there is a dedicatd advisory council that can help determine community concerns.

Note 2: There may be a difference between Option A and Option B in how overload situations and the separation of different tasks goes. The existence of an advisory board may take off some board or staff load to deal with community opinion determination, freeing the board to do its strategic work and staff to concentrate on operations and execution.

Note 3: Setting expectations is difficult merely based on an organisatorial model. Certainly a clear separation between roles of the board and staff helps. However, expectations are also a matter of documentation, which would have be created and communicated. Finally, expectations are a cultural matter, current IAOC arrangements and community views have ended up in a situation where there is a lack of trust and unclear models for what can or can not be expected.

IETF-ISOC Relationship
----------------------

For the IETF-ISOC relationship, the implications of the current situation and the three options are summarized here:

```

|                | Current situation | Option 1         | Option 2        | Option 3        |
| SCALE          |         NO        |        NO        |       YES       |       YES       |
| EVOLVE         |         NO        |   NO (Note 4)    |  MAYBE (Note 4) |   YES (Note 4)  |
| STRAT TSK      |         NO        |   NO (Note 4)    |       YES       |       YES       |
| OPS TSK        |        YES        |       YES        |       YES       |       YES       |
| OVERLOAD SEP   |        YES        |       YES        |       YES       |       YES       |
| CLEAR ISOC REL |         NO        |        NO        |       YES       |       YES       |
| DIR CONTROL    |         NO        |        NO        |       YES       |       YES       |
| CULTURE        |        YES        |       YES        |       YES       |       YES       |
| WORK SEP       |        YES        |       YES        |       YES       |       YES       |
| IASA EXP       |         NO        |   MAYBE (Note 3) |  MAYBE (Note 3) |  MAYBE (Note 3) |

```

Note 4: Evolution in the current system is more difficult than if IETF was either clearly a subsidiary or its own organisation. This would also ease driving any strategy that the IETF wants to drive, as decisions would be more on the IETF side than something that today would require negotiation with ISOC.

Financial Impacts
-----------------

There are two different classes of changes. First, both the ISOC interface change and staff changes will imply changes in what is being accounted for in budgets and reports, even in cases where the actual work or the number of people stays the same. Secondly, there are actual increases.

We expect all the alternatives to lead to somewhat higher funding needs, and in fact shifting more work to staff from volunteers is one of the goals. For the internal reorganisation, the primary position actually being added is having both Executive Director and Operations Director, instead of one IAD. We've already had Legal Counsel and Communications Director. These chances coincide with other personnel changes in IASA, as the experienced, long-term IAD is retiring. Even from a learning curve point of view more people will be needed, but in this case it also makes sense to have the organisation be less dependent on one central person.

Given the learning curve effect, and a new organisation, it is expected that the role of the Legal Counsel will also increase, e.g., in terms of reviewing contracts. Staff 

The effects of ISOC relationship changes to finance are for further study.

Other Impacts
-------------

Depending on the chosen option, volunteers are needed for either different roles than today (the board) or for both different roles and more volunteers (the board and the advisory council).

It is for further study whether current IETF leadership (e.g., IAB Chair) should continue to be part of these boards or councils.

Conclusions and recommendations
===============================

Clearly more work is needed, and thoughts and contributions regarding either new options or their implications is welcome.

Acknowledgments
===============

This text is the work of the design team, but greatly influenced by discussions in the IETF community. The team would in particular like to thank Alissa Cooper, Andrew Sullivan, Ray Pelletier, Ted Hardie, Gonzalo Camarillo, Brian Carpenter, Lucy Lynch, Stephen Farrell, Dave Crocker, Jon Peterson, Alexa Morris, Michael Richardson, Olaf Kolkman, Kathy Brown, and Melinda Shore for interesting discussions in this problem space.

--- back

Non-normative references
========================

