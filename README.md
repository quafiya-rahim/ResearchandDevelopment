# ResearchandDevelopment
1. What is HTML?

--Think of it as the skeleton of a webpage — it gives structure to the content like text, images, links, tables, etc.
   We use HTML to:

   1)Structure content (like headings, paragraphs, images, lists, tables).
   2)Connect web pages using hyperlinks.
   3)Help browsers understand how to display content.
   4)Work with CSS & JavaScript to make websites look beautiful and interactive.
                                                   HTML+CSS+JAVA Script . 

2. What is CSS?
--While HTML gives structure and content (like headings, paragraphs, images),
CSS controls the look and layout of that content — such as colors, fonts, spacing, and positioning.

3. What is website dev?
--Website development is the process of making a website work and look good.
  It’s like building a house:

                      HTML = the walls and structure (the content)

                      CSS = the paint and decoration (the design)

                     JavaScript = the electricity and movement (the actions and logic)

Front End using (html,css,java) ND Back End concept(python,java ,etc.works with mySQL ):

Web Hosting:Once a website is created, it must be stored on a server so that people can access it through the internet.
            The website is published using a domain name like www.google.com

4. what is good analytics and web analytics and list and R &D about the competitive tools of Google or web analytics?

--Web analytics helps you understand your website visitors so you can improve your site’s performance.
  -How many people visited your website.
  -Which country they came from.
  -Which product pages they looked at.
  -How many people bought something.
  -Where people left your site without buying.

   Google Analytics (GA) is the most popular tool used for web analytics.
  Other tools:-matomo -clicky -adobe analytics -hotjar -crazy egg ,etc.

5. what is digital analytics?

--Digital Analytics means collecting, measuring, and analyzing data from all your digital channels:
  🌍 Websites ,📱 Mobile apps ,💬 Social media (Instagram, Facebook, X, etc.),✉️ Emails,🎥 Online ads (Google Ads, YouTube Ads, etc.)
   Tools: adobe analytics ,hotjar ,google analytics etc.

6. What is looker?
--Looker is a data analytics and business intelligence (BI) tool by Google.

7. what is business analysis?
---DA for uncovering the what and why from data.
   BA for turning insights into business action.

   Business Analysis means studying a business — how it works, what problems it faces, and how it can improve — 
   to help the company make better decisions and achieve its goals.
   A Business Analyst (BA) acts like a bridge between business people and technical people.
   They understand the business needs, and then help design solutions (like new processes, software, or strategies).

8. what is DNS?
--Domain Name System :- Translator between human-friendly website names and computer-friendly IP addresses.

9. What is web scrapping?
---Web Scraping means automatically collecting data from websites using a tool or a program instead of doing it manually.
   Web scraping = Reading and copying data from a website automatically using code or a tool.
   can write a small Python program (or use a tool like ParseHub or Octoparse) that.
   other tools:BeautifulSoup → easy and beginner-friendly.
               Scrapy → powerful framework for large websites
               Selenium → for scraping dynamic sites (like JavaScript-heavy pages)
               Octoparse / ParseHub → no coding required (click-based tools 

10. what is data security?
---protecting digital data from unauthorized access, corruption, theft, or loss throughout its entire life cycle.
   It ensures that the data remains confidential, accurate, and available to only the right people.
   methods:Encryption,access contro,data masking,coud security, backup recovery, etc.

   Data Security Laws and Regulations:1) GDPR (General Data Protection Regulation) – Europe
                                      2) HIPAA (Health Insurance Portability and Accountability Act) – USA (health data)
                                      3) IT Act 2000 – India (cybersecurity and digital crimes)
                                      4) CCPA (California Consumer Privacy Act) – USA (consumer data rights)

  Common Threats to Data Security:Phishing attacks – Fake emails tricking users to reveal passwords.

                                  Malware and Ransomware – Malicious software that steals or locks data.

                                  Insider threats – Employees misusing access to sensitive data.

                                   Data breaches – Unauthorized access and data leaks.

                                   Human errors – Accidental sharing or deletion of data.

                                   Physical theft – Stolen laptops, USB drives, or paper files.

11. which compliances comes under the data security globally?

---Global Compliance regulations:-
   GDPR (General Data Protection Regulation)-->EU
   HIPAA (Health Insurance Portability and Accountability Act)-->USA
   PCI DSS (Payment Card Industry Data Security Standard)-->Global
   CCPA / CPRA (California Consumer Privacy Act / Privacy Rights Act)-->USA
   LGPD-->Brazil
   PIPEDA (Personal Information Protection and Electronic Documents Act)-->Canada
   APPI (Act on Protection of Personal Information)-->Japan  etc.
   
12. what is PCI DSS? HOW it is helpful?
---PCI DSS stands for Payment Card Industry Data Security Standard. It’s a global information security standard designed
   to ensure that all companies that process, store, or transmit credit card information maintain a secure environment.
    It was developed by the Payment Card Industry Security Standards Council (PCI SSC) — founded by major credit card 
    brands like Visa, MasterCard, American Express, Discover, and JCB.
    PCI DSS was invented to unify these standards into one global framework for securing payment card data.

                                             PURPOSE
  1. Protect Cardholder Data
  2. Reduce the Risk of Data Breaches and Fraud
  3. Establish a Baseline of Security Best Practices
  4. Ensure Trust in Digital Payments  ....etc.

13. data visualization?
---involves the graphical representation of information and data. By using visual elements like charts, graphs,
   maps, and dashboards, data visualization tools make it easier to see patterns, trends, and outliers in large data sets.

   Tools:-execl , tableau, power bi, looker, python(matplotlib nd seaborne).

14. Cursor? --- IDE tools?
---Cursor is an AI-powered code editor (IDE).
   Think of Cursor as your coding notebook + AI helper combined:
   When you type code, Cursor can:1)Suggest code as you type (like auto-complete but smarter)
                                  2)Explain code you don’t understand
                                  3)Fix errors automatically
                                  4)Generate new code from natural language instructions (you can just say what you want!)

15. software developemet life cycle? 
---Software Development Life Cycle (SDLC) is a step-by-step process that helps =developers gathering requirement & Analysis,
   =plan, =design, =build, =test and =deliver software in an organized way.

It ensures the final software is high quality, meets user needs, and is delivered on time.

16. SQL ENGINE?

 ---SQL Engine(Brain of the database system) Components:-
1. User Input (Query): Where queries originate.
2. Query Parser: Validates and structures the query.
3. Query Optimizer: Finds the best way to execute the query.
4. Query Executor: Runs the query and fetches data from the database.
5. Database: The storage system containing tables and records.
6. Result: The output delivered to the user.


notes:-SQL queries are used to extract, transform, and load (ETL) data for analysis.


revise this query:-3. Combining CASE and NULL Handling
Problem:
Classify students&#39; performance after substituting NULL Marks with a default value.
Query:
SELECT 
    StudentID,Name,Subject,
    COALESCE(Marks, 50) AS AdjustedMarks,
    CASE 
        WHEN COALESCE(Marks, 50) &gt;= 85 THEN &#39;Excellent&#39;
        WHEN COALESCE(Marks, 50) &gt;= 70 THEN &#39;Good&#39;
        ELSE &#39;Needs Improvement&#39;
    END AS Performance
FROM StudentGrades;

Having Clause:-Group by Region and Filter for Regions with Total Sales Greater Than 5


SELECT Region, SUM(Quantity) AS TotalQuantity
FROM SalesData
GROUP BY Region
HAVING SUM(Quantity)> 5;
 

                                                           TASKS 
-------------------------------------------------------------------------------------------------------------------------
16. PROJECT - PROTFOLIO CREATION WITH DOMAIN AND GIT HUB HOSTING?
17. Allison  -- e learning platform? ---- learn here promt generation --- 2 hrs hours and certificate will be issues 
    --- 700 rs.
18. web srapping? using the beautifull soup ? python --- data collection from web pages?
19. https://alison.com/course/basics-of-aws-redshift#google_vignette.(AWD REDSHIFT)
20.https://alison.com/course/aws-devops-continuous-integration-delivery-and-deployment(CI/CD pipelines).
21.https://alison.com/course/web-design-with-html(HTML WEBDESIGN).
22.https://alison.com/course/diploma-in-gdpr-and-data-protection.
23.https://alison.com/course/data-protection-officer-training#google_vignette.

================================================================
* do R and D..
* understand wht you need to be done.
* purpose
* outcome
* promte generation
================================================================

I’m a B.Com graduate and certified Data Analyst with a strong interest in turning raw data into meaningful insights.
 Skilled in Excel, Power BI, SQL, and Python, I enjoy finding patterns in data that help businesses make smarter decisions.
 As a fresher, I’m eager to apply my analytical and visualization skills to real-world projects and grow in the 
field of data analytics.
