# Hey there! 👋 I'm Jean Lynberg

Welcome to my GitHub! 🎉 I’m a **C++** enthusiast, aspiring **Software Engineer**, and someone who loves creating innovative solutions. Below are some of the projects I’m working on.

--------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🚀 About Me

- 💼 **Current Role:** Aspiring Software Engineer
- 🎓 **Learning:** C++ Development, Algorithms, Web Development
- 🌱 **Interests:** Building scalable systems, problem-solving, and exploring the cloud
- 💬 **Fun Fact:** Fitness and coding are my passions 🏋️‍♂️ ⚽

---------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🌟 **AWS Cloud Practitioner Certification**

As an **AWS Cloud Practitioner**, I designed an AWS-hosted application architecture focused on high availability, scalability, and fault tolerance. Here’s how I structured the infrastructure:

### **Project: Hosting an Application on AWS Cloud**

- **Static Content**: 
  - Used **Amazon S3** for hosting static assets (HTML, CSS, JS).
  - Linked **S3** to **S3 Glacier** for backup in another Availability Zone (AZ) for reliability.
  - **Amazon CloudFront** for low-latency content delivery globally.

- **Virtual Private Cloud (VPC)**: 
  - Created a **VPC** to isolate the infrastructure.
  - Configured **Private Subnets** for databases and backend services.
  - Created **Public Subnets** for EC2 instances and used **Internet Gateway** for internet access.
  - Split infrastructure across 2 Availability Zones for redundancy.

- **Security Groups**: 
  - Added **Security Groups** for each subnet to control access and enhance security.

- **High Availability & Scalability**: 
  - Enabled **Auto Scaling** for EC2 instances.
  - Ensured every service has a backup in another AZ for fault tolerance.

- **Monitoring & Alerts**: 
  - Used **Amazon CloudWatch** for monitoring, set up alarms, and integrated **Amazon SNS** for failure notifications.

---------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🔧 **Machine Learning Load Balancer (C & Python)**

This project features a **Load Balancer** that intelligently distributes traffic using machine learning to predict server load and performance. Designed with **AWS** redundancy, the system ensures cost optimization and optimal performance.

### **Key Features**:
- **High Performance**: Developed in **C** for low-latency and efficient socket handling.
- **Machine Learning Integration**: A **Python-based ML model** predicts server load and assigns dynamic weights.
- **Dynamic Scalability**: Adapts to real-time changes in server conditions.
- **Customizable Metrics**: Supports metrics such as CPU usage, memory utilization, and latency for load predictions.

### **Technologies Used**:
- **C**: For socket programming and multithreading (pthread).
- **Python**: For machine learning (scikit-learn, joblib).
- **Communication Tools**: Python-C API for integration.

### **Possible Use Cases**:
- **Traffic Allocation**: Distributes traffic dynamically based on load predictions.
- **Server Readiness Score**: Uses ML predictions to evaluate the readiness of servers.

### **Future Enhancements**:
- Multi-cloud integration (AWS, Azure, Google Cloud).
- Real-time dashboard for visualizing server loads and traffic patterns.

---

## 🔧 Technologies & Tools I Use

- **Languages**: C++, Python, JavaScript
- **Cloud Services**: AWS (S3, EC2, Lambda, CloudFront, CloudWatch)
- **Tools**: Git, GitHub, Visual Studio Code, Linux
- **Frameworks**: Object-Oriented Programming, Data Structures, Algorithms

---

## 🔥 Current Projects

Here’s a sneak peek at some of my active projects:

### 📝 **To-Do List Project (C++)**
A task management system built using C++ that features adding tasks, tracking subtasks, and sorting by priority. [Check it out!](https://github.com/LynbergJean/To_Do_List)

### 🎮 **Hangman Game (Python)**
Collaborating with the Game Dev Club to create a simple Hangman game in Python. [View Repo](https://github.com/LynbergJean/Hangman)

---


---

Thank you for stopping by! 🚀

