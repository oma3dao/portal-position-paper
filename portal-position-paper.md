# Portals Unleashed:  Creating a teleportation standard to connect the metaverse

## Introduction
In the realm of the metaverse, the concept of 'portals' is emerging as a transformative technology set to revolutionize the way we interact with digital spaces. Similar to how the advent of high-speed transportation networks during the industrial revolution connected commercial centers, or how the HTTP standard facilitated the linking of information silos, portals in the metaverse promise to create a new era of connectivity, accessibility, and productivity.

The industrial revolution was fueled, in part, by advancements in transportation technology. Railroads, highways, and airports served as critical conduits, knitting together disparate commercial hubs and facilitating the free flow of goods, services, and people. These networks of physical connectivity exponentially increased productivity and accelerated the pace of economic growth.

Likewise, the introduction of the HTTP standard in the digital realm was a watershed moment in the evolution of the internet. It broke down information silos, connected isolated data repositories, and enabled the seamless transfer of knowledge across the globe. In essence, HTTP acted as a universal translator, allowing diverse systems to communicate and interact, and led to an unprecedented explosion in the availability and accessibility of information.

Metaverse portals have the potential to be the next pivotal development in this lineage of transformative technologies. Just as railroads and highways connected physical spaces, and HTTP linked digital repositories, portals promise to bridge disparate metaverse environments. They provide a means of 'transportation' within the digital realm, enabling users to move seamlessly between different metaverse platforms, thereby enhancing accessibility and engagement.The development and standardization of portaling technology stand as the next frontier in the evolution of the metaverse, with the potential to unlock new levels of connectivity, commerce, and shared experiences within the digital realm.

Railways, highways, and the Internet are built on widely accepted standards and a metaverse portal system needs to take the same approach.  Building good standards is not an easy task.  There are countless examples of standards that had interoperability issues initially (Bluetooth) or use cases with competing standards (the current electric vehicle charging infrastructure).  Luckily there exists a body of knowledge and processes that consortiums can use to avoid such issues.  OMA3 leverages these best practices.  

OMA3 is a consortium of Web3 metaverse platforms, game developers, and infrastructure providers. The goal of OMA3 is to ensure virtual land, digital assets, ideas, and services are highly interoperable between platforms and user owned. OMA3 is open for any organization to join.  The OMA3 Portaling and Mapping Working Group (PMWG) is currently the most active group in OMA3.  Its scope is the development and maintenance of portaling and mapping specifications, and the PMWG’s portaling standard is the focus of this paper. 

The PMWG believes that portals have the potential to revolutionize the way we interact with the metaverse. Portals could make the metaverse more accessible, immersive, and engaging. They could also create new revenue streams for software developers.  However, there are still a number of challenges that need to be addressed before portals can be widely adopted. Although the portaling standard is far from complete, the PMWG is committed to addressing these challenges and making portals a reality. 

The PMWG is currently focused on defining the technical requirements for portals.  It has completed a use case description and a preliminary threat model.  Future tasks include developing a portaling protocol, creating a portal registry, and educating the community to spur adoption.  The purpose of this paper is to educate the Web3 community on the potential of a metaverse-wide teleportation system and to solicit more input and contributions from interested parties as we move to the next steps of the standardization process.

## Executive Summary

In this position paper we delve into the transformative technology of 'portals' within the metaverse and how they promise to redefine our interaction with digital spaces. The OMA3 Portaling and Mapping Working Group (PMWG) takes center stage in this endeavor, focusing on the development and maintenance of portaling specifications.

The paper provides a comprehensive description of the OMA3 portal system, defined using the Unified Modeling Language (UML) for clarity and precision. We outline the benefits and challenges of a universal metaverse portal system for various stakeholders, categorized into consumers, businesses, and platforms. While acknowledging the hurdles, we emphasize the potential benefits and the revolutionary shift that such a system can bring to the metaverse.

The ideal portal system, we argue, should be intuitive, cross-platform, flexible, and performant. It should respect the uniqueness of each platform, offer seamless transition between different metaverse worlds, and cater to varying degrees of Web3 adoption. The significance of performance metrics, such as throughput, latency, reliability, and security, is highlighted, underlining the importance of a robust, efficient, and user-friendly portal system.

The paper overviews the importance of widespread adoption and specification quality in the success of a standard. OMA3, with its extensive representation from top Web3 metaverse companies, is well-positioned to make its portal system the de facto standard in Web3. The focus on specification quality is reflected in OMA3's operational procedures, governance models, and legal structures, which are closely modeled after successful industry alliances.

We detail the current progress in the development of the portaling standard, outlining the step-by-step process followed by OMA3 and how it mirrors the approach of top industry alliances. The paper concludes with a call for more participation from the Web3 community, inviting expertise and active involvement in the OMA3 working groups. Overall, this paper not only serves as an educational guide on the potential of a metaverse-wide teleportation system but also as an invitation to join this groundbreaking initiative.

## Background

The concept of portal technology in virtual worlds has its roots in various forms of media, ranging from literature to video games. One of the early literary examples of portals in virtual worlds is Neal Stephenson's 1992 science fiction novel, "Snow Crash." The novel introduced the concept of the metaverse, a vast virtual reality space where users interact through avatars and travel between different environments using portals.

![Figure 1](https://github.com/oma3dao/portal-position-paper/blob/main/oma3-portal.jpg)

In the realm of video games, the use of portals can be traced back to classic titles like "Doom" (1993) where teleporters were utilized as a mechanic to traverse the game's labyrinth-like levels. "Myst" (1993), with its iconic linking books, allowed players to travel between different ages or worlds, pioneering the concept of inter-world portaling. The "Ultima" series (1981-1999) was also known for its moongates, magical portals that provided instant transportation between different locations within the game world.

More recently, Valve's "Portal" series (2007-2011) took the concept to a new level, making portals a core mechanic for puzzle-solving and navigation in a 3D environment. "No Man's Sky" (2016) features teleporters for interstellar travel between discovered space stations and player bases. In "Fortnite" (2017), rifts function as portals, allowing players to teleport around the map. 

Beyond games, portals have been employed in various virtual world platforms. Second Life, a virtual world launched in 2003, allows users to create teleportation devices for moving between different locations within the world. VRChat, a social VR platform released in 2017, enables users to create and share custom virtual worlds interconnected by portals. Similarly, platforms like Decentraland and The Sandbox, both launched in recent years, utilize portals to navigate between different parcels of virtual land within their blockchain-based metaverse worlds.

Overall, the history of portal technology in virtual worlds spans several decades, from early video games to contemporary virtual reality and blockchain platforms. The continued evolution and implementation of portal technology promise a future where seamless navigation and interaction across diverse digital spaces become the norm.

## The OMA3 Portal System

The OMA3 portal system, tentatively named the Inter-World Portaling System (IWPS), is essentially an inter-world version of the intra-world teleporting systems described above.  In other words, OMA3’s portal system allows travel between different worlds, not just locations in the same world.  To be more specific, we have defined two portal system use cases using UML (Unified Modeling Language) to reduce confusion moving forward.

UML use case descriptions are commonly used by consortiums as the first step in a standardization process.  Use cases describe the main goals and functions of a “system” (in this case, IWPS) from the perspective of the external entities that interact with it. These entities are called “actors” and they can be humans or non-humans (e.g.- software applications or hardware).

### Portal Actors

A use case consists of a sequence of actions that shows how actors and the system collaborate to achieve a specific outcome or perform a certain task (in this case, two tasks). OMA3 has defined the following actors for IWPS use cases:

  * User- The User is an entity (most likely a human, but it could be machine-based) that operates in real life and operates one or more Avatars in one or more Metaverse Platforms.
  * Asset- An avatar or an item, owned by the User or a Platform.
  * Avatar- A graphical representation of the User in a Platform.  If the Platform is a first-person Platform, the Avatar is the object the Platform uses to identify the User as an entity in the Platform world.
  * Item- A thing belonging to the Avatar on the Originating Platform, which the Avatar may bring with it to the Destination Platform.
  * Platform- The software that creates a virtual world that users can explore. All the Platforms available to a User defines the Metaverse.
  * Originating Platform- the Platform from which the Avatar starts.
  * Destination Platform- the Platform the Avatar goes to after the portaling process.
  * Destination Location- address of the location in the Destination Platform
  * Service- A software that refers to an action of helping or doing work for an individual platform or many platforms.
  * Portal UI- A Service that provides a user interface element within a Platform that allows the initiation of the teleportation of an Asset to a Destination Location in the Metaverse.
  * Identity Service- A Service that allows a User to log in to a Platform, either manually or automatically.
  * Platform Registry- A Service that stores all the Platforms that support the OMA3 portaling standard.
  * Asset Transfer System- A Service that transfers Assets (e.g.- Avatars and Items) between Platforms, and possibly the infrastructure these Platforms are built on (e.g.- blockchains).
  * Inter-Platform Messaging System- A Service that sends messages between Platforms.

These actors interact with each other to perform two different but related tasks- portal utilization and portal creation.

![Figure 2](https://github.com/oma3dao/portal-position-paper/blob/main/portaling-actors.png)

### Portal Utilization

  1. A User uses the Identify Service to log into the Originating Platform and starts controlling the Avatar.
  2. User uses a Portal UI to initiate the teleportation of an Avatar to a Destination Location.  This use case assumes that the destination already is determined by the Portal.  The Portal can be a visual “door” in the Platform that the Avatar “walks through”.  It can be a UI toolbar that allows the User to enter a destination “address”.  It may or may not offer the User a dialog to confirm the intended destination.
  3. Originating Platform triggers IWPS to initiate the teleportation.
  4. Portal system launches the Destination Platform and notifies the Destination Platform of the incoming Avatar and the Destination Location.
  5. Destination Platform gives portal system instructions.
  6. User uses Identity Service to log into the Destination Platform, possibly going through steps to register the User or possibly doing it automatically.
  7. Avatar appears in the Destination Platform (with the native representation in the Destination Platform) at the Destination Location specified by the Originating Platform Portal, or other location the Destination Platform specifies that overrides the Destination Location based on the Destination Platform rules.
  8. Optional- Portal system may use an Asset Transfer System to transfer Items to the Destination Platform.  Such Items must be messaged to the System by the Originating Platform.
  9. Optional- Avatar can return to the Originating Platform using a Portal UI at the Destination Location (or overridden location) that has stored the location of the Originating Platform Portal UI. 

![Figure 3](https://github.com/oma3dao/portal-position-paper/blob/main/portal-utilization-flow.png)

### Portal Creation

  1. Destination Platform registers itself with the Platform Registry, including a default Destination Location and persistence support (persistent and/or ephemeral Portals)
  2. Optional- Platform Registry may require Destination Platform to pass an interoperability test in order to be registered.
  3. Originating Platform queries Platform Registry for a list of Destination Platforms.
  4. User or Originating Platform (depending on Originating Platform implementation choices) chooses Destination Platform (and optionally Destination Location) and creates the Portal.
  5. Optional- User or Originating Platform (depending on Originating Platform implementation) records the desired Destination Location in the Portal.
  6. User or Originating Platform decides if the Portal is persistent, depending on Originating Platform implementation.
  7. Optional- Originating Platform sends message to Destination Platform using the Inter-Platform Messaging System to set up a return destination Portal with the proper parameters for returning an Avatar from the Destination Platform back to the Originating Platform.


## Portal Benefits

Although we believe a universal metaverse portal system will be a net benefit to the ecosystem, it is worthwhile going into more detail on the benefits and challenges of this system to ecosystem stakeholders.  We divide stakeholders into three categories:

**Consumers-** consumers that participate in the metaverse.  

**Businesses-** individuals and organizations that leverage the metaverse for a business purpose. 

**Platforms-** virtual worlds that create the experience of users and businesses using software and sometimes hardware (the same Platforms in the UML model above).  

We start with benefits and then review the challenges.

1. Variety and Exploration: Portaling allows users to more easily explore and experience a wide variety of digital environments. This can provide a sense of novelty, adventure, and limitless possibility.  We believe this is the primary benefit to IWPS.

2. Social Interaction and Networking: Users can more easily meet and interact with people from different metaverses, potentially diversifying their social networks and opening up opportunities for collaboration or friendship. 

3. Learning and Skill Development: Making it easier to navigate multiple metaverses can help users develop a range of skills, including digital literacy, problem-solving, and adaptability.  Imagine the complexity of quests that span multiple virtual worlds.

4. Personalization and Creativity: Users can express their creativity and individuality by creating avatars, possessions, or environments that are adaptable to different metaverses.

5. Access to Diverse Content: Users will be encouraged to access a wider range of content, experiences, and services because of the ease of portaling between metaverses.

6. More Metaverse Customers: Businesses who are currently active in a limited number of platforms will see more customers as IWPS will make it easier for users to visit these platforms.

7. Metaverse Expansion: Businesses can more easily justify a presence across many more platforms as IWPS allows them to create portals between their locations in all the platforms.  

8. Data Collection and Analysis: With the appropriate permissions from users, businesses can use portals to collect and analyze data from multiple platforms, which could provide valuable insights into user behavior and preferences across different digital environments. 

9. Links to the Physical World:  Platforms based in the real or physical world can set up portals to Platforms based in fantasy.  For example, a virtual world that augments a physical retail store (AR metaverse) can have a portal that goes to a fantasy virtual retail store, ultimately giving users more choice.

10. Higher value of goods:  Items that can be brought from one metaverse to another through a portal will be valued more highly than items that are constrained to a single platform, especially as there’s always the risk of the platform going away or decreasing in popularity. 

11. Metaverse synergies:  Portaling can be the start of further collaborations between metaverse platforms.  

12. More businesses:  When businesses expand their presence to more platforms, this brings in more revenue to the metaverse as a whole.  It also makes the metaverse more attractive to users, feeding into a virtuous cycle of metaverse adoption.

## Portal Challenges

1. Complexity and Learning Curve: It can be challenging for users to understand and navigate the unique rules and structures of different metaverses, especially for users new to virtual worlds. This could lead to a steep learning curve and a frustrating experience.  World designers must be careful to ensure users are prepared for portals before they can be used.  For example, perhaps users must reach a certain level before portals are available, as is the case with many MMORPGs that implement intra-world portals.

2. Digital Divide: Portaling might exacerbate the digital divide, as some users may not have the skills or hardware needed to support multiple types of worlds, leaving IWPS to only those that can understand and afford it.  This is a problem for the metaverse as a whole, but it is exacerbated by portals.

3. Terms of Service Inconsistency: Currently different platforms have different terms of service, differing on user rights such as item ownership, world governance, etc.  These differences may catch users by surprise and frustrate them.  The PMWG must work hard to harmonize such terms as much as possible, and notify users appropriately when they diverge.

4. Interoperability Issues: Users might face limitations or barriers when moving between metaverses if the standard is not designed or implemented properly and there are interoperability issues between different digital environments.  The ultimate goal for the OMA3 portal system is true interoperability with avatars and items, and this is a challenging problem to solve.

5. Complexity and Cost: Managing a business presence in multiple metaverses could be complex and costly. It may require significant resources, including time, money, and expertise, to understand and navigate the unique rules and structures of each metaverse.

6. Data Security and Privacy: Portaling could raise concerns about data security and privacy. Businesses will need to ensure they comply with data protection regulations across different metaverses, which may vary widely.  Industry self-imposed requirements, either formal or informal, could be a solution here.

7. Interoperability Issues: Not all metaverses may be compatible or interoperable, which could limit the effectiveness of portaling. OMA3 needs to play a large role in ensuring a clear standard and Platform compliance with the standard to address this challenge.

8. User Churn:  Leaving one world through a portal is the equivalent of clicking off a website to go to another.  The originating world loses the revenue potential or engagement of the user to another.  The hope is that IWPS brings more users overall to the metaverse, and the rising tide lifts all boats.

9. Platform Clash:  An influx of users from a world with completely different social norms from the destination world could be a disruption to long-time participants in the destination world.  

10. Technical Complexity:  It is a significant engineering challenge to build a truly interoperable portal system that not only transports avatars and identities, but also reconciles the graphic rendering and game mechanics of such.  Addressing items that are carried by avatars through portals adds to the challenge.  Luckily OMA3 is not alone in trying to solve this.  Other organizations include Khronos Group, Metverse Standards Forum, and Open Metaverse Initiative.

11. Adoption: Even if a universal standard is developed, getting all platforms to adopt and implement it can be a challenge. This requires extensive collaboration, negotiation, and consensus-building among different stakeholders.  

12. Evolution: The metaverse and associated technologies are rapidly evolving. The standards must be flexible and adaptable to accommodate future technological advancements and changes in user behavior.  OMA3 must be nimble enough to meet this challenge.

In addition to the above challenges, there exists a wide range of others that revolve around cybersecurity threats and error cases.  OMA3 is still in the process of identifying these challenges, but here are a few examples:

  * A number of things can happen during the teleportation process, and the system needs to recover gracefully if they occur.
  * A malicious actor can create a compromised destination world, or circumvent the portaling system to steal assets.
  * Destination worlds need the ability to control the experience of incoming portal travelers, similar to border control.

## Goals 

In addition to addressing the various challenges, threats, and error cases outlined above, we believe the ideal portal system needs to have the following characteristics:

**Intuitive:**  When users use the system, we want their experience to make sense. Usability features, such as sign-on steps, platform launch processes, and user setup, should be streamlined to provide a smooth experience.

**Cross platform:**  Metaverse platforms are built on different technology stacks and a truly universal portal system needs to support all possibilities.  We need a platform-agnostic solution that allows seamless transition between metaverse worlds. The solution should support various technologies, including web-based APIs, SDKs, blockchain, hardware, and operating systems. It must cater to both 2D and 3D worlds and integrate with existing wallets and app stores

**Flexible:**  Not only are platforms built on different stacks, they also have uniqueness of experience.  The system needs to honor platform sovereignty as much as possible without confusing users or sacrificing interoperability.  Metaverse platforms also have different levels of Web3 adoption.  Some put all mechanics and assets on-chain.  Others are mostly centralized with only a few assets minted as NFTs.  IWPS should be able to support as wide a range of Web3 adoption as possible.

**Performant:**  Performance is crucial, with metrics such as throughput, latency, and reliability being key considerations. Additionally, the system should account for potential user limitations, such as new users without an account or uses without the destination platform downloaded.  The solution should offer high uptime, DDoS protection, and censorship resistance, while also maintaining privacy and ensuring interoperability.

## Why OMA3

There are two main factors that determine the success of a standard.  The overwhelming factor is adoption, especially when there are competing systems.  Even if a standard has technical issues, it can recover if it has widespread industry support.  Bluetooth is a prime example.  Bluetooth initially had compatibility issues, but it had so much industry support that it was able to recover and become the defacto standard anyway.

OMA3 was created by top Web3 metaverse companies and has grown since then to represent millions of active metaverse users.  OMA3 cannot force members to adopt its projects, but if just a fraction of OMA3’s membership adopts IWPS it will be well on its way to becoming the defacto standard in Web3.  Of course, the number of current active Web3 metaverse users is only a fraction of the number of Web2 metaverse users but OMA3 is actively working with other standards bodies such as Metaverse Standards Forum to ensure it gets input from the Web2 industry as well.

The second main factor for success is the quality of the project.  Is the specification accurate enough to ensure compatibility between different implementations?  Is there a program to ensure poor implementations don’t harm the system?  Is it secure?  Does it provide the anticipated benefits?  Is it easy to use?  OMA3 is modeled after organizations that have already provided the world with high quality standards that successfully answered these questions.  Some of these standards are household names:  WiFi, Bluetooth, USB, and more.  These organizations use very similar legal structures, governance models, and operational procedures to OMA3.  OMA3 is essentially a carbon copy of these successful industry alliances.

Besides organizational structure, widespread participation is also a determining factor in the quality of a project.   A consortium can have a membership that represents the vast majority of the industry, but if these members are not actively participating in working groups it does not matter.  Iron sharpens iron, and active and inclusive debate builds great standards.  Participation in PMWG meetings is growing every week, but one of the purposes of this paper is to attract more organizations to our process.  

## Where we are now

As mentioned above, OMA3 mimics the process of the top standards-creating industry alliances in the world.  You can read more about the process in the blog post, but here’s a short summary:

Step 1:  Create detailed and clear use cases, so all participants understand what is being built.

Step 2:  Identify threats that can derail the use cases.

Step 3:  Build requirements that can be used to judge specification proposals

Step 4:  Solicit specification proposals from the membership.  This is vastly more efficient than group spec writing. 

The PMWG portaling work is now at Step 3.  A few PMWG participants have even built prototypes that will be updated to meet the specifications voted on by PMWG:

[Space prototype](https://drive.google.com/file/d/1bY0TEDJBoKR4pAP6Rt4z8E27scSe5-oa/) utilizing IPSME relying on Industry of Integrations  
[Made For Gamers prototype](https://www.youtube.com/watch?v=W7FXogTn2M8) using portals to travel between Unity and Unreal worlds.


## Call for Community Participation

OMA3 needs more participants to ensure the highest quality portaling standard.  PMWG is actively recruiting Web3 metaverse platforms and companies that are currently developing portal systems.  Our Asset Transfer Working Group (ATWG) is also important to PMWG as assets may need to be transferred across blockchains to allow users to bring assets through portals.  If you have cross-chain asset transfer expertise we need you as well.

## Authors

This paper was written using contributions from the following individuals:

Batis Samadian, CEO of Space, Vice Chair of OMA3  
Alfred Tom, Acting Executive Director of OMA3  
Judy Chen, Growth Wivity  
Paul-David Oosthuizen, CEO of Made For Gamers  
Idan Zuckerman, Co-CEO of Upland  
Nate Peace, Director at Unstoppable Domains  
Riccardo Sibani, CPO Allice Foundation  
Joel Dietz, CEO Metametaverse  
Somnath Banerjee, CTO of MetaJuice  
Tokuro Uhara, CEO Crosstech  
Anthony Knode, CFO Crosstech  
Jörg Brakensiek, CTO Wivity  
Gino Cingolani, Decentraland Foundation  
Stilyan Mitrev, Product Lead of EnterDAO   
Marc McGinley, Animoca Brands  
Lucas Shrewsbury, CTO of The Sandbox  
David Saavedra, CEO Hash Trust  
Hrish Lotlikar, CEO, SuperWorld
 
## Public Comments
Create an issue on Github:  [https://github.com/oma3dao/public-documentation/](https://github.com/oma3dao/public-documentation/)   
Comment in Google Docs: [https://docs.google.com/document/d/13MW6ME6lwXBEnwXFShQPSHtjtGHSsXZBEZPjQkWqRAY/](https://docs.google.com/document/d/13MW6ME6lwXBEnwXFShQPSHtjtGHSsXZBEZPjQkWqRAY/edit)

## Get Involved

Become a member:
[https://www.oma3.org/join](https://www.oma3.org/join)

Joint the community:
[@oma3dao](https://www.twitter.com/oma3dao)   
[https://www.linkedin.com/company/oma3/](https://www.linkedin.com/company/oma3/)

## Stay Connected

Contact us:
[info@oma3.org](info@oma3.org)

Subscribe to our newsletter:
[https://www.oma3.org/join-newsletter](https://www.oma3.org/join-newsletter)

