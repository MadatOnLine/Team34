# CalSAAS
=========

A platform for connecting requesters and volunteers with a workflow pipeline and NLP integration. CalSAAS is built for scale right from the get-go!


## Motivation
Sewa US and many other NGO's find it challening to deploy large scale solutions. The communication between Organizations and volunteers has historically been manual, and broadcast based. Further, there is no standard way of registering a volunteer or requester. We present CalSAAS - a one-click deploy platform for a) new-user onboarding, b) requests handling, and c) volunteer assignments.


## What it does
[]Users interact with our system through the Telegram chatbot. This includes users onboarding, and ingestion of user requests. 
[]An AI engine that ingests all the responces, and assigns a "criticalty/urgency score" using Sentiment Analysis
[]Each request is handled as a unique ticket on Trello. Each ticket flows through 4 stages: Backlog, Awaiting Approval, In Progress, Completed. 
[]Sensitive data such as 'Family Services' go through an additional 'Awaiting Approval' stage. 
[]Every ticket is broadcast to an increasing number of prospective volunteers based on their location and the requester's location (using hilbert curves). Customized buttons to capture responses from the volunteers to avoid the bystander effect.  
[]A Trellis dashboard allows for fine-grained monitoring of each request. 

## Deploying CalSAAS 

'''
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)
'''

## Using  

[] Subscribe to the bot at  http://t.me/calsaas_bot
[] `/new` Add a new user
[] `/help` Request for a volunteer
[] `/done` User task completion 
[] `/cancel` Reset state




## Trello APIs