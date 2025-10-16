# Machine-Learning-Data-Gathering
This is the repository that handles the dataset and features of the User Behavior
through the interaction with the keyboard and the mouse for the purpose of
understanding a presence of an Insider Threat and Account Takeover

This repository contains the dataset used in profiling a user through their interaction
with their personal computer.

**Objectives:** Profiling Users for Machine Learning

**Type of Data:** CSV Files or other structured format

**How data were acquired:** Client Agents Running in Cross Platform Environment

**Data Format:** Raw Data

**Parameters for Data Collection:** To model the behaviour of each individual with his/her
computer, we will consider keyboard, mouse


NB: The procedure of collecting the logs of keyboards and mouse activity of a user is sensitive because of the privacy implications of it.

## Account Takeover & Insider Threat

<details>
  <summary>Consent & Policy for Privacy Implications</summary>

  - Notify the user that you will collecting their keystrokes and mouse activity for better interactions
  - Notify them about the retention and scope of logging their events
  - Give them a chance to opt-out from the process if there is need required
</details>

<details>
  <summary>Data Computation & Implementation</summary>

  - Ensure you don’t collect raw keystrokes, passwords, PIIs (Personal Identifiable information) instead collect the aggregate of featured computation within the endpoint (e.g. averages, variances) not raw event streams
  - Compute these features on the endpoint and send anonymized scores to the ML systems.
</details>

### Data Collection
The agent which is the log/data collection components, will continuoulsy monitors the data generated when the
user interact with the keyboard and mouse. This information will then further be processed to obtain the
features

