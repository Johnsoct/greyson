# Greyson

To my son, who I am dedicating this adventure to,

I hope you don't grow up thinking I work too much, but if you do, I hope I've taught you a few things.

1. I am not under the illusion I work more than necessary "for you." I work so much because, to me, this is a big piece of what it means to be a man, a husband, and a father.
1. The hard path is almost always the right path
1. You can do whatever you want as long as you don't get in someone else's way

## The goal

**Transition from a lead web frontend engineer into a role building and operating systems supporting real-world research or field operations.**

I want to maintain my role as a software engineer while expanding to hardware-adjacent and field-deployed systems - building data pipelines, edge services, and operational tooling for environments where reliability, observability, and on-site deployment matter.

Common names for this new role:

- RSE (research software engineer)*
- Scientific programmer
- Field systems engineer
- Data systems engineer
- Embedded systems engineer

*I will be referring to the position/role/industry I'm wanting to transition into as "RSE" for simplicity.

## The plan

Over the next three to five years, I'm going to teach myself the skills and gather the experience necessary to find a junior-to-mid-level RSE position.

As a self-taught frontend engineer, I've made the same mistake most self-taught engineers make - spending too much time "studying" instead of building things. However, there is a tremendous amount of foundational information I am aware I don't have which I absolutely need to understand, so I'll be reading and building concurrently. I will be intentionally avoid YouTube content, but I will be utilizing AI for learning and debugging.

As a new father, with another on the way, an intensive full-time job, three dogs, and a farm to manage, I can only dedicate one and a half to two hours every morning.

### Reading list

I do *intend* to read in the following order; however, I wouldn't usually put *Interview Design Patterns* and *Pheonix Project* at the top of the list, but I had already started *Interview Design Patterns*, and I hate not to finish what I start, and *Pheonix Project* is relevant to things going on at work right now.

I've included a personal reading list to serve as a break when needed between the highly technical reads. Ignore it if you don't care, but this is what I prefer to read in my freetime if not isekai novels.

*I will be utilizing audio books

#### Technical

1. Interview Design Patterns - common algorithms and interview prep
1. Pheonix Project - devops
1. Code: the Hidden Language of Computer Hardware and Software - first principles of how computers work
1. Computer Systems: a Programmer's Perspective - deep dive into a computer's systems
1. The Go Programming Language - my preferred, relevant "lower-level" language
1. Designing Data-Intensive Applications - scalability, consistency, reliability, efficiency, and maintainability of data
1. System Design Interview - high-level system design of common, everyday systems
1. The Clean Coder - disciplines, techniques, tools, and practices of software craftsmanship
1. Clean Architecture - impementation examples combining Clean Code and Clean Coder principles

#### Life/philosophical

1. Atomic habits
1. Beyond Order: 12 more rules for life
1. Wild at heart
1. Lions and scavengers

### Project list

Projects slowly progress from systems I've been wanting around my home which mostly consistent of integrating off-the-shelf systems to "full pipeline" projects implementing collection, storage, analysis, visualization, and insights.

*\*I'm going to buy a 3D printer this spring to expirement with making "hardware" for projects, such as cases, mounts, hooks, etc., and things around the farm, so any piece of a project I can make myself, I will attempt to do so.*

*\*Projects are subject to change.*

*\*Projects order is subject to change.*

#### Easy; integration of off-the-shelf products

1. Outdoor, point-to-point networking setup for my barns
1. NAS server
1. 4K camera system for my property

#### Medium; some custom hardware and software glue, partial pipeline

1. Tablet-focused home and family management system to manage chores, schedules, the greenhouse, equipment maintenance, view weather reports, etc. (think Skylight, but less expensive and extremely time consuming and less capable than a smartphone...)

#### Hard; custom hardware and software implementations, full pipeline

Interestingly enough, my wife and I have a big interest in gardening, mostly for self-sufficiency, and this spring, I'm converting an old 20x40 barn into a greenhouse. I'm not sure I could ask for a better opportunity to build projects which both teach me real world applications with real, useful data and are useful to my family.

I'm not an expert in how specific environmental conditions affect plant growth, so as of right now, my goal is to be able to collect, store, and visualize the data in various ways to react immediately to problematic conditions and see if I can draw my own insights as to how said condition affected growth or yield; however, it's my assumption these insights take years or multiple growth cycles (in a year-around greenhouse) to produce enough data to make fact-based claims; therefore, I am going to do everything in my power to get as many systems in place as quickly as possible so I can begin collecting data...

##### Collection and storage

1. Weather station - temperature, wind, and light sensors for real-time temperature data around my property, especially along the perimeter of my greenhouse
1. Greenhouse camera system - live feeds from all four corners of the greenhouse
1. Greenhouse monitoring system - temperature, humidity, soil, and light sensors in a grid-based configuration
1. Greenhouse watering system - automate watering schedules per bed based on the monitoring system with water usage analytics
1. Greenhouse bed camera system - daily timelapse of each bed

##### Visualization and insights

###### Web application

1. Interact with site maps for real-time camera and sensor information
1. Track and view plant growth and yield
1. View camera feeds
1. View camera timelapse data
1. View power consumption
1. View sensor data
1. View water consumption
1. Override the automated watering system
1. Correlate plant growth and yield with sensor data

###### Alert system

1. Scheduled watering did not happen
1. Power outage
1. Dangerous temperature
1. Soil in bed #1 is too wet or dry

###### Failure and manual override systems

And, although I have no clue what this would look like, I probably need a way to interact with different parts of the system locally and a way to override the system manually...

### Documentation
