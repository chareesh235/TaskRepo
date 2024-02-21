# Resume
## Hareesh C

Hareesh C
hareesh.chr@gmail.com | +91 9739054927 | http://linkedin.com/in/hareesh-c-9a1780196
PROFESSIONAL SUMMARY ___________________________________________________________________
Experienced Senior Software Engineer with over a decade of expertise in leading QA teams and driving end-to-end testing processes for software projects. Proficient in test case design, execution, and automation using Python, Selenium WebDriver, and other industry-standard tools. Skilled in fostering collaborative environments, and ensuring the delivery of high-quality software products. Adept at identifying and addressing critical defects, optimizing testing workflows, and achieving project objectives within stipulated timelines.
EXPERIENCE ____________________________________________________________________________________
Senior Software Engineer: ASM Technology	Oct 2019 – Oct 2023
•	Led a QA team of 10 members, cultivating collaboration for productivity and professional development
•	Supervised all aspects of the testing lifecycle, including test case writing, review, and report preparation, ensuring adherence to industry standards and best practices
•	Facilitated regular team meetings and knowledge-sharing sessions to enhance team cohesion and proficiency in testing methodologies
•	Assumed ultimate responsibility for QA sign-off, ensuring the readiness and quality of deliverables before production deployment
Senior Associate: Cognizant Technology	Oct 2016 – Oct 2019
•	Managed a proficient QA team of 20 members, ensuring cohesive and efficient in testing across projects
•	Directed the end-to-end testing process, including test case writing, review, report preparation, automation, and final QA sign-off, guaranteeing the delivery of high-quality software products
•	Implemented and optimized the Robot Framework for test automation, leading to a 30% reduction in manual testing efforts and a 40% increase in test coverage
•	Acted as a liaison between the QA team and other cross-functional teams, fostering collaboration and alignment on project objectives and timelines
Senior Software Engineer: ASM Technology	Jun 2010 – Oct 2016
•	Contributed to the QA team by actively participating in test case preparation, ensuring comprehensive coverage of system functionalities and requirements
•	Managed customer escalations efficiently, addressing concerns promptly and effectively to maintain customer satisfaction levels, achieving a 95% customer satisfaction rating
•	Conducted rigorous verification of hotfixes, ensuring the timely resolution of critical issues and minimizing system downtimes, leading to a 30% reduction in resolution time
•	Travelled onsite to the United States twice to provide direct support and facilitate collaboration between offshore teams and clients, enhancing collaboration and understanding of project requirements
SKILLS ___________________________________________________________________________________________
 
•	Python
•	API Testing
•	AWS
•	Kafka
•	Test Case Design
•	Regression Testing
•	Selenium WebDriver
•	TestNG
•	HDFS
•	S3
•	Exploratory Testing
•	CI/CD
•	Jenkins
•	BigData
•	IOT 
•	Security Testing
•	Confluence
•	System Testing
•	Docker
•	macOS
•	Gitlab
•	MySQL
•	MongoDB
•	Jira 
PROJECTS _______________________________________________________________________________________
EclecticIQ | Python-Flask, RabbitMQ, GIT, Jenkins, REST API	Aug 2021 – Oct 2023
•	Engaged in preliminary discussions with the development team to comprehend new features, ensuring a seamless transition from development to testing
•	Achieved a 20% reduction in miscommunication by participating in requirement clarification sessions
•	Participated in test case review sessions, contributing to a 10% increase in the overall quality of test documentation and provided constructive feedback, ensuring alignment with development goals 
•	Identified and addressed critical defects, leading to a 25% reduction in post-release issues and utilized JIRA for bug tracking, ensuring efficient coordination with the development team
•	Raised and tracked to the closure of 50+ bugs during the testing phase and identified potential automation test cases to enhance test efficiency and coverage
BYOD | PHP, AWS	Jul 2020 – Jul 2021
•	Contributed to test planning, devising strategies for comprehensive system functionality coverage
•	Participated in the design phase by outlining test scenarios and prioritizing testing activities, achieving a 15% improvement in test efficiency
•	Collaborated closely with stakeholders to understand system requirements and user expectations
•	Detected and reported critical issues promptly, contributing to a 30% reduction in high-severity defects and ensured adherence to quality standards and best practices throughout the testing process
EDUCATION _____________________________________________________________________________________
EWIT College of engineering, Bangalore (VTU)	Sep 2004 – Aug 2008 
Bachelor of Engineering in Electronics and Communication, 64.5%
CERTIFICATIONS _______________________________________________________________________________
•	MSCE, CCNA and Linux Admin Courses from Sun Marss Technologies
ACHIEVMENTS __________________________________________________________________________________
•	Got an award from ASM technologies for completing 5 years


For production release:

```sh
gulp build --prod
```

Generating pre-built zip archives for distribution:

```sh
gulp build dist --prod
```

## Docker

Dillinger is very easy to install and deploy in a Docker container.

By default, the Docker will expose port 8080, so change this within the
Dockerfile if necessary. When ready, simply use the Dockerfile to
build the image.

```sh
cd dillinger
docker build -t <youruser>/dillinger:${package.json.version} .
```

This will create the dillinger image and pull in the necessary dependencies.
Be sure to swap out `${package.json.version}` with the actual
version of Dillinger.

Once done, run the Docker image and map the port to whatever you wish on
your host. In this example, we simply map port 8000 of the host to
port 8080 of the Docker (or whatever port was exposed in the Dockerfile):

```sh
docker run -d -p 8000:8080 --restart=always --cap-add=SYS_ADMIN --name=dillinger <youruser>/dillinger:${package.json.version}
```

> Note: `--capt-add=SYS-ADMIN` is required for PDF rendering.

Verify the deployment by navigating to your server address in
your preferred browser.

```sh
127.0.0.1:8000
```

## License

MIT

**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
