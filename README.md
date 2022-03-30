# Smart Campus Enquiry
## Problem Statement: When a student wants to take admission in a new college he/she faces a lot of issues regarding correct information about the college especially when it comes to government colleges & private colleges in rural areas. During Covid-19 Lockdown students faced many issues; they were unaware & unsure about the information. When students don't get right information by sitting in their homes, they have to travel to college to ask about the information regarding college in college office & senior students who are already studying in college. Students who are already admitted in colleges faces difficulty in getting correct notifications at correct time related to college hostel, holidays, training & placement events, Trainings & internships recommended by college etc. 
## Description: The project is mainly targeted at colleges and the synchronization of all the sparse and diverse information regarding the regular college. In this project we are making a chat bot for students to ask or enquire about college by sitting in their homes. Due to this project students don't have to personally go to college office for the enquiry which will result in minimizing the time required to solve the queries. This project tries to bridge the gap between students, teachers, college administrators and senior students studying in the college. Therefore in the real world scenario, such as college campus, the information in the form of notices, oral communication, can be directly communicated through the android devices and can be made available for the students, teachers directly for their android devices and the maintenance of application will be easier in later future.
## Introduction: Azure Chatbot- Smart Campus is a chatbot which guides students to get information regarding college. For eg. Fee Structure, College essentials, Training etc.
## Technologies Used

- Microsoft Azure

In this project I have taken **Microsoft Azure** as primary technology.
Azure is a cloud computing platform and an online portal that allows you to access and manage cloud services and resources provided by Microsoft. These services and resources include storing your data and transforming it, depending on your requirements. To get access to these resources and services, all you need to have is an active internet connection and the ability to connect to the Azure portal. It was launched on February 1, 2010, significantly later than its main competitor, AWS.
It’s free to start and follows a pay-per-use model, which means you pay only for the services you opt for.
Interestingly, 80 percent of the Fortune 500 companies use Azure services for their cloud computing needs.


In this project, I have used these following **Azure Cognitive Services** into my project:

1. QnA Maker: QnA Maker is a cloud-based Natural Language Processing (NLP) service that allows you to create a natural conversational layer over your data. It is used to find the most appropriate answer for any input from your custom knowledge base (KB) of information. QnA Maker is commonly used to build conversational client applications, which include social media applications, chat bots, and speech-enabled desktop applications. QnA Maker doesn't store customer data. All customer data (question answers and chat logs) is stored in the region the customer deploys the dependent service instances in.

2. Knowledge Base: QnA Maker imports your content into a knowledge base of question and answer pairs. The import process extracts information about the relationship between the parts of your structured and semi-structured content to imply relationships between the question and answer pairs. You can edit these question and answer pairs or add new pairs.

3. App Service Plan: An App Service plan defines a set of compute resources for a web app to run. These compute resources are analogous to the server farm in conventional web hosting. One or more apps can be configured to run on the same computing resources (or in the same App Service plan).

4. App Service: Quickly build web apps and APIs in the cloud. Azure App Service is an HTTP-based service for hosting web applications, REST APIs, and mobile back ends. You can develop in your favorite language, be it . NET, . NET Core, Java, Ruby, Node.

5. Application Insights: Application Insights is a feature of Azure Monitor that provides extensible application performance management (APM) and monitoring for live web apps. Developers and DevOps professionals can use Application Insights to: Automatically detect performance anomalies. Help diagnose issues by using powerful analytics tools.

6. Search Service: Azure has a unique service offering aptly named “Azure Search”. This is a search-as-a-service cloud solution that lets you add a rich search service to your apps. The search service abstracts the complexities of document retrieval through both a REST API and a . NET SDK.

7. Web App Bot: The Azure Bot resource provides the infrastructure that allows a bot to access secured resources. It also allows the user to communicate with the bot via several channels such as Web Chat.

-Developed a Website using Languages such as HTML & CSS. Framework used is- Bootstrap. I have hosted this website on Replit. Replit is a simple yet powerful online IDE, Editor, Compiler, Interpreter, and REPL. Code, compile, run, and host in 50+ programming languages.

## Background working of Azure Cognitive Services:

![Screenshot_20220228-122919 (1)](https://user-images.githubusercontent.com/91502734/155944983-6dc91296-9c99-4a63-92d3-79b7c701a480.jpg)

Here, in the above diagram, explains how cognitive services work in background.  

With the help of Azure QnA maker we have created an knowledge base, then this knowledge base is connected to our azure chatbot and this chat bot is then embedded to our google site DevOps Master --> Client Device sends input to the Bot --> Azure Language understanding understands the client queries and automatically chooses an knowledge base and hence finds the similar answer and sends the output.

