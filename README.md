# Pibit.ai

## Q. Short Assignment: Write a ChatGPT Prompt which takes your Resume as input and parse the content in JSON format. Share Github Link of the solution if possible.

```
prompt = """
Parse the following resume content into JSON format.

Resume:
Naga Venkata Yaswanth Lankadasu
Linkedin: linkedin.com/in/lnvyaswanth/
GitHub: github.com/yaswanth-github/
Email: lnvyeswanth1575@gmail.com
Mobile: +91-7731905045

SKILLS
• Languages: Python, Java, C++, JavaScript, C
• Frameworks: HTML and CSS, Bootstrap, NodeJS, React
• Tools/Platforms: MySQL, MongoDB, Git/GitHub
• Soft Skills: Problem-Solving Skills, Team Player, Project Management, Adaptability

SUMMER TRAINING
Jun2023-Jul2023
• ProgrammingPathshala
  App development for IOS and Android | Flutter Developer
  ◦ About: Spearheaded the development of a cross-platform healthcare mobile app for iOS and Android, addressing healthcare needs with a focus on a blood donation platform.
  Proficiently managed version control using Git throughout the development lifecycle, resulting in 97% code stability and 30% faster issue resolution.
  ◦ Tech stacks used: Flutter, MySQL, Figma, Dart, GitHub.

PROJECTS
• AyurBharat | Symptom-based Disease detection algorithm:
  ◦ Developed and implemented an innovative website utilizing symptom-based disease detection algorithms, resulting in a 40% reduction in misdiagnosis and improved patient outcomes.
  ◦ Leveraged ML, Python, Django, and REST API for website development, contributing to a 40% reduction in response time and a 25% increase in user engagement through enhanced data analysis capabilities.
  Tech: Python3, Linux, Bash, Django, REST API, ML
• Exploratory Data Analysis on Suicides in India:
  ◦ Analyzed sizable datasets using advanced statistical techniques, uncovering key insights that drove strategic decision-making and increased customer retention by 15%.
  ◦ Strengthened data analysis skills through effective management and analysis of large datasets, resulting in a 20% increase in accuracy and 30% improvement in efficiency.
  Tech: Data Analysis, Python3, ML.

RESEARCH EXPERIENCE
• Skin Cancer Classification using a Convolutional Neural Network: An Exploration into Deep Learning
  Sep 2023 - Dec 2023 Researcher
  ◦ Implementation and Fine-tuning of CNN Models: Renovated and refined CNN architectures tailored specifically for dermatoscopic image analysis. This process involved tasks such as data preprocessing, model design, and performance optimization.
  ◦ Research Methodology: Developed expertise in designing and conducting experiments, collecting, and analyzing data, and drawing meaningful conclusions from experimental results.

CERTIFICATES
• Development in Flutter by Programming Pathshala.
• Introduction to Hardware and Operating Systems. (Coursera)
• The Bits and Bytes of Computer Networking. (Coursera)

ACHIEVEMENTS
• Selected Among 120 Teams in Smart India Hackathon:
  Emerged as one of the top selections from 120 teams during the 36-hour hackathon gateway for SIH2023.
• Google Crowdsource top contributors:
  Secured one of the top 5 contributors for weeks 3 and 5 all over India.
• One among Dean’s top 10 % students at university:
  For good academic performance and extra-curricular activities at university.

EDUCATION
• Lovely Professional University
  Bachelor of Technology - Computer Science and Engineering AI-ML; CGPA: 7.52
  Punjab, India
  Since Jul 2021
• Bharatiya Vidya Bhavans Residential Public School
  Intermediate; Percentage: 86%
  Tadepalligudem, Andhra Pradesh
  Jun 2019 - May 2021
• Bharatiya Vidya Bhavans Residential Public School
  Matriculation; Percentage: 67.6%
  Tadepalligudem, Andhra Pradesh
  Jun 2018 - Apr 2019
"""
```

## Output JSON:

```
{
  "Name": "Naga Venkata Yaswanth Lankadasu",
  "LinkedIn": "linkedin.com/in/lnvyaswanth/",
  "GitHub": "github.com/yaswanth-github/",
  "Email": "lnvyeswanth1575@gmail.com",
  "Mobile": "+91-7731905045",
  "Skills": {
    "Languages": ["Python", "Java", "C++", "JavaScript", "C"],
    "Frameworks": ["HTML", "CSS", "Bootstrap", "NodeJS", "React"],
    "Tools/Platforms": ["MySQL", "MongoDB", "Git/GitHub"],
    "Soft Skills": ["Problem-Solving Skills", "Team Player", "Project Management", "Adaptability"]
  },
  "Summer Training": {
    "Period": "Jun 2023 - Jul 2023",
    "Organization": "ProgrammingPathshala",
    "Role": "Flutter Developer",
    "About": "Spearheaded the development of a cross-platform healthcare mobile app for iOS and Android, addressing healthcare needs with a focus on a blood donation platform. Proficiently managed version control using Git throughout the development lifecycle, resulting in 97% code stability and 30% faster issue resolution.",
    "TechStacksUsed": ["Flutter", "MySQL", "Figma", "Dart", "GitHub"]
  },
  "Projects": [
    {
      "Title": "AyurBharat",
      "Description": "Symptom-based Disease detection algorithm",
      "Details": "Developed and implemented an innovative website utilizing symptom-based disease detection algorithms, resulting in a 40% reduction in misdiagnosis and improved patient outcomes. Leveraged ML, Python, Django, and REST API for website development, contributing to a 40% reduction in response time and a 25% increase in user engagement through enhanced data analysis capabilities.",
      "Tech": ["Python3", "Linux", "Bash", "Django", "REST API", "ML"]
    },
    {
      "Title": "Exploratory Data Analysis on Suicides in India",
      "Description": "Analyzed sizable datasets using advanced statistical techniques, uncovering key insights that drove strategic decision-making and increased customer retention by 15%. Strengthened data analysis skills through effective management and analysis of large datasets, resulting in a 20% increase in accuracy and 30% improvement in efficiency.",
      "Tech": ["Data Analysis", "Python3", "ML"]
    }
  ],
  "Research Experience": [
    {
      "Title": "Skin Cancer Classification using a Convolutional Neural Network: An Exploration into Deep Learning",
      "Period": "Sep 2023 - Dec 2023",
      "Role": "Researcher",
      "Description": "Implementation and Fine-tuning of CNN Models: Renovated and refined CNN architectures tailored specifically for dermatoscopic image analysis. This process involved tasks such as data preprocessing, model design, and performance optimization. Developed expertise in designing and conducting experiments, collecting, and analyzing data, and drawing meaningful conclusions from experimental results."
    }
  ],
  "Certificates": [
    "Development in Flutter by Programming Pathshala",
    "Introduction to Hardware and Operating Systems (Coursera)",
    "The Bits and Bytes of Computer Networking (Coursera)"
  ],
  "Achievements": [
    "Selected Among 120 Teams in Smart India Hackathon: Emerged as one of the top selections from 120 teams during the 36-hour hackathon gateway for SIH2023.",
    "Google Crowdsource top contributors: Secured one of the top 5 contributors for weeks 3 and 5 all over India.",
    "One among Dean’s top 10% students at university: For good academic performance and extra-curricular activities at university."
  ],
  "Education": [
    {
      "Institution": "Lovely Professional University",
      "Degree": "Bachelor of Technology - Computer Science and Engineering AI-ML",
      "CGPA": 7.52,
      "Location": "Punjab, India",
      "Period": "Since Jul 2021"
    },
    {
      "Institution": "Bharatiya Vidya Bhavans Residential Public School",
      "Degree": "Intermediate",
      "Percentage": 86,
      "Location": "Tadepalligudem, Andhra Pradesh",
      "Period": "Jun 2019 - May 2021"
    },
    {
      "Institution": "Bharatiya Vidya Bhavans Residential Public School",
      "Degree": "Matriculation",
      "Percentage": 67.6,
      "Location": "Tadepalligudem, Andhra Pradesh",
      "Period": "Jun 2018 - Apr 2019"
    }
  ]
}

```
