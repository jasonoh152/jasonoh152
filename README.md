# Hello, I'm Jason Oh 👋

#### I'm a passionate Full-Stack Developer and Data Engineer, dedicated to building resilient and scalable web applications, optimizing backend systems, and designing efficient cloud-based data pipelines.

💼 Worked at:
- [**Spare-it**](https://www.linkedin.com/company/spareit/) as a Data Engineer, where I built a data pipeline from S3 buckets to SageMaker and EC2 instances, carefully selecting the most efficient EBS and EFS sizes. I automated the entire process using Boto3 and leveraged multiple open-source tools like Ultralytics, Albumentations, and Sahi to train segmentation models. Additionally, I worked extensively with Lambda, DynamoDB, and data lakes to extract insightful data and display it in our admin dashboard product.
- [**BU Spark!**](https://www.bu.edu/spark/) as a Software Engineer Intern. I led the development of three full-stack applications, managing project requirements and timelines to align with stakeholder expectations.

  1. **Boston Scofflaw Landlords Tracker – Bad Landlords:**  
     Crafted a dynamic website for the Boston City Council to list properties owned by scofflaw landlords, helping to reduce housing fraud. I reengineered the codebase using Next.js, integrated Mapbox.js and ArcGIS for geospatial visualization, and modernized the UI with Tailwind CSS. I also performed exploratory data analysis (EDA) and set up a PostgreSQL database on Railway Cloud, overseeing schema migrations with Prisma ORM.

  2. **District 7 Community Resources App - D7:**  
     Built a mobile web application for District 7 residents to access resources and event information. I resolved API issues, revamped the frontend following Figma design specifications, and developed backend features with Strapi Headless CMS, streamlining the frontend using Vite.js for better performance.

  3. **University Catering Leftovers Sharing App – Spark Bites:**  
     Created a web application for students to share leftover catering food, contributing to reduced waste on campus. I implemented OAuth for secure authentication, designed intuitive UI/UX interfaces, and developed middleware using TypeScript and Zod for type-safe API calls. I also configured Firebase and PostgreSQL databases, set up a CI/CD pipeline with GitHub Actions and Jest, and containerized the application with Docker.
- **South Korean Air Force Information Systems Management Group** where I managed a database system overseeing millions of inventory records, ensuring 99.9% uptime for critical operations. I led a 14-member team for one year, modernizing legacy code with five team members by allocating tasks and strategizing product delivery. Additionally, I created Python scripts and Excel macros to reduce manual work and increase data accuracy.

🎓 **Computer Scinece Major** at **Boston University**, graduated in May 2024.

## 🚀 Personal and Group Projects

- **Waste Detection and Contamination Identifier**: In this project, I developed an image detection model utilizing bounding boxes from COCO JSON labels. Early data analysis was conducted to identify key challenges, particularly a significant class imbalance in the dataset. Leveraging the power of the YOLOv8 model from Ultralytics, we tackled pressing challenges in waste classification, including skewed model performance due to overrepresentation of common items like paper towels. To address this, I implemented sophisticated solutions such as oversampling, undersampling, and extensive data augmentation using the Albumentations library. Additionally, I balanced batch distributions to prevent overfitting and improve model generalization across diverse waste types. Custom loss functions were created to enhance detection accuracy, particularly in separating and identifying individual waste items within clusters. This allowed the model to better distinguish closely packed items, significantly improving its practical utility.  
  | [Repository](https://github.com/BU-Spark/ml-spare-it-contamination/tree/dev) | [Demo](https://huggingface.co/spaces/jasonoh/spare-it) |
  
  ![slide1](https://github.com/jasonoh1998/jasonoh1998/assets/92873161/758c9e1d-3055-4132-95ec-42eb545fd19e) ![slide2](https://github.com/jasonoh1998/jasonoh1998/assets/92873161/e3794708-6f46-4a83-85ad-d14ec330fc9a)

- **Generative AI Applications:**  
  Investigated the capabilities of OpenAI's GPT language model, developing three key features: Document Interaction Chatbot, Stock Analysis Chatbot, and Automatic Quiz Generator. I utilized Azure Web App, Azure Blob Storage, Azure Key Vault, and GitHub Actions to deploy and host Streamlit applications. The project also leveraged LangChain libraries for dynamic model switching between GPT models and Llama2.  
  | [Demo](https://jasonoh-genai.azurewebsites.net/) |

  1. **Document Interaction Chatbot – DocTalk:**  
     Processed document inputs, conducted OpenAI embeddings, and applied FAISS for efficient content retrieval. Tokenized the input and employed various distance strategies to enhance document retrieval accuracy.

  2. **Stock Analysis Chatbot – StockGlimps:**  
     Engineered a chatbot that delivers detailed reasoning using the Reasoning+Acting prompting technique, deploying Agents to split questions midway. Incorporated external APIs like DuckDuckGo to refine and enhance AI decision-making.

  3. **Automatic Quiz Generator – QuizGen:**  
     Programmed the automatic generation of quizzes and answer keys in JSON format from Wikipedia or inputted documents.
     
  ![image](https://github.com/user-attachments/assets/0da1f872-ce8e-4423-b98f-ace3f6a0aad5)![image](https://github.com/user-attachments/assets/4a8eaf23-c02c-4607-bd85-6b8b6a9eff41)![image](https://github.com/user-attachments/assets/a7eea3e3-f912-4555-bde0-009b5db87820)

- **Voice Gender Prediction using Neural Network:**  
  Specializing in audio data analysis, I focused on applying spectrograms, mel-spectrograms, and MFCCs for gender and age detection. This initiative involved training a convolutional neural network (CNN) to achieve high accuracy in gender identification, with ongoing improvements aimed at refining age estimation capabilities.  
  | [Repository](https://github.com/jasonoh1998/audio-cnn-project) |

- **Boston Scofflaw Landlords Tracker – Bad Landlords:**  
  As the full-stack developer, I was responsible for designing and implementing a dynamic website for the Boston City Council to list properties owned by scofflaw landlords. I drew out entity table diagrams to analyze census data and identify precise geolocational data for display using Mapbox.js. I led the overall framework revamp from Vite.js with Express.js and a local JSON dataset to Next.js with Railway Cloud data migration. Additionally, I utilized Tailwind CSS to style the website and employed TypeScript, Prisma ORM, and Zod to ensure API endpoints were type-safe.  
  | [Repository](https://github.com/BU-Spark/se-bad-landlords/tree/dev) | [Demo](https://deploy-preview-20--bad-landlords-qa.netlify.app/map) |
  
  ![image](https://github.com/jasonoh1998/jasonoh1998/assets/92873161/e1030195-894e-4e7b-b1a3-995bc2331d20) ![image](https://github.com/jasonoh1998/jasonoh1998/assets/92873161/53cd8ec6-bfac-4077-a172-102e4cccf80d)

- **Shine-AI:**  
  This project focused on mental health support, where I led the development of an application using Next.js, Prisma, Firebase, Vercel, and Jest. I was responsible for designing backend services and integrating external support mechanisms to provide users with direct access to professional help. The application aimed to create a seamless connection between users and mental health resources.  
  | [Repository](https://github.com/BU-Spark/se-shine-ai) |
  
  ![image](https://github.com/jasonoh1998/jasonoh1998/assets/92873161/b70137f8-baf2-4c0a-9ed0-486a44dc609a)

- **District 7 Community Resources App - D7:**  
  This project aimed to enhance community services in Boston's District 7. I built a mobile web application for residents to access resources and event information, facilitating financial assistance for Boston residents. I troubleshot and resolved API issues to ensure seamless data retrieval while revamping the frontend in line with Figma design specifications to enhance the user experience. The backend was developed using Strapi Headless CMS, and I streamlined the frontend with Vite.js to boost performance and maintainability. I also contributed to code refactoring and feature integration to meet the project’s requirements. Collaborating with Boston City Councilor Tania Fernandes Anderson, I ensured the project’s alignment with community needs.  
  | [Repository](https://github.com/BU-Spark/se-d7-dashboard) |

- **OTT Streaming Service Project - SwanStream:**  
  In this project, I built a full-stack streaming service platform for drama and comics using JSP, Bootstrap, jQuery, Java, Spring, MyBatis, JSTL, and OracleDB. Deployed on AWS, the platform was designed for robust performance and scalability, enabling a seamless user experience.  
  | [Repository](https://github.com/jasonoh1998/swan_stream) |

  ![image](https://github.com/user-attachments/assets/31529598-a206-41d1-88f4-bdea64f945b4)![image](https://github.com/user-attachments/assets/d108642b-b2e7-4b49-bf5a-ae6d3a6e2605)![image](https://github.com/user-attachments/assets/045605d3-8c64-4a26-81d5-8b3f0b719307)![image](https://github.com/user-attachments/assets/07be2f69-293f-40b0-a91e-475f38194bdd)
  ![image](https://github.com/user-attachments/assets/9f987e60-9836-4dab-b574-5a9ee04b01a9)![image](https://github.com/user-attachments/assets/bc62b024-4e7d-458f-a14b-60d025a88719)![image](https://github.com/user-attachments/assets/ae0a6fe3-8342-4223-adbb-c4043067cd21)

## 🛠 Full-stack & Data Engineering Technologies

**💡 Proficient In (Everyday Use):**

- **Languages:** Python, TypeScript, JavaScript
- **Web:** React.js, Next.js, Vite.js, Node.js, Express.js, Flask, Tailwind CSS, Material UI
- **Databases & Cloud:** PostgreSQL, MySQL, Firebase, AWS, Railway
- **DevOps:** Docker, Git, GitHub Actions
- **Machine Learning & AI:** PyTorch, Keras, OpenAI, Llama, LangChain, FAISS

**🏗 Intermediate (Know How to Use):**

- **Languages:** Java, SQL
- **Web:** JSP, Spring, MyBatis, JSTL, Headless CMS (Strapi)
- **Mobile:** Expo, ReactNative
- **Databases & Cloud:** OracleDB, MongoDB, Azure

**🌱 Basic Knowledge (Learning & Exploring):**
- **Languages:** Rust, C++
- **Web:** Svelte
- **Mobile:** Flutter

## 🌐 Connect with me
- **LinkedIn:** [Jason Oh](https://www.linkedin.com/in/cheolminoh/)
- **Email:** jasonoh1998@gmail.com
