# DRAFT - NOT YET APPROVED by Magma Core Foundation

# **GRANTS**

## Deadline and Notifications: Rolling

The Magma Core Foundation (MCF) oversees the grant program.  We provide individuals and project teams with access to funding, technical support, and community resources. Grant proposals are reviewed and approved by the MCF team and Grant Committee.

The Magma Core Foundation seeks to connect the world to a faster internet by enabling service providers to build cost-effective and extensible connectivity services.  This is where you come in. We are actively looking for teams to help us build and improve Magma and Magma related products to make the Open Source Wireless future possible. Our funding is non-dilutive, so we never take any ownership over the IP or team, but we do ask that any software be licensed under the BSD 3 Clause license and contributed to the Magma Open Source library.  We typically prefer working on smaller grants, but will consider funding grants up to a maximum of $1M USD. Grants are priced and issues in USD. We are happy to cover things like prototyping costs, but don&#39;t typically pay for travel, rentals, yachts or freelancers&#39; salary. Ideally the scope of the work fits within a 12 month period.


 ## Grant Program Criteria

Here is the primary criteria for MCF grant applicants:

- Implements features or functionalities of Magma or Magma related Open Source software
- You have a business need with a differentiated service offer, wherein Magma is used for leverage and accelerate the time to market.  
- Have a good idea on your service offer tied to a market TAM (total addressable market) and your approachable SAM (Serviceable addressable market).  
- Timeframe: up to 12 months to Proof of Concept (poc).
- Licensed openly under the BSD 3 Clause license.
- Implemented to the quality standards of the Magma Project as confirmed by one or more then current Magma Codeowners

 ## How to Apply

The application process itself is fairly easy, although most applicants find creating a good roadmap to be the hardest part (see below for an example). The best way to get your proposal accepted is to write a great roadmap and be ready to share the business case tied to your service offer. If you have a great idea for building in our ecosystem, apply!

We recommend that the scope of the work (SoW) can fit within a 12 month period or less.

ProTip: Milestones should relate to a completed deliverable over an estimated timeframe and payments which reflect these milestones.

For a roadmap, we recommend the following:

- describe the expected functionality and how to validate it
- how your project would leverage Magma ( description of soluiton architecture, solution stack, end to end representation is best)
- tie function(s) to milestones

For a business case, we recommend the following:

- Target Market (TAM) and approachable servicablity opportunity (SAM)
- Financial model to end customer 
- Route to Market - Offer specifics
- Commerical revenue projections if any

Example:

Milestone 1, September 30 2021, $2000 upfront

*implementation of X feature or functionality, explain*

Milestone 2, October 31 2021, $5000 when completed

*explain additional features and implementation*

Milestone 3, November 20 2021, $5000 when completed

*final feature implementation and poc/mvp demo*

**Please make a copy of the [Application Template](https://github.com/magma/grants/blob/master/template.md) and submit as an issue in this repo.**

## Proposal Acceptance, approval and grant awards

Each grant proproal received will be reviewed by the Magma Core Foundation's Technical Steering Committee (TSC).  Prior to consideration of any grant for approval the TSC must gain sign-off from at least one current Magma Codeowner, as defined in the Magma Technical Charter, who will agree to serve as a Technical Lead with oversight of the performance against any gant awarded against the proposal. The TSC may request changes to the proposal to help it better align with the objectives and practices of the MCF as well smooth integration into Magma's overall roadmap.  The TSC may also request clarification regarding schedules and committments associated with the grant.  

Those proposal's that recieve technical acceptance from the TSC will be forrwarded to the MCF Governing Board (GB) for final approval and grant award.  The GB may request further clarification and changes before any grant is awarded.

Performance against the committments associated with any grant awarded will be monitored by the project Technical Lead (codeowner) appointed by the TSC.

----------------------

**Best Practices:**

- All code must be sumitted for public review and approval by at last one Magma Codeownerprior to being accepted/merged into Magma
- Provide a test suite, comprising unit and integration test, along with a guide on how to set up and run.
- Unit Test must include code coverage of at least 70% of the code submitted.
- Provide tutorials for the community to onboard or implement your project
- Indicate milestone duration as well as number of full-time employees working if it varies from milestone to milestone

-----------------------

**Areas of Interest**

*Based on feedback from the community, here are some projects in no particular order that MCP is keen to support.*

1. Support for outbound roaming of Magma subscribers
2. Support for inter-AGW handoff between Magma AGWs
3. Support for handoff between Magma AGWs and non-Magma 3gpp compliant networks
4. Full support for IPv6 user (bearer plane) data connections
5. Support for VoLTE and/or VoNR (5g) by integrating with 3rd party IMS platforms
6. Support for 5g Network Slicing functions
7. Improved security of for Magma
8. Updating Magma's use of 3rd party packages to current revisions
9. Resolution of issues with Magma discovered by automated code scanning tools 

-----------------------

Some examples from prior project proposals:

| Project                                             | Notes
|-----------------------------------------------------|----------------------------------------------
| TBD | TBD |
