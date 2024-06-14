# News Tracker Application IBM-Project-Batch no:B5M1E-05

## Course Content

| Module   | Content                                             | Duration |
|----------|-----------------------------------------------------|----------|
| Module-1 | Introduction to Modern App Development              | 4 Hours  |
|          | -Importance of App Modernization                    |          |
|          | - Platforms Used for Development                    |          |
|          | - Essentials for App Modernization                  |          |
|          | - Important Modernization Technologies              |          |
| Module-2 | Hands-on with Web-app Development                   | 4 Hours  |
|          |   - HTML Basics                                    |           |
|          |   - HTML with CSS                                  |          |
|          |   - JavaScript                                     |          |
| Module-3 |  Flask                                             | 8 Hours  |
|          |   - Introduction to Flask                          |          |
|          |   - Python and Flask Environment Setup             |          |
|          |   - What is web framework                          |          |
|          |   - Flask Basics and Routes, Dynamic Routing, Forms|          |
|          |   - HTTP Methods                                   |          |
|          |   - Templates and Static Files, Redirect and Errors|          |
|          |   - Cookies and Session                            |          |
| Module-4 |  IBM DB2                                          | 3 Hours  |
|          |   - Introduction to IBM DB2 Database               |          |
|          |   - Introducing python SDK for IBM DB2 Database    |          |
|          |   - Connecting Flask app to DB2 Database           |          |
|          |   - Working on Insert, Update, Delete, Retrieve    |          |
|          |   - Learn creating micro-services with CRUD ops    |          |
|          |                                                    |          |
| Module-5 |  Introduction to IBM Object Storage                | 3 Hours  |
|          |   - Introducing python SDK for IBM Object Storage  |          |
|          |   - Creating a new bucket                          |          |
|          |   - Uploading files to the bucket                  |          |
|          |   - Update and delete the files in bucket          |          |
|          |                                                    |          |
| Module-6 |  IBM Watson Assistant                               | 4 Hours  |
|          |   - An Introduction to Watson Assistant            |          |
|          |   - Learning about Intents, Entities, Dialog       |          |
|          | - Buliding a use case with IBM Watson Assistant    | 4 Hours  |
|          | - Learn integrating Bot with Flask Application     |          |
|          |                                                    |          |
|Module-7  | [Intro and Basics of Containerization  ](https://docs.google.com/presentation/d/1cQ2nY2PltUTINkcK8KeQ1VH9b2v-eUbX5rJQK2CWq8s/edit#slide=id.p18)             |          |
|          |   - What is a Container?                           |          |
|          |   - Containerization vs. Virtual Machine           |          |
|          |   - Docker installation                            |          |
|          |   -Main Docker Commands                            |          |
|          |   - Building your own Containerized Image for Flask App |     |



### Miscellaneous Links
#### Getting Started:
- [How to Install Flask](https://flask.palletsprojects.com/en/2.2.x/installation/)
- [How to Install Pip on Windows](https://www.geeksforgeeks.org/how-to-install-pip-on-windows/)
- [Installing Pip](https://bootstrap.pypa.io/get-pip.py)
- [SQLAlchemy Documentation](https://www.sqlalchemy.org/)
- [Installing SQLAlchemy](https://www.sqlalchemy.org/)
- [Setting up Flask Blog with DB](https://github.com/kshyam/flask-blog-with-db)

#### HTTP Basics:
- [HTTP Status Codes](https://restfulapi.net/http-status-codes/)

#### Database Integration:
- [Flask with IBM DB2](https://github.com/kshyam/flask-with-ibm-db2)
- [Microservice with IBM DB2](https://github.com/kshyam/micro-service-with-ibm-db2)

#### Chatbot Integration:
- [Watson Assistant](https://cloud.ibm.com/catalog/services/watson-assistant)
- [Watson Assistant Web Chat](https://web-chat.global.assistant.watson.appdomain.cloud/preview.html?backgroundImageURL=https%3A%2F%2Fjp-tok.assistant.watson.cloud.ibm.com%2Fpublic%2Fimages%2Fupx-855958b6-f1ca-490c-9178-349a7f319979%3A%3A141c6279-92ff-4e93-9d9b-be164ab337b5&integrationID=17a66346-6210-477f-aa46-96d7da7a20cb&region=jp-tok&serviceInstanceID=855958b6-f1ca-490c-9178-349a7f319979)
- [Watson Assistant Web Chat](https://web-chat.global.assistant.watson.appdomain.cloud/preview.html?backgroundImageURL=https%3A%2F%2Fjp-tok.assistant.watson.cloud.ibm.com%2Fpublic%2Fimages%2Fupx-855958b6-f1ca-490c-9178-349a7f319979%3A%3A8f9e8cbb-a8a6-49f4-85ac-37fffdbae1c7&integrationID=fca0ee27-ced6-43aa-84a4-7d619001a75a&region=jp-tok&serviceInstanceID=855958b6-f1ca-490c-9178-349a7f319979)

#### Additional Resources:
- [Presentation 1](https://docs.google.com/presentation/d/14gU82U3nIBtAxW9LHjimZU2PqEOSVhF6ZADpUa2zuVg/edit#slide=id.g1568bcaaf87_0_68)
- [Presentation 2](https://docs.google.com/presentation/d/1E8SfSJFLogn9NN8PDexeyTeFPvCforKcrWsIV5d007w/edit#slide=id.g1d9c67055b_0_154)
- [Presentation 3](https://docs.google.com/presentation/d/1ozhQtOSZQ9mSiSkFGfdxkwMnCTezj8VRKkAxfJURR0A/edit#slide=id.g15f7a6adf1b_3_0)
- [Presentation 4](https://docs.google.com/presentation/d/1cQ2nY2PltUTINkcK8KeQ1VH9b2v-eUbX5rJQK2CWq8s/edit#slide=id.p18)
- [Best Docker Image Hosting Platforms](https://razorops.com/blog/best-docker-image-hosting-platforms/)

#### Trainer's Resources:
- [Trainer's GitHub Profile](https://github.com/kshyam)
- [Flask with IBM DB2 (Trainer's Repository)](https://github.com/kshyam/flask-with-ibm-db2)


## Overview

News tracking often never comes in handy as we have to access Google, and search for the relevant topics. Eventually, some of them are fake and not the exact kind of news we look for. Tracking the news hence will help people to avoid boring, fake and helps in finding the desired news.

The amount of data has grown exponentially with the increasing networks and information passing around through the internet. The concern ultimately is the selection and identification of extracting the knowledge of interest for different kinds of people. In the current models, the LDA (latent Dirichlet allocation) technique is used to extract topics from news texts. It is supported with various other processes like Gibbs Sampling method to speculate parameters. The topic mining using the K-means method is compared to highlight the advantages of using LDA for topic discovery. Second, the improved single-pass algorithm is used to track news topics.

One kind of a large network of online resources and interconnected people sharing their opinions and news circulating around is Twitter. Breaking news that are posted, are categorized as groups, ranks and tracks. Instead of using a supervised ML model, the twitter messages are made into an intermediate value called as timeline to be tracked.

Clustering of the various messages, probable news with the format or structure, can be used to find the topic of relevance or interest by the people who need to view the news based on it. The improvement of the common agglomerative hierarchical clustering algorithm based on average-link method, which is used to implement the retrospective topic detection and the online topic detection of news stories of the stocks is implemented already as per the submitted paper.

Ultimately tracking of news by using stochastic models are also in use due to information occurring in fragments. These are formed by the storylines tracking in news channels and in documents. Using the Kullback–Leibler divergence, we can:
1) Identifying the same topics
2) Clustering the similar nodes
3) Topic selection
4) Topic Detection

<!-- ![News Tracker Application](https://github.com/Pushpakumar02/pushpakumar02.github.io/blob/main/images/newstracker_app.png) -->
<img src="https://raw.githubusercontent.com/Pushpakumar02/pushpakumar02.github.io/main/images/newstracker_app.png" alt="News Tracker Application" style="width:100%; max-width:594px; height:auto;">

Real-time updates can be obtained by everyone at any time and anywhere in the area of interest without any hassle.

## Technology Architecture
![Technology Architecture](https://user-images.githubusercontent.com/66555276/196895753-90542501-710f-4e94-8bdb-08aa2e780817.jpg)

## Hardware Requirements
- Laptop or PC
- I3 processor system or higher
- 8 GB RAM or higher
- 100 GB ROM or higher
- Processor: Intel i5 9th Gen

## Software Requirements
- Anaconda Prompt
- Visual Studio Code
- Flask
- Operating System (Windows 7+/Linux/MaxOs)

## IDE’s, Tools and Techniques Used
- Python
- Flask
- LDA (latent Dirichlet allocation)
- K-Means Clustering
- Gibbs Sampling

## Solution Architecture
![Solution Architecture](https://user-images.githubusercontent.com/66555276/196893314-5cf3fcf2-4e17-497f-85eb-81cd0b2d01db.jpg)

## Conclusion

One of the factors in successful news app development is the visualization of news and its features with users. For the development of an Android app, material design is very useful and provides a smooth experience with custom layout, views, and animations. Hence, the application of the news tracker is a very essential use of news access from anywhere anytime.

Also inspired by the original repository: [samuelhatcliff/newstracker](https://github.com/samuelhatcliff/newstracker).
