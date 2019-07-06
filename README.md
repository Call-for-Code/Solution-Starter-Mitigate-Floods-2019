# Solution Starter: Building Back Better to Reduce the Impact of Future Disasters

This solution starter was created by Team Two at the United Nations Human Rights Office in Geneva, Switzerland on June 3-4, 2019. It features contributions by technologists from Capgemini, Lloyds, RBS, Deutsche Telekom, and IBM. 

## What's the challenge?

Enhance resiliency and integrate disaster risk reduction during the recovery, rehabilitation, and reconstruction phase. Consider how to use technology-driven solutions to take action in anticipation of events, strengthen key infrastructure including buildings, roads, and hospitals, and ensure capacities are in place for effective response and recovery at all levels in the future.

## Why is this needed?

Research shows when countries rebuild stronger, faster, and more inclusively after a natural disaster, the impact on individuals' livelihood and well-being can be reduced by more than 30 percent, cutting losses from $555B to $382B per year.  As climate change increases, countries will benefit from placing an even greater priority on more resilient, swift, and inclusive recovery and reconstruction processes. Building back better, stronger, and faster after a natural disaster is one of the best ways to reduce impact and end the cycle of poverty.

## Overview

Water-related disaster events are becoming more frequent and more severe, leading to specific issues for affected communities. Preventing floods and improving our response to them can significantly mitigate loss of life and property damage. How can technology help communities improve their flood prevention and response while ensuring access to clean water in the aftermath of a natural disaster?

Access to clean water immediately after a natural disaster is one of the greatest issues facing communities around the world.  After floods, even though there is no shortage of water, access to clean water that communities need for life is essential.

Use the proposed solution idea below to inspire what you build to address this problem through your own custom Call for Code submission.

## Video

[![Call For Code Solution Starter Kit: Building Back Better](https://img.youtube.com/vi/JQzkbc8sEjk/0.jpg)](https://www.youtube.com/watch?v=JQzkbc8sEjk)

## The idea

The team approached the problem by proposing a two-part solution; one is a mobile app that helps flood victims respond to disasters and another is a dashboard for authorities that can use existing datasets (such as which populations are most at risk) with real-time situational data to prioritize response.

Beyond real-time response, the app incentivizes users to prepare long ahead of dire situations by using gamification. Users create personalized evacuation plans in case their area is impacted by a flood.

## How it works

There is a lot of information available before and during disasters, but it does not fully reach the potential to help the survivors. Although there has been an increased surge for mapping geodata, this data only includes general risks, and does not incorporate exposure and the vulnerability of the victims. This is because the information is not personal and relevant.

The mobile app would provide a personalized training program that allows the user to self-report important information, discover his or her potential for risks, and prepare a personalized escape route. This user data would flow into a big data visualizations dashboard for first responders with data-set mapping and links to government organizations. The dashboard helps responders prioritize their teams and focus on the most vulnerable people, sending out notifications and guidance to the survivors.​

## Additional diagrams and documentation

![Challenge 2 Architecture 1](/images/Challenge_2_Architecture_1.png?raw=true "Challenge 2 Architecture 1")

The solution that we propose addresses the concerns from the survivor's perspective. Before the disaster, we suggest a personal training program. With gamification we incentivize potential survivors to find, and prepare a personalized escape route. This enables the survivor to more efficiently escape the disaster, and brings a feeling of being in control. During the training program, personalized needs and tags are opted in, that can provide personal insights and advice, and enables first responders to address the needs of the survivor.

1. The end user installs a custom mobile application or visits a web application accessible from their mobile device before a disaster.
2. They can then configure their profile by going through a series of steps in a game-like fashion that builds a context around their unique situation before.
3. With this profile data stored in a central location, local authorities can understand their particular needs and if they fit into a vulnerable community category. Relevant information can then be pushed to them.

![Challenge 2 Architecture 2](/images/Challenge_2_Architecture_2.png?raw=true "Challenge 2 Architecture 2")

Big data visualization sits at the core of the solution, enabling the planner to take informed decisions during the disaster: integrated with personal disaster app, 3rd party datasets and having a direct link with governmental body budgets. Given the data collected from the survivors, available on the dashboard, the planner would be able to prioritize the teams to focus on the most vulnerable people, sending out notifications to the survivors.

1. Local authorities and disaster management agencies build up a threat model about the community using a variety of datasets
1. These pieces of information are stored and versioned as needed for historical access to train a threat model.
1. Watson Machine Learning then creates an model based on the user and threat information.
1. The recommendations for prioritizing response is then plotted on a map.
1. That information is then displayed in a dashboard (or pushed to incident responders).

## Data sets

- https://callforcode.weather.com/register/
- https://www.usgs.gov/products/data-and-tools/real-time-data/floods
- https://www.census.gov/data.html
- https://sedac.ciesin.columbia.edu/
- https://www.usgs.gov/products/maps/topo-maps

## Tech to implement the solution

* ### Possible IBM Cloud services

  - https://www.ibm.com/cloud/push-notifications
  - https://cloud.ibm.com/catalog/services/speech-to-text
  - https://cloud.ibm.com/catalog/services/watson-assistant
  - https://cloud.ibm.com/catalog/services/mobile-foundation
  - https://cloud.ibm.com/catalog/services/watson-studio
  - https://cloud.ibm.com/catalog/services/machine-learning
  - https://cloud.ibm.com/catalog/services/cloud-object-storage

* ### IBM Code Patterns and tutorials
  - https://developer.ibm.com/tutorials/use-drones-after-floods-to-help-survivors-watson-visual-recognition/
  - https://developer.ibm.com/patterns/create-ios-app-uses-builtin-custom-classifiers/
  - https://developer.ibm.com/patterns/weather-forecasting-for-ios/
  - https://developer.ibm.com/patterns/tag-based-push-notifications-for-hybrid-mobile-applications/
  - https://developer.ibm.com/patterns/tone-analyzer-for-ios/
  - https://developer.ibm.com/patterns/perform-a-machine-learning-exercise/
  - https://developer.ibm.com/patterns/generate-insights-from-multiple-data-sources-using-watson-studio/

* ### Possible open source technologies
  - https://github.com/pixiedust/pixiedust

## Resources for futher reading, research, and learning
- https://www.unisdr.org/archive/58108
- https://www.youtube.com/watch?v=20bknRt2jFQ
- https://www.unocha.org/middle-east-and-north-africa-romena/egypt

## License

This solution starter is made available under the [Apache 2 License](LICENSE).
