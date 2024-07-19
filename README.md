# Resume-Parser-Prompter
This is a Gemini-Pro Resume Parser Prompter.

To run it install the following dependencies by:
```
pip install PyPDF2 google-generativeai
```

Then paste the path to the resume you want to parse in the `extract_text_from_pdf` function arguments

Enjoy!

Sample Output:
```
JSON
{
    "name": "Sujal Kulshrestha",
    "contact_information": {
        "email": "sujal.kulshrestha_cs.aiml21@gla.ac.in",
        "phone": "+91 8445433348",
        "address": null
    },
    "summary": null,
    "experience": [
        {
            "job_title": "Trainee",
            "company": "GLA University, Mathura",
            "location": null,
            "start_date": "June 2022",
            "end_date": "July 2022",
            "responsibilities": [
                "Learnt Python libraries like pandas, numpy, matplotlib, seaborn, etc for machine learning (Data Science)",
                "Learnt image processing in the field of ML and created a n image pre -processing pipeline project"
            ]
        }
    ],
    "education": [
        {
            "degree": "Bachelor of Technology in Computer Science (AIML)",
            "institution": "GLA University, Mathura",
            "location": null,
            "start_date": null,
            "end_date": "June 2025"
        },
        {
            "degree": "Intermediate",
            "institution": "St. Andrews Sr. Sec. School, Agra",
            "location": null,
            "start_date": null,
            "end_date": "May 2021"
        },
        {
            "degree": "High School",
            "institution": "St. Andrews Sr. Sec. School, Agra",
            "location": null,
            "start_date": null,
            "end_date": "May 2019"
        }
    ],
    "skills": [
        "Python",
        "Java",
        "MongoDB",
        "ExpressJS",
        "ReactJS",
        "NodeJS",
        "Django",
        "ML/DL",
        "Effective Communication Skills",
        "Effective Debugging Skills",
        "Team Management Skills",
        "Research -Based Skills"
    ],
    "projects": [
        {
            "project_name": "Learner’sEd (Students Platform)",
            "description": "Created a Web + AIML -based solution for Intel OneAPI Hackathon 2023, a platform for E -Learning, to tackle the   the native method of online learning and preventing  unfair means amongst students",
            "technologies": [
                "Django",
                "Bootstrap",
                "HTML",
                "CSS",
                "Tensorflow",
                "Python",
                "Intel OneAPI libraries"
            ]
        },
        {
            "project_name": "EchoSphere ( Grievances Redressal System )",
            "description": "Created a Web + AIML -based solution for Smart India Hackathon 2023, the main goal was to provide a platform   that makes the lodging of grievances regarding public services and facilities with the help of the NLP model that   makes the process of lodging easier for locals.",
            "technologies": [
                "React",
                "Django",
                "Bootstrap",
                "Tensorflow",
                "Python"
            ]
        },
        {
            "project_name": "AI Smart Cane",
            "description": "With the help of IoT and AIML technologies, created a smart blind stick that uses a single camera module and a  Raspberry P i (SBC) to detect the environment in front of the user and provide feedback accordingly",
            "technologies": []
        },
        {
            "project_name": "Ayakshma (Assistive Technology for Rural India)",
            "description": "Created a PWA (Progressive Web Application) that works on both online and offline mode, to tackle the challenge of  network issues",
            "technologies": [
                "NodeJS",
                "MongoDB",
                "Flask",
                "React"
            ]
        }
    ],
    "certifications": [
        {
            "certification_name": "Full Stack Web Development Certification",
            "institution": "Coursera",
            "date": "June 2023  – September  2023"
        }
    ]
}
```
