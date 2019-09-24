## Intro to Dev Ops

## The Purpose of Dev Ops

- Purpose of a Company is to create value : Physical/Intellectual/Social
- To Create Value, Needs Idea for Product or Service (Solves a Problem)
- Requires Communication between Teams
- DevOps facilitates Communication
- Without DevOps, it's difficult to manage the technical load during the production process

## Definition of DevOps

- No one official Definition, Many Descriptions
  - Practice of Operation and Development Engineers participating together in the entire service lifecycle (From design to Development and Production Support)
  - Cultural and Professional movement, focused on how we build and operate high velocity organizations, born from the experiences of its practitioners.
- Development roles don't just include Code (Everybody who's involded including: QA / Product Managers / Sysadmins / Security etc)

#### Acronym CAMS

- C (Culture)
- A (Automation)
- M (Measurements)
- S (Sharing)

### What Dev Ops is not

- Lots of different views on Dev Ops
  - Dev Ops isn't taking over Ops
  - Nor is it just a bunch of management tools
    - Does Google Calendar cause you to show up on time to meetings? It's simply a tool to accomplish a tool

### Software Development lifecycle

- Agile Development
  - Plan => Code => Test
    Feedback collaborated between Teams
    - Unit Testing
    - Integration Testing
    - User Acceptance Testing
  - Doesn't speak to the Release Process, Only Development
- Agile + Continuous Integration + Delivery

  - Plan => Code => Test => Release => Deploy => Operate
    ^-Feedback-^^Automation^ ^--Feedback-^----------^

- Dev Ops
  - Agile + Continuous Integration + Delivery + Dev Ops
    - Plan => Code => Test => Release => Deploy => Operate
      ^-Feedback-^^Automation^ ^--Feedback-^ Monitoring----^

#### Tools used in the Course

- Packer

  - Creates Golden Images for Developers to launch servers

- Jenkins for Continuous Integration

- Monitor using Amazon Aws

#### C is for Culture

- Huge inspiration of Dev Ops is Agile, Key point is People over Process over tools

  - Most efficient product/develop/marketing but without Communication, Loss of Resources

- Improving Flow over Pipeline, Focus on Customers as Main Goal
- Hug Ops, Understand and empathize on both Devs and Ops side

#### A is for Automation

- Whenever you write a piece of code to do a task. that otherwise you'd do by hand, that's Automation
- Deployment is an example of automation, Sysadmins no longer needid to set up Physical servers
- Scaling makes Automation necessary

#### M is for Measurements

- In order to improve something, you have to be able to quantify/measure it
- Benchmarking / Measurements
- Participation of Development team with Ops, increases Measurements
- Record Business Metrics, Tsx/per Second
- Effectiveness of your own Tools

#### S is for Sharing

- Align all the different stakeholders towards the same Goal
- Everyone understands and collaborates the Work Flow
- People are willing to work together when their thoughts and opinions are the same
- Define and measure key performance indicators between all platforms
