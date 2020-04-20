# Amazon Alexa Skill Building

In this lab session, we will be building a Alexa Skill that will do the following:

* Greet the user with a welcome message when they open the Alexa Skill

We will do this using a Alexa Skill interaction model and a AWS Lambda function (using Python)

* Conversation dialog experience and fetching data from a database

We will do this using Intents and Slots (to fulfill user input) and a DynamoDB database table, which will house the various questions and responses that Alexa will use to relay to the user via Speech prompts

* Build and Test the Skill

We will do this using the Alexa Simulator and also using a Alexa Echo Dot device
* Publishing and Certification

Discuss the process and options available

*  Public Skill vs. Private Skill
* Beta Testing

When starting to build for voice, it is a good practice to design the conversation experience. Two main artifacts that help with voice design are:

* Conversation Script
* Conversation Flow

Let's take a closer look at the design artifacts and what we will be building in this lab session. Click the below link to learn more about these design artifacts.
* Design artifacts

Now that we have reviewed the voice design artifacts, we will now start to build the Alexa skill. You will need two different Account setups:

* Amazon Developer account – this will house the Alexa Skill

* AWS account – this will house the Lambda function and DynamoDB database table

