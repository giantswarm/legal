# Service Level Agreement - Giant Swarm GmbH

This Giant Swarm Service Level Agreement ("SLA") is a policy governing the use of the services provided by Giant Swarm GmbH ("GS") and its connected systems under GS management unless otherwise noted in this document and under the [Giant Swarm Terms of Service](https://giantswarm.io/terms/) ("TOS") as available under [https://giantswarm.io/terms/](https://giantswarm.io/terms/) between Giant Swarm GmbH and users of GS ("you"). This SLA applies separately for each organisation that one or multiple user accounts are connected to. We reserve the right to change the terms of this SLA in accordance with the TOS.

## 1. Service Commitment

GS will use commercially reasonable efforts to make the Giant Swarm Service available with a Monthly Uptime Percentage (defined below) of at least 99.95%, in each case during any monthly billing cycle (the "Service Commitment"). In the event GS does not meet the Service Commitment, you will be eligible to receive a Service Credit as described below.

## 2. Definitions

Generally the definitions as made and used in the TOS apply.

- "Monthly Uptime Percentage" is calculated by subtracting from 100% the percentage of minutes during the month in which the Giant Swarm Service, as applicable, was in the state of "GS Unavailable." Monthly Uptime Percentage measurements exclude downtime resulting directly or indirectly from any GS SLA Exclusion (defined below).

- “Kubernetes Master” is the controlling unit(s) of your Kubernetes Cluster.

- “Nodes” are the compute instances of your Kubernetes Cluster.

- "Cluster Storage" is our persistent storage facility, providing you with long-term data storage.

- "GS Node Unavailable" and "GS Node Unavailability" means that all your Nodes cannot be reached from outside of the GS network and due to reasons that are not in the sphere of the respective user.

- "GS Master Unavailable" and "GS Master Unavailability" means that your Kubernetes Master cannot be reached from outside of the GS network and due to reasons that are not in the sphere of the respective user.

- "GS Unavailable" and "GS Unavailability" in terms of Cluster Storage means that you were not able to connect to the storage from inside the GS Network and due to reasons that are not in the sphere of the respective user.

- A "Service Credit" is a monetary credit, calculated as set forth below, that we may credit back to an eligible account.

## 3. Service Commitments and Service Credits


For GS Node Unavailability, Service Credits are calculated as a percentage of the total charges paid by you for Giant Swarm Services affected for the monthly billing cycle in which the GS Node Unavailability occurred in accordance with the schedule below.

| Monthly Uptime Percentage  | Service Credit Percentage |
|----------------------------|---------------------------|
| Less than 99.95%           | 10%                       |
| Less than 99.90%           | 20%                       |
| Less than 99.85%           | 30%                       |
| Less than 99.80%           | 40%                       |
| Less than 99.75%           | 50%                       |


## 4. Reporting GS Unavailability

To receive a Service Credit, you must submit a claim by opening a case via an email to support@giantswarm.io or via our support tools. To be eligible, the credit request must be received by us within 10 days of the GS Unavailability and must include:

a) the words "SLA Credit Request" in the subject line;

b) the dates and times of each GS Unavailability incident that you are claiming;

c) the affected Kubernetes Master and Nodes or Cluster Storage unit; and

d) your request logs that document the errors and corroborate your claimed outage (any confidential or sensitive information in these logs should be removed or replaced with asterisks).

## 5. Limitations

5.1. You are not entitled to a credit if you are in breach of the TOS with GS (including your payment obligations to GS) until you have cured the breach. You are not entitled to a credit if downtime would not have occurred but for your breach of your agreement with GS or your misuse of the Services. You are not entitled to a credit for downtime or outages resulting from denial of service attacks, virus activity, hacking attempts, or any other circumstances that are not within GS's control.

5.2. Notwithstanding anything in this Service Level Agreement to the contrary, the maximum total credit for the monthly billing period, including all guaranties, shall not exceed 50% of your GS fee for that billing period. Credits cannot not be carried forward to future billing periods.

## 6. GS SLA Exclusions

The Service Commitment does not apply to any unavailability, suspension or termination of a Kubernetes Master or Nodes or Cluster Storage, or any other Kubernetes Master or Kubelet or Cluster Storage performance issues: (i) that result from a suspension described in Section 4.1 of the TOS; (ii) caused by factors outside of our reasonable control, including any force majeure event or Internet access or related problems beyond the demarcation point of the Kubernetes Master, Nodes or Cluster Storage; (iii) that result from any actions or inactions of you or any third party; (iv) that result from your equipment, software or other technology and/or third party equipment, software or other technology (other than third party equipment within our direct control); (v) that result from failures of individual instances or volumes not attributable to GS Unavailability; (vi) that result from any maintenance as provided for pursuant to the Giant Swarm Terms; or (vii) arising from our suspension and termination of your right to use Giant Swarm Services in accordance with the Giant Swarm Terms (collectively, the "GS SLA Exclusion"). If availability is impacted by factors other than those used in our Monthly Uptime Percentage calculation, then we may issue a Service Credit considering such factors at our discretion.
