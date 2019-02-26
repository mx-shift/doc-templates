# Design Specification Template

### Author: [you@](mailto:you@domain.example)

## Objective 

_One or two sentence description of what you problem you are trying to solve._


## Goals

_List of things your design explicitly tries to accomplish. The design must meet all of these to be acceptable._

  *
  *

## Non-goals

_List of things your design explicitly chooses to not address._


  *
  *

## Background

_Describe any systems, components, and/or technologies which are required for
but are not part of this design proposal. Assume your audience is unfamiliar
with the design space. Only provide as much detail here as necessary for a
reader to make sense of your design proposal and know where to look if they
want additional detail. Include links to relevant references both internal
and external._

_This is also the place to discuss the limitations of prior designs and
implementations. Wait to describe your solutions to those limitations as part
of the Design section._


## Design

_Describe your design in terms of what you covered in the Background section.
Provide an overview of the major components in your solution, how users and
external components will interact with them, and how the components interact
with each other internally._

_Unlike a Design Proposal, this section should contain specific details of
what you plan to build. Cite specific design patterns, technologies, and
components that are required to build the design. Avoid specifying ancillary
details such as specific libraries, programming languages, etc unless their
use is explicitly part of the design. For example, prefer to specify “a SQL
server” rather than “MySQL” unless your design depends on features that are
only available with MySQL or MySQL was specifically chosen for this design
after an evaluation and team discussion._


## External Dependencies

_Are you depending on others to deliver a component required for this design to succeed? What other systems
does this depend on at runtime?_


## User Data Handling

_Does your design carry user data (PII or other)? Why? Is it transitory or
stored by your system? What safeguards are in place to prevent unauthorized
access?_


## Security Considerations

_How have you minimized the impact of vulnerabilities in your design? Are
there any known weak areas that lack alternatives? What tools and practices
are you using to prevent unsafe coding practices?_


## Testing

_What testing methodologies will you use? How are tests being monitored for
failures? What is your code coverage target? How is it measured? Must all
tests be passing before a normal release?_


## Source Code

_Where does the code actually live? Who has access? What style guide is being
used? Will tools to automatically enforce that style guide be put in place?_


## Alternatives Considered

_For each major design choice in your proposal, add a subsection here to
describe each alternative you considered and why you rejected it. A reader
should be able to understand your reasoning that led to your proposal even if
they disagree._

