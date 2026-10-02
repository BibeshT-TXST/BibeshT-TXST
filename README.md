<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=520&lines=Hi%2C+I'm+Bibesh+%F0%9F%91%8B;CS+%40+Texas+State+University;Full-Stack+%2B+Applied+ML;Atomic+Commits+%3E+Atomic+Habits+%3AP)](https://git.io/typing-svg)

<br/>

**Computer Science Junior at Texas State University · Student Worker @ UL Systems**  
I build systems at work and train models at home. Currently deep in Backend Architectures, Cloud Systems Design(AWS) and Secure Large Language Model(LLM) and Convolution Neural Network(CVN) serving.

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Bibesh_Timalsina-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bibesh-timalsina-a7a9482b9/)
[![Blog](https://img.shields.io/badge/Blog-Dark_Matters_Tech-FF6C37?style=flat-square&logo=blogger&logoColor=white)](https://darkmatterstech.blogspot.com/)
[![Email](https://img.shields.io/badge/Email-timalsinabibesh747@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:timalsinabibesh747@gmail.com)

</div>

## What I do

Hi, I'm Bibesh, a Computer Science junior who is aspiring to be a Software Engineer. I love solving problems, optimizing existing solutions, improving throughput and eliminating backdoor variabilities. At TXST library I build and manage software used by the library employees. 

I am focusing on AI integration, Cloud services(AWS personally, Azure at Work), Backend, Data Modeling, Data Security and  Deployment but I also love to build frontend components, sandbox  environments and unit tests. I use claude code for researching and prototyping solutions only as I strive to maintain a clean codebase, good version control practices and ship maintainable code.
## Personal Projects

### 🔬 SightX &nbsp;·&nbsp; `Feb 2026 – Present` &nbsp;·&nbsp; [Repo](https://github.com/BibeshT-TXST/SightX) &nbsp;·&nbsp; [Blog](https://darkmatterstech.blogspot.com/) (V2: AWS Migration Ongoing)

A clinical AI screening tool for **diabetic retinopathy**: A leading cause of preventable blindness that often shows no symptoms until too late.


- Trained a **ResNet-50** V2 diabetic retinopathy classifier on 35K retinal images and achieved kappa **κ = 0.8454** on a personal MacBook (Apple M4, no cloud compute) using CLAHE preprocessing, cosine annealing with warmup, and gradual unfreezing.
- Built a post-processing safety pipeline using **temperature scaling**, **Bayesian prior correction**, and an asymmetric cost matrix that converts raw model logits into 3 actionable triage tiers.
- Built a **108-iteration test-time augmentation ensemble** that runs stochastic transforms per inference pass and returns the modal prediction with averaged confidence, making the system robust to camera artifacts.
- Built and shipped a 3-container Docker microservices stack (React, Node.js, FastAPI) with ephemeral in-memory image handling (no patient data written to disk), JWT + row-level security via Supabase, and a single-command deploy targeting Private Red Hat Enterprise Linux servers.
- Currently deploying in AWS using **AWS CloudFront, Lambda, SQS, RDS, S3, IAM** and **VPC** and testing builds using **Local Stack**.

`PyTorch` `ResNet-50` `FastAPI` `React` `Node.js` `PostgreSQL` `Docker` `Supabase` `AWS` `Microservices`

### Texas State University Libraries Systems Team &nbsp;·&nbsp; `Dec 2025 – Present` &nbsp;*(Internal)*
#### Travel App Project `May 2026 - Present`(V1 in active Development) 
- Collaborate with 2 senior software engineers to build and maintain Open API specs, controllers and services in a MVC backend for the UL Travel App project used by 100+ library employees. 
- Built frontend components using shadcn, typescript & next.js and and wiring them to the backend services.
- Built a Sandbox Backend & Database network using Api docs, MongoDB, Typescript, Docker and Postman to test endpoints.

#### TOPS Asset Management Web App `Feb 2026 - Present`(V1 Live)(V2 In active Development)
- Rebuilt an Inventory Management application to a TOPS Asset Management Web Application Secured behind TXST’s SSO. The application is built as 4 Docker container services: Nginx Load Balancer, Next.js Frontend, Flask Backend and PostgreSQL database
- Built a JWT cookie header based auth system with Next.js proxy + Argon2 client side hashing and session guards across all route groups.
- Traced a data duplication error in a live Flask backend server and fixed it using WHERE NOT EXISTS subqueries
- Co-deployed TOPS Asset Management Web App to a TXST Red Hat Enterprise Linux test server via a custom Github Actions CI/CD pipeline with Linters, Dependency Tests, Unit Tests and Integration Tests.

#### Project GitGud(OnBording Project #2) `Dec 2025 - May 2026` &nbsp;·&nbsp; [Repo](https://github.com/BibeshT-TXST/SightX) (Completed)
- Built a Book Inventory management web app using JavaScript, React, REST APIs, PostgreSQL, Docker and Git.
- Built a JWT session storage based auth system with Argon2 client side hashing and session guards across all route groups.
- Built a custom 5-column MUI-DataGrid component with inline row editing, debounced search, and batch edit/cancel and its CRUD routes in the backend.
- Co-deployed the app to a TXST Red Hat Enterprise Linux test server via a custom Github Actions CI/CD pipeline with Dependency Tests and Unit Tests, under guidance of senior developer.

#### Project Error Pages(OnBording Project #1) `Dec 2025 - Jan 2026`(Completed)
- Build 4 resuable error pages from scratch using HTML and CSS(Tailwind & BootStrap)
- Customized CSS for each screen type mobile, tablet & Laptop so the pages are responsive.
- Pages deployed to be used by any application under TXST network to replace generic error messages/pages.

`TypeScript` `Next.js` `Node.js` `PostgreSQL` `MongoDB` `Azure Blob` `python` `flask` `Docker` `Docker Compose` `REST API` `MVC` `NGINX` `GitHub Actions` `Storybook` `Vitest` `Tailwind CSS` `Radix UI` `MUI` `Shad-cn` `Figma`

## Stack

**Programming Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**Frameworks, Libraries & APIs**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-4B5563?style=flat-square)
![WebSockets](https://img.shields.io/badge/WebSockets-4B5563?style=flat-square)
![OpenAPI](https://img.shields.io/badge/OpenAPI-6BA539?style=flat-square&logo=openapiinitiative&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Vector DBs](https://img.shields.io/badge/Vector_DBs-4B5563?style=flat-square)

**Cloud**

![AWS CloudFront](https://img.shields.io/badge/AWS_CloudFront-232F3E?style=flat-square)
![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-232F3E?style=flat-square)
![AWS SQS](https://img.shields.io/badge/AWS_SQS-232F3E?style=flat-square)
![AWS RDS](https://img.shields.io/badge/AWS_RDS-232F3E?style=flat-square)
![AWS S3](https://img.shields.io/badge/AWS_S3-232F3E?style=flat-square)
![AWS IAM](https://img.shields.io/badge/AWS_IAM-232F3E?style=flat-square)
![AWS VPC](https://img.shields.io/badge/AWS_VPC-232F3E?style=flat-square)
![AWS Bedrock](https://img.shields.io/badge/AWS_Bedrock-232F3E?style=flat-square)
![Red Hat Enterprise Linux](https://img.shields.io/badge/Red_Hat_Enterprise_Linux-EE0000?style=flat-square&logo=redhat&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)

**Infrastructure & DevOps**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![NGINX](https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Deployment](https://img.shields.io/badge/Deployment-4B5563?style=flat-square)
![Observability](https://img.shields.io/badge/Observability-425CC7?style=flat-square&logo=opentelemetry&logoColor=white)

**AI/ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Model Training and Serving](https://img.shields.io/badge/Model_Training_and_Serving-4B5563?style=flat-square)
![Transfer Learning](https://img.shields.io/badge/Transfer_Learning-4B5563?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-4B5563?style=flat-square)
![Vector Search](https://img.shields.io/badge/Vector_Search-4B5563?style=flat-square)
![Evaluations](https://img.shields.io/badge/Evaluations-4B5563?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)

**Tools and Practices**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Bitbucket](https://img.shields.io/badge/Bitbucket-0052CC?style=flat-square&logo=bitbucket&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Swagger UI](https://img.shields.io/badge/Swagger_UI-85EA2D?style=flat-square&logo=swagger&logoColor=black)
![Agile Development](https://img.shields.io/badge/Agile_Development-4B5563?style=flat-square)
 
## A bit more about me

- Spent ~2 years as a research coach at the university. Helping students find what they need taught me that clear communication is its own kind of skill.
- Former middle school math tutor. Engineering problems are usually easier (usually).
- If I was born in the middle ages I'd be a Knight

<div align="center">
<sub><i>Atomic Commits > Atomic Habits :P</i></sub>
</div>
