# dawn-avery-alexa-skill-20180823

I strongly believe this Alexa Skill will be a giant leap towards setting your business ahead of your competition.

<img src="https://cdn-images-1.medium.com/max/1600/1*XlHvsU3ejM4PF6YDjFGgig.png" width="70%">

Planning and developing an Alexa Skill is composed of multiple tasks:

- Pick your skill _invocation name_, this is how Alexa knows users are initiating a conversation with your skill - e.g. Alexa, ask **dry cleanners** to...
- Define the _intents_ your skill is able to serve. These were the intents we mapped during our call:
  - Phase (1): laundry pickup, laundry return
  - Phase (2): cleaning tips, schedule recurring service
  - Phase (3): (suggested) payment integration: one-time payments and manage default form of payment
- Define _slots_, mandatory information for sucessful fulfillment of your intents - e.g. When or Where
- List _uterances_, phrases that users would say to invoke your intent
- Create a _dialog model_, it identifies required slots and the prompts Alexa to collect and confirm the slot values
- Create a cloud-based service that accepts these intents as structured requests and then acts upon them - AWS Lambda and MongoDB - Phase (1):
  - Store converstion data;
  - Forward customers' requests to you (and/or business manager) via SMS (requires an account with Twilio or similar) or email;
  - Store customers' requests data in a Google Sheet
- Skill configuration that brings all of the above together so that Alexa can route requests to the service for your skill
- Post development: Testing, Certification and Publishing

**_This scope of this proposal covers the intents listed on Phase (1) only, and all tasks required for developing, testing, certifying and publishing your Alexa Skill._**

Estimated workload: 40 hours
Rate per hour: $60
Total cost (on fixed price contract): $2,400
- Milestone (1): $1,400 Defining intents and slots, listing uterances, creating the dialog model
- Milestone (2): $400 Development of cloud functions (back-end that will fulfill your skill's intents)
- Milestone (3): $250 Skill configuration
- Milestone (4): $350 Testing, Certification and Publishing

Looking forward to your comments.

Sincerely,
-Bruno Soares
