# MAKEI ALIAKSANDR

## IT Project Manager, Developer, Analyst

### Year of birth &emsp;&emsp; 1987 
### Adress &emsp;&emsp;&emsp;&emsp;&nbsp;&nbsp; Grodno, Republic of Belarus  

**Email**&emsp;       al.gr.0017@gmail.com  
[LinkedIn](https://www.linkedin.com/in/aliaksandr-m-8b508342/ "LinkedIn") | 
[GitHub](https://github.com/AlexXG0152 "GitHub") | 
[CodeWars](https://www.codewars.com/users/AlexXG0152 "CodeWars")

***
## Briefly about me  
Professional with almost 15 years experience in the field of personnel who decided to change the field of work and go to **IT**.
Trained at EPAM in **Business Analysis**.  
Independently studied **English**, **Python** (Django, Flask, Pandas), **VBA** (for MS Word and MS Excel) and everything related to IT.
Been part in the development of **software requirements** in my current job.

***
## Work experience  
### **May 2013 - up to now** &emsp; -- &emsp; **Head of the Recruitment Bureau**  
**Recruitment and Personnel Accounting Department  
Branch «Khimvolokno Plant» JSC «Grodno Azot» (production of nitrogen fertilizers, chemical fibers and polyamide-6), Grodno.**  
- planning needs in personnel;
- study labor market and search and selection specialists in different areas (interviews, development questionnaires, test tasks, etc.);
- creation and maintenance a database of candidates;
- development adaptation programs, professional development;
- organization personnel training;
- personnel assessment and certification;
- work with the reserve (formation, training, internships);
- reports preparation;
- participation in the preparation of the organization's business plan in terms of the formation and justification of personnel costs;
- management of bureau specialists (nine people);
- experience in passing audits for the organization's compliance with the requirements of international standards;
- creation a personnel accounting automation system;
- establishment of internal communications;
- maintenance of personnel documentation, development of documents / programs (standards, orders, templates, description of business processes);
- consultations of managers and employees on personnel issues;
- participation in the organization of corporate events.

### **March 2007 - April 2013** &emsp; -- &emsp; **HR specialist (category II)**
**Recruitment and Personnel Accounting Department  
Branch «Khimvolokno Plant» JSC «Grodno Azot», Grodno.** 

***
## Education  
### **2005 - 2011** &emsp; -- &emsp; BIP - Institute of Jurisprudence  
**Specialty:** &emsp; &emsp; Political Science  
**Qualification:** &emsp;political scientist - lawyer

***
## Certificates  
  
Period                        | Course name, place
---------------------------   | ---------------------------
July 2021 - September 2021    | Process Mining: Data science in Action, coursera.org, online.
February 2019 - March 2019    | Business Analyses course in EPAM, EPAM Systems, Grodno.     
June 2018                     | Personnel management. KPI, motivation, assessment and competency management tools, BelGISS, Minsk.  
February - April 2018         | HR Manager, Business School XXI VEK-CONSULT, Minsk.  
January 2011 - June 2013      | Polish language courses, Grodno.  

## Skills  
  
Skill              | Mark
----------------   | ----------------
Polish             | :red_circle::red_circle::red_circle::red_circle::red_circle::red_circle::red_circle::red_circle::white_circle::white_circle:
English            | :red_circle::red_circle::red_circle::red_circle::red_circle::red_circle::white_circle::white_circle::white_circle::white_circle:
Human Resources    | :red_circle::red_circle::red_circle::red_circle::red_circle::red_circle::red_circle::red_circle::red_circle::white_circle:
Python             | :red_circle::red_circle::red_circle::red_circle::red_circle::red_circle::white_circle::white_circle::white_circle::white_circle:
VBA                | :red_circle::red_circle::red_circle::red_circle::white_circle::white_circle::white_circle::white_circle::white_circle::white_circle:
Business Analysis  | :red_circle::red_circle::red_circle::red_circle::red_circle::red_circle::red_circle::white_circle::white_circle::white_circle:
Reports            | :red_circle::red_circle::red_circle::red_circle::red_circle::red_circle::red_circle::red_circle::white_circle::white_circle:

* Two years experience as an expert on part of customer in process of implementing **"Human Resources and Payroll"** block of **ERP system**. Description of existing business processes and systems, development requirements for a new system, implementation a new system, training and pilot start a new system.  
* **Team** management.  
* **Project** management and **scheduling**.  
* Ability to **self-study**, **responsibility**, initiative, sociability, purposefulness.
* Experienced user of **MS Windows, MacOS, iOS, Android, MS Office, Internet, CSS&HTML, Photoshop, IDE, GitHub, SQL, browsers, hardware**. 

***
## Code Examples
I'm made little one file application in Python for convert JSON-like government report file to easy check and readable .xlsx file.  
This is front-end part from file.  
Repository with file place on [GitHub](https://github.com/AlexXG0152/PU-2 "GitHub").  

```html
<!DOCTYPE html>
<html>
  <meta charset="utf-8">
  <head>
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
  <script src="https://rawgit.com/enyo/dropzone/master/dist/dropzone.js"></script>
  <link rel="stylesheet" href="https://rawgit.com/enyo/dropzone/master/dist/dropzone.css">
  </head>

  <body>
  <form action="/upload" method="post" class="dropzone" enctype="multipart/form-data" name="upload" id="upload"></form>
  <button type="button" onclick="onSubmit('/convert')">Convert</button>

  <p id="result"></p>
  <a href="example">
    <p id="response"></p>
  </a>

  <script>
    function onSubmit(value) {
      var myRequest = new Request("/convert");
      var myInit = { method: "PUT" };
      fetch(myRequest, myInit).then(response => response.text())
        .then((response) => {
            $("#response").text(response)
            $("a").prop("href", (response))
            $("#result").text("Your result .xlsx file in this folder:")
        });
    }
  </script>

  <script>
  Dropzone.options.upload = {
        acceptedFiles:'.json, .txt'       
    };
  </script>  
  
  </body>
</html>

```

Code example form [CodeWars](https://www.codewars.com/kata/5680781b6b7c2be860000036 "CodeWars") cata for find and show the index of the vowels in a given word:
```python
def vowel_indices(word):
    return [k for k, v in enumerate(word, 1) if v in "aeuioyAEUIOY"]
```

***
## Interests
* Codewars
* Сycling
* Reading
* Learning languages
* Traveling 
* Paintball / Airsoft 

*** 
## Languages  
* English - B2  
* Polish - C1  
* Ukrainian - A1  

***
