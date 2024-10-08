# Tech Playground Challenge

Welcome to the **Tech Playground Challenge**!

## About the Challenge

This is your opportunity to dive into a real-world dataset and create something extraordinary. Whether you're passionate about data analysis, visualization, backend development, or creative exploration, there's a task here that's perfect for you. Choose the challenges that excite you and let your skills shine!

## How to Participate

- **Choose Your Tasks**: Pick any tasks from the checklist below that spark your interest. You're free to choose as many or as few as you like.
- **Showcase Your Skills**: Focus on creating high-quality, well-thought-out solutions.
- **Use Your Favorite Tools**: Feel free to use any programming languages, frameworks, or tools you're comfortable with.

## Dataset Overview

The provided dataset (`data.csv`) contains employee feedback data with fields in Portuguese. The data includes:

- **nome** (Name)
- **email**
- **email_corporativo** (Corporate Email)
- **celular** (Mobile Phone)
- **area** (Department)
- **cargo** (Position)
- **funcao** (Function)
- **localidade** (Location)
- **tempo_de_empresa** (Company Tenure)
- **genero** (Gender)
- **geracao** (Generation)
- **n0_empresa** (Company Level 0)
- **n1_diretoria** (Directorate Level 1)
- **n2_gerencia** (Management Level 2)
- **n3_coordenacao** (Coordination Level 3)
- **n4_area** (Area Level 4)
- **Data da Resposta** (Response Date)
- **Interesse no Cargo** (Interest in Position)
- **Comentários - Interesse no Cargo** (Comments - Interest in Position)
- **Contribuição** (Contribution)
- **Comentários - Contribuição** (Comments - Contribution)
- **Aprendizado e Desenvolvimento** (Learning and Development)
- **Comentários - Aprendizado e Desenvolvimento** (Comments - Learning and Development)
- **Feedback**
- **Comentários - Feedback** (Comments - Feedback)
- **Interação com Gestor** (Interaction with Manager)
- **Comentários - Interação com Gestor** (Comments - Interaction with Manager)
- **Clareza sobre Possibilidades de Carreira** (Clarity about Career Opportunities)
- **Comentários - Clareza sobre Possibilidades de Carreira** (Comments - Clarity about Career Opportunities)
- **Expectativa de Permanência** (Expectation of Permanence)
- **Comentários - Expectativa de Permanência** (Comments - Expectation of Permanence)
- **eNPS** (Employee Net Promoter Score)
- **[Aberta] eNPS** (Open Comments - eNPS)

**Note**: Since the data is in Portuguese, you may need to handle text processing accordingly, especially for tasks involving text analysis or sentiment analysis.

## Task Checklist

Select the tasks you wish to complete by marking them with an `X` in the `[ ]` brackets.

### **Your Selected Tasks**

- [ ] **Task 1**: Create a Basic Database
- [ ] **Task 2**: Create a Basic Dashboard
- [ ] **Task 3**: Create a Test Suite
- [ ] **Task 4**: Create a Docker Compose Setup
- [ ] **Task 5**: Exploratory Data Analysis
- [ ] **Task 6**: Data Visualization - Company Level
- [ ] **Task 7**: Data Visualization - Area Level
- [ ] **Task 8**: Data Visualization - Employee Level
- [ ] **Task 9**: Build a Simple API
- [ ] **Task 10**: Sentiment Analysis
- [ ] **Task 11**: Report Generation
- [ ] **Task 12**: Creative Exploration

---

## Task Descriptions

### **Task 1: Create a Basic Database**

**Objective**: Design and implement a database to structure the data from the CSV file.

**Requirements**:

- Choose an appropriate database system (relational or non-relational) such as MySQL, PostgreSQL, MongoDB, etc.
- Design a schema or data model that accurately represents the data, considering the Portuguese field names.
- Write scripts or use tools to import the CSV data into the database.
- Ensure data integrity and appropriate data types for each field.
- Provide database creation scripts or configurations and instructions on how to set it up.

**Bonus**:

- Implement indexing or other optimizations for faster query performance.
- Organize the data efficiently to reduce redundancy and improve access speed.

---

### **Task 2: Create a Basic Dashboard**

**Objective**: Develop a simple dashboard to display important data insights.

**Requirements**:

- Use any frontend technology (e.g., HTML/CSS, JavaScript, React, Angular, Vue.js).
- Connect the dashboard to your database or use the CSV file directly.
- Display key metrics such as:

  - Number of employees per department (**area**).
  - Average feedback scores.
  - eNPS distribution.

- Include interactive elements like filtering by department (**area**) or position (**cargo**).
- Ensure the dashboard is user-friendly and visually appealing.

**Bonus**:

- Implement responsive design for mobile compatibility.
- Add advanced visualizations using charting libraries (e.g., D3.js, Chart.js).

---

### **Task 3: Create a Test Suite**

**Objective**: Write tests to ensure the reliability and correctness of your codebase.

**Requirements**:

- Use a testing framework relevant to your chosen language (e.g., pytest for Python, JUnit for Java, Jest for JavaScript).
- Write unit tests for key functions or components.
- Include tests for edge cases and error handling.
- Provide instructions on how to run the tests.

**Bonus**:

- Achieve high code coverage.
- Implement integration tests to test interactions between components.

---

### **Task 4: Create a Docker Compose Setup**

**Objective**: Containerize your application and its services using Docker Compose.

**Requirements**:

- Write a `Dockerfile` for your application.
- Create a `docker-compose.yml` file to define services (e.g., application server, database).
- Ensure that running `docker-compose up` sets up the entire environment.
- Provide instructions on how to build and run the containers.

**Bonus**:

- Use environment variables for configuration.
- Implement multi-stage builds to optimize image size.

---

### **Task 5: Exploratory Data Analysis**

**Objective**: Analyze the dataset to extract meaningful insights.

**Requirements**:

- Compute summary statistics (mean, median, mode, etc.) for numerical fields.
- Identify trends or patterns (e.g., average feedback scores by department (**area**)).
- Visualize key findings using charts or graphs.
- Provide a brief report summarizing your insights.

---

### **Task 6: Data Visualization - Company Level**

**Objective**: Create visualizations that provide insights at the company-wide level.

**Requirements**:

- Develop at least two visualizations that represent data across the entire company.
- Examples include:

  - Overall employee satisfaction scores.
  - Company-wide eNPS scores.
  - Distribution of company tenure among all employees.

- Ensure visualizations are clear, labeled, and easy to understand.
- Explain what each visualization reveals about the company.

**Bonus**:

- Use interactive dashboards or advanced visualization techniques.
- Incorporate time-series analysis if temporal data is available.

---

### **Task 7: Data Visualization - Area Level**

**Objective**: Create visualizations focusing on specific areas or departments within the company.

**Requirements**:

- Develop at least two visualizations that provide insights at the area or department level.
- Examples include:

  - Average feedback scores by department (**area**).
  - eNPS scores segmented by department.
  - Comparison of career expectations across different areas.

- Include interactive elements such as filtering or hovering to display more information.
- Ensure visualizations are clear, labeled, and easy to understand.
- Explain what each visualization reveals about the different areas.

**Bonus**:

- Highlight significant differences or trends between departments.
- Suggest possible reasons for observed patterns based on the data.

---

### **Task 8: Data Visualization - Employee Level**

**Objective**: Create visualizations that focus on individual employee data.

**Requirements**:

- Develop visualizations that provide insights at the employee level.
- Examples include:

  - An individual employee's feedback scores across different categories.
  - A profile visualization summarizing an employee's tenure, position, and feedback.
  - Comparison of an employee's scores to department or company averages.

- Ensure privacy considerations are met (e.g., anonymize data if necessary).
- Explain how these visualizations can be used for employee development or management.

**Bonus**:

- Create a template that can generate individual reports for any employee.
- Include recommendations or action items based on the data.

---

### **Task 9: Build a Simple API**

**Objective**: Develop an API to serve data from the dataset.

**Requirements**:

- Implement at least one endpoint that returns data in JSON format.
- Use any framework or language you're comfortable with.
- Include instructions on how to run and test the API.

**Bonus**:

- Implement multiple endpoints for different data queries.
- Include pagination or filtering options.

---

### **Task 10: Sentiment Analysis**

**Objective**: Perform sentiment analysis on the comment fields.

**Requirements**:

- Preprocess the text data (e.g., tokenization, stop-word removal).
- Use any method or library to analyze sentiment in Portuguese (e.g., NLTK with Portuguese support, spaCy with Portuguese models).
- Summarize the overall sentiment and provide examples.
- Document your approach and findings.

**Note**: Since the comments are in Portuguese, ensure that your tools and methods support processing text in Portuguese.

---

### **Task 11: Report Generation**

**Objective**: Generate a report highlighting key aspects of the data.

**Requirements**:

- Include tables, charts, or graphs to support your findings.
- Summarize important metrics like eNPS scores or feedback trends.
- The report can be in any format (PDF, Markdown, HTML).

---

### **Task 12: Creative Exploration**

**Objective**: Explore the dataset in a way that interests you.

**Requirements**:

- Pose a question or hypothesis related to the data.
- Use the data to answer the question or test the hypothesis.
- Document your process, findings, and any conclusions drawn.

---

## Getting Started

1. **Download the Dataset**: Access `data.csv` from the repository.
2. **Choose Your Adventure**: Pick the tasks that excite you and mark them in the checklist above.
3. **Create Your Masterpiece**: Develop your solutions using your preferred tools and technologies.
4. **Share Your Work**: Organize your code and documentation, and get ready to showcase what you've built.

## Submission Guidelines

- **Code and Files**: Include all code, scripts, and other files used in your solution.
- **README**: Provide a README file that:
  - Lists the tasks you completed.
  - Explains how to run your code and view results.
  - Discusses any assumptions or decisions you made.
- **Documentation**: Include any reports or visualizations you created.
- **Instructions**: Provide clear instructions for setting up and running your project.

## Let Your Creativity Flow!

This is more than just a challenge—it's a playground for your ideas. Feel free to go beyond the tasks, add your own flair, and have fun exploring the possibilities!

---

We hope you enjoy this challenge and look forward to seeing the amazing things you create. Happy coding!
