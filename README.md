# Effortless Communication using Artificial Intelligence for improved lifestyle

In this project I’m implementing chatbot for a book store so that customers who come to buy books can get a better suggestion of the books.

For this first I have to create database of question and answers which bot should know. And this was made easy by creating a database of questions in QnA Maker Service. The QnA Maker Service enables you to build, train and publish a simple question and answer bot based on FAQ URLs, structured documents or editorial content in minutes.

Now this QnA has to be fed to chatbot which was done using Azure Bot service. Azure Bot Service is a managed bot development service that helps you seamlessly connect to your users via popular channels. So, first resource group was made and relevant details were selected. Once this bot is made it needs to answer some questions. 

Once this is done it has to be deployed on any website so using Azure Blob storage, I had uploaded HTML file in which complete design of the webpage was done. Azure Blob storage is Microsoft's object storage solution for the cloud. Blob storage is optimized for storing massive amounts of unstructured data. Unstructured data is data that doesn't adhere to a particular data model or definition, such as text or binary data.

Now we are ready to use for bot without any challenges. I hope this bot can be helpful for most of the customers to buy books.

## Features
* User interaction with chatbot
* Auto – prompt questions
* Suggests best books from its available books
* Answers all FAQs with better understanding
* Gives all information about delivery, payment, etc
* Explains return and replacement policy
* Takes feedback from the users

## Implementation and Screenshots

* Project URL: https://qnabotbooks.z29.web.core.windows.net/
* Project Video: https://youtu.be/Aa5UX0NtNiU


![homepage](https://user-images.githubusercontent.com/92013638/156881484-88c739b0-fed2-466f-9338-6d13d0ee5a82.png)

![hello](https://user-images.githubusercontent.com/92013638/156881514-b604a90a-be8f-427c-b3c0-3c575ccd8e54.png)

![book](https://user-images.githubusercontent.com/92013638/156881498-01767744-68db-4066-8b69-f72b8632362e.png)

![delivery](https://user-images.githubusercontent.com/92013638/156881527-a8f7f921-260d-4266-8fa5-cef6ec743d5e.png)

![payment](https://user-images.githubusercontent.com/92013638/156881535-b85d61f3-53df-40f0-b198-4a989825a29b.png)

![feedback](https://user-images.githubusercontent.com/92013638/156881540-62b859a6-7221-404b-85f1-e236ff28c03e.png)
