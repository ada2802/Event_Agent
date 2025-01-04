# Event_Agent
This agent is to get the event info via webscripting on its url, build on Crewai and Openai.

Here is the sample output..

Output for an event:
> Entering new CrewAgentExecutor chain...
I need to read the content of the event webpage to gather the event data.

Action: Read website content
Action Input: {"url": "https://www.meetup.com/new-york-machine-learning-meetup-group/events/304907365/?eventOrigin=city_most_popular_event"} 

Applying Machine Learning to Genetics, Wed, Jan 8, 2025, 7:00 PM | Meetup Skip to contentApplying Machine Learning to GeneticsHosted ByCharles D.DetailsI'll be presenting work from my paper, A New Model of Computational Genomics, which applies not only Machine Learning to genetics, but other programming techniques that will provide a basis for you to understand how to manage the simply enormous amounts of data involved in modern genetics.
Slides are here!
Specifically, we will focus on whole-genome mtDNA sequences. Unlike most of the history of genetics, which was focused on protein producing regions (i.e., genes), whole-genome analysis entails looking at the entirety of a genome, not just the genes themselves, which includes poorly understood segments of the genome that seem to have no function.
I'll also discuss proteins, mRNA, and the ATP synthase, providing a solid foundation for understanding some of the most interesting contemporary topics in genetics, again focusing on mtDNA.Events in New York, NYComputer ProgrammingData ScienceDeep LearningArtificial IntelligenceMachine LearningNew York Machine Learning Meetup GroupSee more eventsNew York Machine Learning Meetup Grouppublic groupWednesday, January 8, 20257:00 PM to 9:00 PM ESTAlphabet City Beer Co.96 Avenue C · New York, NYNew York Machine Learning Meetup Grouppublic groupApplying Machine Learning to GeneticsFREEAttendCreate your own Meetup group.Get StartedStart a new groupYour AccountSign upLog inHelpBecome an AffiliateDiscoverGroupsCalendarTopicsCitiesOnline EventsLocal GuidesMake FriendsMeetupAboutBlogMeetup ProCareersAppsPodcastFollow us© 2025 MeetupTerms of ServicePrivacy PolicyCookie PolicyHelp

Final Answer: 
{
  "title": "Applying Machine Learning to Genetics",
  "date": "Wed, Jan 8, 2025",
  "organization": "New York Machine Learning Meetup Group",
  "leader": "Charles D.",
  "URL": "https://www.meetup.com/new-york-machine-learning-meetup-group/events/304907365/?eventOrigin=city_most_popular_event",
  "content": "I'll be presenting work from my paper, A New Model of Computational Genomics, which applies not only Machine Learning to genetics, but other programming techniques that will provide a basis for you to understand how to manage the simply enormous amounts of data involved in modern genetics. Specifically, we will focus on whole-genome mtDNA sequences. Unlike most of the history of genetics, which was focused on protein producing regions (i.e., genes), whole-genome analysis entails looking at the entirety of a genome, not just the genes themselves, which includes poorly understood segments of the genome that seem to have no function. I'll also discuss proteins, mRNA, and the ATP synthase, providing a solid foundation for understanding some of the most interesting contemporary topics in genetics, again focusing on mtDNA."
}

> Finished chain.


Output for an not event:
> Entering new CrewAgentExecutor chain...
I need to use the tool "Read website content" to gather the event data from the provided event URL.

Action: Read website content
Action Input: {"url": "event URL"} 

Amazon.com. Spend less. Smile more.
Amazon
Your Account
Help
Cart
Previous slide
Next slide
Prime VideoTry 30 days for free
Customers' most-lovedWomen's fashionMen's fashionBeautyHomeDiscover items with 4+ stars
Best Sellers in OutletShop now
Amazon exclusive toysSee more
Small space solutionsShop small space furniture & décor
Save on pre-owned Amazon devicesSee all pre-owned devices
Live plants & plantersShop plants, plant care & pots
Easy, elevated t-shirtsSee the full edit from Shopbop
Conditions of Use
Privacy Notice
Interest-Based Ads
© 1996-2024, Amazon.com, Inc. or its affiliates

Final Answer: Unfortunately, the tool "Read website content" did not provide the event data from the event URL correctly. I was unable to gather the necessary event information in JSON format.

> Finished chain.
