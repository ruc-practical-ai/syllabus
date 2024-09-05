# Practical AI - Fall 2024

## Course Information

**Time**: Thursday 6:00 pm – 8:50 pm

**Location**: ATG/ARM-201

**Office Hours**: Mondays, 5:00 - 6:00 pm in ATG/ARM-312

**GitHub Classroom**: [https://classroom.github.com/classrooms/179165335-ruc-practical-ai-classroom](https://classroom.github.com/classrooms/179165335-ruc-practical-ai-classroom)

More information on fall semester schedules:
* [https://scheduling.rutgers.edu/scheduling/academic-calendar](https://scheduling.rutgers.edu/scheduling/academic-calendar)
* [https://camden.rutgers.edu/registrar/catalogs-calendars/2024-2025](https://camden.rutgers.edu/registrar/catalogs-calendars/2024-2025)

### Computer Use

This is a hands-on, coding-heavy course. Bringing your own computer is highly recommended when possible. If you do not have your own computer, you may use one of the computers in the lab. Many students find it easier to use their own computer.

### Instructor

**Name**: Mauro Sanchirico

**Email**: ms3978@rutgers.edu

### Where to Find This Syllabus

The latest copy of this syllabus is always available online in our class GitHub at [https://github.com/ruc-practical-ai/syllabus](https://github.com/ruc-practical-ai/syllabus). If you are referencing a hard copy, be sure to check that link for the latest version.

## Course Description

This is a one semester advanced course on the practical aspects of designing, developing, and deploying artificial intelligence (AI) applications. The course material will cover and apply to a broad span of AI methods and a similarly broad span of applications, with in-depth focus on deep learning enabled perception methods, i.e., methods for using deep neural networks for detecting, classifying, and keeping track of patterns in data. The theory of some common deep learning architectures will be briefly reviewed, but as we will see throughout the semester, knowing the theory of a specific AI technique or architecture in isolation is not enough to enable us to design, develop, and deploy robust systems which perform reliably on constantly changing real-world data.

To deploy robust systems augmented with AI capabilities, we will find that we also need to understand and account for applicable software and system considerations, account for the specific data phenomena introduced by the sensors used to collect our data, invoke techniques to explain the decisions made by deep learned system components (explainable AI, i.e., XAI), and consider how we will support our systems from initial design through deployment and continuous monitoring throughout their operational life-cycle, i.e., Machine Learning Operations (MLOps). Key principles in the ethics of deploying autonomous systems will be discussed, including the importance of what we will call the Veterinary Dentists Law, which demands that we possess expertise about AI and the systems we integrate it into (rather than just possessing expertise about AI or just expertise about a system) in the same way veterinary dentists must hold degrees in both dentistry and veterinary medicine.

The course will begin with the mathematical fundamentals of practical deep learning, with special treatment of topics in statistics, optimization, and numerical methods that will aid our analysis throughout the semester. Some modern history which will place the course in historical context will be covered along with fundamentals in machine learning and software. The course will proceed throughout the entire AI life-cycle, starting with data collection, where we will learn how the sensors that collect our data can influence its quality and add phenomena to the data. We will cover the practical aspects of formulating a new AI project, accounting for ethical principles from the beginning, designing our systems to meet runtime constraints, implementing, and testing the software for those systems.

The Machine Learning Operations (MLOps) cycle will be discussed, including data augmentation, transformation, model selection, continuous training, and monitoring. Special classes will be dedicated to XAI methods (LIME, SHAP, counterfactuals, and integrated gradients) and robustness testing, including methods for handling noise, confounding attributes, and adversarial attacks on AI systems (i.e., adversarial AI). Differences between whitebox and blackbox attacks will be covered, along with attacks on AI systems at different phases of the MLOps lifecycle, including data poisoning, evasion techniques, adversarial perturbations, and model stealing. Students will have the opportunity to practice developing secure AI systems by gaming their AI systems against each other.

### Pre-requisite Knowledge

Students should be comfortable with the mathematical fundamentals behind modern AI, specifically those that underpin deep learning, including linear algebra, correlation, model fitting, optimization, and numerical methods. Students should be proficient in Python and know how to set up local and remote Python development environments (i.e., students should be comfortable installing Python and associated libraries on their local computers and using these tools through remote tools like GitHub Codespaces and Amazon Web Services). Students do not need to be C++ experts but should be familiar writing and compiling a limited amount of C++ code or able to learn to do so quickly.

Familiarity with tools including scikit-learn, torch, torch lightning, thunder, pandas, matplotlib, numpy, cupy, Open Neural Network Exchange (ONNX) and Continuous Integration / Continuous Deployment (CI/CD) pipelines may be helpful but is not required. Previous familiarity with machine learning algorithms including deep neural networks, support vector machines, decision trees, and ensemble methods is helpful but not explicitly required for students possessing the mathematical background to learn these methods quickly. Mathematical and software fundamentals will be reviewed so the course is as self-contained as possible.

### Software Development and Professionalism

This is a hands-on, coding-heavy course. The course is designed to mirror the environment students will encounter when working in a professional machine learning team. Classes will be taught in an interactive manner using GitHub and all assignments will require submitting code using Git. Students should be comfortable installing and setting up tools for software development, or ready to learn to do so quickly. At the end of each class, we will review tools students should install to be prepared for the next class and students are expected to be ready to work with these tools by the next class.

Students should be comfortable modifying code and should be ready to learn to write entirely new code from sets of high-level directions and requirements. Students should be prepared to write professional-quality reports in the form of Jupyter notebooks and GitLab markdown documentation visualizing the results of their assignments. Taking RUC’s Data Management and Visualization course provides helpful background in this but is not a strictly required prerequisite.

### Class Resources

Several guides are provided to help students with this course.

* Setting up a development environment: [https://github.com/ruc-practical-ai/development-environment-setup](https://github.com/ruc-practical-ai/development-environment-setup)
* Using GitHub Codespaces: [https://github.com/ruc-practical-ai/codespaces-tutorial](https://github.com/ruc-practical-ai/codespaces-tutorial)

## Grading Policy

The semester will use the following grading scheme.

* 4 quizzes: 15%
* 6 homework assignments: 45%
* 1 midterm examination: 20%
* 1 final project: 20%

### Final Grades

* 89.5 - 100.0 = A
* 86.5 - 89.49 = B+
* 79.5 - 86.49 = B
* 76.5 - 79.49 = C+
* 69.5 - 76.49 = C
* 59.5 - 69.49 = D
* 00.0 - 59.49 = F

### Extra Credit

There will be a handful of opportunities for extra credit, potentially to include student research in special topics. Any point(s) awarded are applied directly to your final grade, up to a maximum of 4 points.

### Course Outline

* **09/05**: First day of class
* **10/17**: Midterm Exam
* **11/28 - 12/1**: Thanksgiving break
* **12/05**: Last day of class
* **12/06-12/19**: Fall reading period and exams (final project working time)
* **12/19**: Final project due

Our week-to-week schedule is organized as follows, though it is subject to change depending on class pace and interests. Assignments and quizzes will always be announced at least one week in advance. Special topics of interest to students may be discussed.

#### 09/05: Class 01 - Course introduction, Mathematical Fundamentals
* Course introduction and motivation
* Statistics
* Linear algebra
* Linear and nonlinear functions
* Optimization
* Correlation, fitting, and mutual information
* Transforms

#### 09/12: Class 02 - History and Background of Modern Deep Learning Techniques
* Hodgkin and Huxley
* Perceptrons and XOR problem
* Backpropagation
* Universal Approximation
* Autoencoding
* Convolutional Neural Networks
* Deep Dream
* Attention
* Google Circuits Project (explainable AI introduction)

#### 09/19: Class 03 - Programming Fundamentals
* Bash
* Python, Jupyter and associated libraries
* Git / GitLab
* Review of compilers vs. interpreters
* C++ basics
* Tools of the trade: scikit-learn, torch, torch lightning and torch thunder, pandas, matplotlib, numpy, CUDA, cupy, Open Neural Network Exchange (ONNX)
* Continuous Integration / Continuous Deployment
* Unit Testing
* Software hygiene

#### 09/26: Class 04 - Machine Learning Basics
* Separation of training and testing data
* The necessity of data diversity
* Data drift
* Model fitting power and capacity
* Keeping track of model decisions over time
* The need to automate model training
* Basic model evaluation metrics

#### 10/03: Class 05 - Advanced Data Input and Output Considerations
* Understanding signal to noise ratio (SNR) considerations
* Time series data collection
* Imagery data collection
* How cameras work
* How radios work
* Know your actuator

#### 10/10: Class 06 - Formulating an AI Project
* Developing a use case for AI techniques (with special emphasis on deep learning)
* AI incidents and AI ethics
* Avoiding unintended negative consequences
* The Veterinary Dentists Law
* Hardware considerations
* Selecting data sources
* Understanding how the output will be used

#### 10/17: Mid-term Examination

#### 10/24: Class 07 - AI System Design
* Understanding clean, noisy, and pre-processed data
* Data quality and data cleaning techniques
* Preprocessing techniques
* Postprocessing techniques
* Identifying who will use the outputs of a model
* Guardrails

#### 10/31: Class 08 - Machine Learning Operations Lifecycle
* The end-to-end machine learning operations lifecycle
* Data augmentation
* Data transformation
* Model selection
* Regularization and bias mitigation
* Explainability
* Model monitoring
* Robustness testing
* Software testing and CI/CD

#### 11/07: Class 09 - Explainable AI (XAI)
* Global vs. local explainability
* Surrogate models
* Symbolic regression
* Attribution and feature importance
* SHAP, LIME, counterfactuals, and integrated gradients
* Neuron by neuron attribution (circuits project)
* DeepDream

#### 11/14: Class 10 - Robustness
* Handling noise
* Handling confounders
* Sparse data
* Adversarial AI
* Blackbox vs. whitebox attacks
* Poisoning, evasion, perturbation, model stealing
* Defenses
    * Exploration and environmental interaction
    * Privacy preservation
    * Sanitization
    * Adversarial training
    * Multiple models

#### 11/21: Class 11 - Putting it All Together: AI System Examples
* Image classification
* Time series classification
* Flight control
* Algorithmic trading
* Facial recognition
* Return to AI ethics and AI incidents

#### 12/05: Class 12 - Final Project (Adversarial AI Tournament)
* Grading rubric
* How the tournament works
* Suggested techniques
* The role of the environment
* Suggestions for offense and defense

## Course References

This course will be taught from current literature. References will be distributed throughout the semester. There is no required textbook.

## Ethical Use of AI Technologies and Large Language Models

Large Language Models (LLMs), e.g., ChatGPT, and other AI technologies are powerful tools that are accessible to all. While you are not prohibited from using these tools to facilitate and enhance your learning experience, **you are strictly prohibited from using these tools to perform your work for you**.

Using these tools to complete assignments and/or assigned tasks is unproductive for learning and indicates a insufficient knowledge of the core material required to properly review the outputs of those AI tools for accuracy and safety. Understanding core material before applying AI to help expedite generation of tools and results is a key tenet of the ethical use of AI in industry and academia.

To elaborate on this, we will (repeatedly) make an analogy to Veterinary Dentists, and the interests we all have in ensuring those who operate on our pets are qualified to do so! To perform oral surgery on our pets, holding only the qualifications of a veterinarian or only the qualifications of a dentist is insufficient. Both degrees must be held. Similarly, to apply AI for critical applications in science and engineering, practitioners must be experts in *both* the AI techniques being applied, and the domain of application. In our discussions around the ethical use of AI in this course, we will call this the *Veterinary Dentist Law*.

**Using AI technologies in any way which immediately violates the Veterinary Dentist Law or puts you on a trajectory to increase your probability of violating the Veterinary Dentist Law in the future is considered in violation of the academic integrity policy for this course**. If an AI tool is found to be used in such a manner for any work in this course, a grade of 0 will be given for that work. No exceptions will be made.

Example violations of the Veterinary Dentist law include the following.

In this course:
* Use of AI to write code for you. This prevents you from learning how to apply the underlying techniques.

In industry, outside the context of this course:
* Use of AI in a critical application (e.g., medicine) without any team members having knowledge of that application (the team is only qualified in AI, but not in medicine).
* Use of AI in a critical application (e.g., medicine) with *only* knowledge of the application, and no knowledge of AI on the team (the team is only qualified in medicine, but not in AI). In industry, this risk is mitigated through AI training (of humans, not of models in this case!) and standards, the same as training and standards compliance are required to operate heavy machinery.

Always:
* Blind application of AI to a problem and use of results therefrom without researching and citing prior work around that problem. (See the following section on academic integrity.)

## University Policies on Academic Integrity

Principles of academic integrity require that every Rutgers University student:

* properly acknowledge and cite all use of the ideas, results, or words of others
* properly acknowledge all contributors to a given piece of work
* make sure that all work submitted as his or her own in a course or other academic activity is produced without the aid of unsanctioned materials or unsanctioned collaboration
* obtain all data or results by ethical means and report them accurately without suppressing any results inconsistent with his or her * interpretation or conclusions
* treat all other students in an ethical manner, respecting their integrity and right to pursue their educational goals without interference. This requires that a student neither facilitate academic dishonesty by others nor obstruct their academic progress
* uphold the canons of the ethical or professional code of the profession for which he or she is preparing.

Adherence to these principles is necessary in order to insure that:

* everyone is given proper credit for his or her ideas, words, results, and other scholarly accomplishments
* all student work is fairly evaluated and no student has an inappropriate advantage over others
* the academic and ethical development of all students is fostered
* the reputation of the University for integrity in its teaching, research, and scholarship is maintained and enhanced.

Failure to uphold these principles of academic integrity threatens both the reputation of the University and the value of the degrees awarded to its students. Every member of the University community therefore bears a responsibility for ensuring that the highest standards of academic integrity are upheld.

Infractions are not taken lightly and will fully be pursued. For additional information, visit [http://academicintegrity.rutgers.edu/](http://academicintegrity.rutgers.edu/)

## University Policies on Disabilities

Rutgers University welcomes students with disabilities into all of the University's educational programs. In order to receive consideration for reasonable accommodations, a student with a disability must contact the appropriate disability services office at the campus where you are officially enrolled, participate in an intake interview, and provide documentation:

[https://ods.rutgers.edu/students/documentation-guidelines](https://ods.rutgers.edu/students/documentation-guidelines).

If the documentation supports your request for reasonable accommodations, your campus’s disability services office will provide you with a Letter of Accommodations. Please share this letter with your instructors and discuss the accommodations with them as early in your courses as possible. To begin this process, please complete the Registration form at [https://webapps.rutgers.edu/student-ods/forms/registration](https://webapps.rutgers.edu/student-ods/forms/registration).
