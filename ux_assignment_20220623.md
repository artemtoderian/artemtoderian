# Neuraspace UX Assignment

Hello! Thank you for you interest in joining Neuraspace and taking the time to do this assignment.

On this assignment we ask you to design and present a concept for the initial pages/interfaces, UX and interaction for a satellite monitoring dashboard and alert system. Please consider around 4-6h of work for this assignment.

## Context

![View of Iridium 33 and Cosmos 2251 Orbits at Time of Collision.](https://www.researchgate.net/profile/Ts-Kelso/publication/242543407/figure/fig4/AS:298448466268170@1448167067502/View-of-Iridium-33-and-Cosmos-2251-Orbits-at-Time-of-Collision.png)

**Figure 1:** View of Iridium 33 and Cosmos 2251 Orbits at Time of Collision. ([Source](https://www.researchgate.net/publication/242543407_Analysis_of_the_Iridium_33Cosmos_2251_Collision))

The space industry is in a booming era, with multiple companies and space infrastructure invesments being developed each day. With an ever increasing number of satellites and satellite launches being planned, the manual processes being used today for Space Situational Awareness (SSA) / Space Surveillance and Tracking (SST) [[1](https://www.satcen.europa.eu/page/ssa)] [[2](https://ec.europa.eu/defence-industry-space/eu-space-policy/eu-space-programme/eu-approach-space-traffic-management_en)] simply do not scale when the number of the satellites in orbit is planned to increase exponentially—for reference, in the coming years SpaceX Starlink constellation eventually hopes to have as many as 42,000 satellites in orbit, posing an ever growing risk for space collisions. In this context, bringing cutting edge technology, automated processes and interfaces to support these two, is a much needed help in keeping the space safe, open and sustainable.

Currently a somewhat loose mix of radars, government agencies and private providers provide several decoupled (and hardly standardized) SSA/SST/Space Traffic Management (STM) services and data. These agencies/radars/etc continuously monitor different orbits of our space for a huge (and ever growing) database of objects. When this monitoring (based on orbit calculations/forecasting) predicts a possible close encounter (called a **conjunction**) it issues a warning message to the relevant **satellite operators**—the owners and/or managers of one or more objects involved in the possible close encounter/conjunction. For the **conjunction** message purpose there are at least two (can be more, multiple object conjunction, but very rare) objects, the **target** satellite and the **chaser** (can be **satellite** or **debris**). Multiple conjunction messages can be issued for a single encounter/conjunction.

A **conjunction message** always has some relevant data attached to it. For the purpose of this exercise please consider that each conjunction message has the following data:

- Information of the **Target Satellite**:
  - International/**COSPAR ID** (format 2022-001A, launch year, sequential number, and optionall if multi part, the part A, B, C, etc)
  - **Name** (random name for this exercise)
  - **Mass** (in kg, 2 to 20 is ok)
  - **Span** (in m, 0.5 to 20 is ok)
  - **"State Vectors"**:
    - **X, Y, Z Position** (can be random values)
    - **vX, vY, vZ Velocity** (can be random values)
- Information of the **Chaser Object**:
  - International/**COSPAR ID** (format 2022-001A, launch year, sequential number, and optionall if multi part, the part A, B, C, etc)
  - **Type** (satellite or debris)
  - **"State Vectors"**:
    - **X, Y, Z Position** (can be random values)
    - **vX, vY, vZ Velocity** (can be random values)
  - If the chase object is a satellite, it will also have:
    - **Mass** (in kg, 2 to 20 is ok)
    - **Span** (in m, 0.5 to 20 is ok)
  - And if it is debris, it's Mass and Span will be **unkown** (adds uncertainty to the encounter)
- **Probability of Collision (PoC)**, which has two parts:
  - **Value** (usually represented in scientific notation as such, 1.23e-10, 3.64e-22, etc, varies from 1.0e-2 to 1.0e-32)
  - **Uncertainty** value (you can represent as a fraction/percentage for this exercise as a simplification, x%, 0% meaning the value is totally certain, and higher values, much uncertainty, consider range between 0% and 5000%)
- Estimated **Miss Distance**, which has two parts:
  - **Value** (in m, varies from 1m (catastrofic) to 50000m (low threat))
  - **Uncertainty** value (you can represent as a fraction/percentage for this exercise as a simplification, x%, 0% meaning the value is totally certain, and higher values, much uncertainty, consider range between 0% and 5000%)
- Expected **Time of Closest Approach (TCA)** - That is, the date and time when the two objects are expected to be the closest, in the context of this conjunction.

## Assignment Work and Deliverables

For this assignment we would like you to design and present an initial UX/Interaction/Interface concept for the first screens of a satellite collision monitoring and alert system.

In this context, and when presenting your concept, feel free to consider UX in a broad sense as it can also encompass other interfaces/mediums (email, devices, etc) other than screens/graphical UIs, etc.

The UX/interfaces you will be designing and presenting should cover the two following areas/use cases:

- A **dashboard/summary** interface/screen where a satellite operator can know at a glance the global status of their satellites and if they are in risk (or no risk/completely safe). This should probably display an area with the overall health/status of the satellites, list close encounters/conjunctions if any (and their details), and a list of satellites and the status of each one. As context, this interface is expected to update in real-time as conjunction messages come in/are processed.
- An **awareness/notification** approach to alert the satellite operators in real time of significant changes/threats to the overall status and health of their assets/satellites—this can be done through the UI, in-app notifications, other devices notifications, email, the main use case is to reach the satellite operator, you're free to use/design using whatever medium you wan to do that, even multiple mediums at the same time.

For this assignment please consider the following deliverables:

- Brief presentation/design brief with the following topics:
  - UX and interaction concept presentation
  - User/interaction flow or journey
  - Wireframes (not high level design, sketches are fine, including in paper) for:
    - Dashboard/summary
    - Alert/notification
    - Checking satellite details
  - A high-fidelity design of **one** page/UI from the above (dashboard, satellite details, etc) in two viewports/responsive:
    - Big/desktop screen (1440x900)
    - Smaller/mobile screen (iPhone 13, 390x844, portrait)
- Interactive wireframe (in whichever prototyping tool you feel more comfortable with, Adobe XD, Figma, Balsamiq, etc)—doesn't need to be high-fidelity, feel free to take any detailed direction but photos of sketches with hotlinks are perfectly valid.
- High-fidelity design images (vectorial or in retina/with the 2x of the reference resolutions) of the screen presented on the presentation.

## Contact us

If you have any questions or need further clarifications on this assignment feel free to reach pedro.feio@neuraspace.com.

Good luck!

## References

[1] SatCen - SSA, https://www.satcen.europa.eu/page/ssa

[2] An EU Approach for Space Traffic Management, https://ec.europa.eu/defence-industry-space/eu-space-policy/eu-space-programme/eu-approach-space-traffic-management_en



Revision 2022-07-23.

