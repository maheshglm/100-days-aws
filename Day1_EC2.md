EC2
===
* https://towardsaws.com/100daysofaws-day-1-ec2-346c40430fae
* It is the fundamental compute service in AWS, many other services are built on top of it
* EC2 is secure, resizable compute capacity in AWS cloud
* Ability to chose from hundreds of different instance types
* 4 different pricing options
    * On-Demand
    * Reserved Instances
    * Spot Instances
    * Savings plans

On-Demand
===

* pay for the computing capacity by the hour
* ability to stop & start instances whenever we need
* Costly pricing option for EC2
* able to change compute capacity on fly
* Best use cases:
    * Short term, Spiky or unpredictable workloads
    * Test & Dev environments


Reserved Instances
===

* It offers up to 75% savings compared to on-demand pricing
* with payment all upfront 3-year plan provides biggest savings
* Best use cases:
    * Steady-state applications
    * Applications require reserved capacity with long term use

Spot Instances
===

* cheapest option
* bid for unused EC2 capacity from AWS at discounted price
* but potential downtime if AWS reclaim resources if bid price goes higher
* Best use cases:
    * Applications that are feasible at extremely low cost
    * used in auto scaling groups as they will be used temporarily when usage peaks for the application





