
RADIOVERSE
==========

**RADIOVERSE** targets amateur radio enthusiasts, scientists, and newbies fascinated by the subject matter.

Amateur radio data is fundamental for reconstructing Earth's ionosphere, an atmospheric layer whose reflection is key to long-range radio communications.
Early detection or even prevention of disturbances in its density can help maintain services such as telecommunications and GPS up and running.

However, data from ham-radio stations on Earth is nearly impossible to find, access, or use for free. When it can be find, it is hard to process because of messy formats and incomplete and obscure software. At the same time, the ham-radio on board the ISS does not provide enough data to this end.

RADIOVERSE aims at gathering a community for
* hosting data collected by radio enthusiasts in an open standard format
* providing it for free, together with a FLOSS suite of algorithms
* engaging new and old ham-radio users with a fun gamification app

During the hackathon, we were able to design a preliminary version of the RADIOVERSE ecosystem, and to develop a small part of it:
1. A **python notebook** for reconstructing and showing the ionosphere starting from ISS ham-radio data. The notebook has the double purpose of
    * Giving a glimpse of the relevance of ham-radio data
    * Offering an interactive primer for targeted libraries (spacepy, cartopy, cdflib) and tools for data handling and visualization (pandas, numpy, matplotlib).
2. A **mock-up for the gamification app** with three sample activities
    * Using your radio apparatus, **contact one of the available ham-radio stations** on the map to unlock new stations and collect *R* coins. The message content (to be better defined) would include the ham-radio ID and a timestamp. The receiving station enriches the message with the timestamp at receival, and sends it to our server. This, in turn, notifies your app and awards you *R* coins. 
    * **Participate in quests** -- e.g. 7-days streak in contacting ham-radio stations -- to earn additional *R* coins and special badges to show off!
    * Use your *R* coins to **customize your avatar** and equip them with your preferred clothing and the latest tech!
* A **website** -- indeed, the ppt presentation itself! -- to show how we would integrate open data, open software, and open knowledge. 
