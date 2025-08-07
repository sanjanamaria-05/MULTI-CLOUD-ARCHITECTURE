# MULTI-CLOUD-ARCHITECTURE
COMPANY : CODTECH IT SOLUTIONS

NAME : SANJANA MARIA P.S

INTERN ID : CT04DH2447

DOMAIN : CLOUD COMPUTING

DURATION : 4 WEEKS

MENTOR : NEELA SANTOSH

# DESCRIPTION :

For this internship task, I was asked to create a basic multi-cloud architecture, which means using more than one cloud platform (in this case, Google Cloud and AWS) to build a small working project. The main goal was to split the project between two cloud providers and show that they can work together — this is called interoperability.

I realized it could be done using free tools provided by both platforms.

What I Built
I created a simple two-part application:

Frontend (Google Cloud): A basic webpage (HTML file) that is hosted using Google Cloud Storage. This acts like the “face” of the application that users see when they visit the link. It includes a button that, when clicked, sends a request to the backend.

Backend (AWS): A small piece of code (called a function) hosted on AWS Lambda. This function is connected to the internet using API Gateway, which provides a public URL. When the Google Cloud frontend makes a request to this URL, the AWS backend sends a response like: { "message": "Hello from AWS Lambda!" }

This setup shows how two cloud platforms can work together — the frontend on Google Cloud and the backend on AWS. The communication between them is what demonstrates multi-cloud interoperability.

Why This Matters
In the real world, companies don’t always rely on a single cloud provider. Using multiple cloud services has several advantages, like avoiding vendor lock-in, improving reliability, and choosing the best tools from different platforms. Even though my project is very basic, it reflects a real-world concept.

My Learning Experience
I learned how to:

Create and configure a Google Cloud Storage bucket
Upload and host a static website
Write a simple HTML page with JavaScript
Create a Lambda function in Python
Use API Gateway to make the function accessible online
Connect the two using a fetch request from the frontend to the backend
Conclusion
By the end of this task, I was able to create a simple multi-cloud project that worked as expected. When I clicked the button on the Google Cloud-hosted webpage, it successfully fetched and displayed a message from an AWS Lambda function. This project helped me understand cloud basics, how APIs work, and how different cloud services can communicate with each other. It was a valuable learning experience and has given me the confidence to explore more cloud-based technologies in the future.

# OUTPUT 
<img width="925" height="485" alt="Image" src="https://github.com/user-attachments/assets/9671f410-9b58-4a61-ad1e-743aa1f02ce8" />

<img width="666" height="196" alt="Image" src="https://github.com/user-attachments/assets/025de277-4de0-4c96-ab39-305828b8feaa" />


