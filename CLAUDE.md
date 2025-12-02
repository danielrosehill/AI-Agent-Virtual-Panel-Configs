I am testing AskRally.com - an extremely intersting AI tool which allows the user to create virtual "focus groups" comprised of different perspectives, which can also be "synced" against real people. 

The platform primarily emphasises use-cases in market research. However, it dovetails significantly with a lot of the tentative and early explorations I've done, albeit in different contexts.

 The purpose of this repository is to gather together planning notes and configurations for some of these panels which I wish to test. Writing each individual persona system prompt would be very time consuming, so your main method of assisting me in this respect will be to generate system prompts after I provide detailed instructions as to the composition of the panels and the type of use cases I'm envisioning. 

 Broad categories will include:

 - Exploring different modes of thinking, such as philosophical views, religious dogma an political movements. 
 - Geopolitical simulations such as simulated multilateral fora involving hypothetical fill in representatives for real Multilateral bodies and Heads of State. In this category, it's important that the panel will be provided with instructions about A simulated forum they are attending to add to the realism of the exericse. 
 - Focus groups which are formulated in an attempt to gather together different perspectives for various socio economic and environmental challenges. I've included one focus group for a particular challenge that I've been involved with lobbying for at a local level. I chose this as it represents, I think, a good example of a stubborn and complicated local issue. 
 - I've also used multi agent configurations of this nature as a means of ranking and stimulating further validation of various business ideas I've come up with over the past year. The VC panel is intended to gather together some of those perspectives. 

The format for the repo can be easily inferred but is:

- Each panel is created as a folder in the panels folder. 
- The panel's MD file is the file I will use to populate descriptive text in the UI. 
- The personas subfolder contains the various personas that will be used. Each persona is a separate file. 
- The Persona file is a system prompt instructing the persona, the AI agent, to adopt this particular trait. Where appropriate, the persona should also be instructed in the overall context within which they are operating. For example, in the UN Agent model a model might be instructured that it is representing the interests and policies of X at a UN forum.

This concept might be extended. In which case, I might ask you to emphasize and some of the prompts that web recall is essential. However, unless I state this, do not assume that to be a requirement as adding this to a system prompt in a model that does not have real time / web retrieval implemeted will only create needless confusion.