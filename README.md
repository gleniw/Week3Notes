Week 3: Test Analysis
=====================

* * *

**HTML & CSS:**

1. **What is the difference between HTML elements and HTML tags?**
   
   

   **.className** = Class Tag - Tags a group of elements

   **#IDName** = ID Tag - Single identifier used to pick out elements



2. **Why id a tag in HTML?**
   When you need to point to a specific style declaration in a style sheet

3. **What is an anchor tag?**
   The anchor tag defines a hyperlink, which is used to link from one page to another.

4. **What is a HTML attribute?**
   HTML attributes provide additional information about HTML elements.

5. **What is the difference between semantic and non-semantic tags?**
   A semantic element clearly describes its meaning to both the browser and the developer whereas non-semanic ones do not. An exmple would be <table> which is a table and <div> which is a divider.

6. **Why should we use IDs?**
   They are better for indentifcation and can take priority over other CSS styles that may effect it. 

7. **What is CSS?**
   Cascading Style Sheets - used to apply style changes to the HTML code

8. **What is the CSS box model?**
   The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content.
   ![](file:///C:/Users/Glen%20Smith/Desktop/Week%203/HTML%20&%20CSS/Margin_Border_CSS.png)

9. **Where in the HTML document do we link to a CSS file?**
   External styles are defined within the <link> element, inside the <head> section of an HTML page
   
   

**Introduction to Web & Mobile Testing**

1. **What is visual testing?**
   UI Testing
   Automated testing can check the details but what happens when it goes live?
   Example. Can users find the way to sign in?

2. **What is meant by responsive design?**
   Design that adapts to device it is being viewed on.

3. **Why is it important?**
   It makes it easier for users to then find the information they are looking for and typically encourages them to stay on your site.

4. **What is web and device fragmentation?**
   The diversity of browsers, devices, and platform versions in use at any given point in time.

5. **What is cross-browser testing?**
   The practice of verifying that web applications work as expected across many different combinations of web browsers, operating systems, and devices.

6. **How does web fragmentation relate to web testing?**
   Web browser type and version compatibility.

7. **What is the difference between functional and non-functional web testing?**
   
   ###### Functional Testing
   
   A type of testing that seeks to establish whether each application feature works as per the software requirements
   
   * Form Fields
   
   * Characters limits and checks
   
   * Broken links
   
   * Error messages & notices
   
   * Data Intergrity
   
   ###### Non-Functional Testing
   
   Assesses application properties that aren't critical to functionality but contribute to the end-user experience

**Introduction to BDD**

1. **What is the structure of a Gherkin script?**
   **Given**- Pre-Condition
   **When**- Action
   **Then** - Post-Condition

2. **What is meant by declarative and imperative styles?**
   Imperative Style
* More detail

* Understood by developers

* Maps to technical implementation

Declarative Style

* Less detail

* Understood by wider stakeholders

* Only pertains to information the business cares about
  ![](file:///C:/Users/Glen%20Smith/Desktop/Week%203/Gherkin%20Script.png)
  
  3. **Explain the BDD Process?**

User drvien requirements, translated to developer through Gherkin scripts that are used as the test basis.



**Introduction to Test Automation:**

1. **What is the test automation pyramid ?**
   ![](file:///C:/Users/Glen%20Smith/Desktop/Week%203/Screenshots/07_03_2023/Test_Automation_Pyramid.png)

2. **What is meant by the 70/20/10 split mean in the context of the Test Automation Pyramid?**
   How to focus the testing - Start with unit tests as the cost to fix a failure at a higher level could be costly.

3. **What is Selenium IDE and how can manual testers use it?**
   A record/run tool that a test case developer uses to develop Selenium Test cases

4. **When should you automate test?**
   To avoid repeating tasks over and over to free up time for testers.

5. **What is the purpose of the Agile Test Quadrants**
   They tell you the type of tests and which ones to automate

6. **Which part of the test quadrant do non-functional tests such as performance testing fall under?**
   Technology facing to Critique the Product.

7. **Which part of the test quadrant do unit tests  fall under?**
   Technology Facing to Support the Team.

8. **Which part of the test quadrant do functional tests fall under?**
   Business Facing to Support the Team.

9. **Which part of the test quadrant do UAT and Functional Testing fall under?**
   Business Facing to Critique the Product.
   
   

**Usability Testing:**

1. **What is usability?**
   Can the user perform the tasks they need to.

2. **What is the difference between usability and user experience**?
   **Usabilty Testing**
   Can the user perform the tasks they need to.
   **User Experience**
   The degree to which a component or system can be used by specified users to achieve specified goals in a specified context of use.

3. **What are the benefits of usability testing?**

4. **What are the disbenefits of usability testing?**
   
   

   **Benfits**

   Competitive edge



   **Limitations**

   Better understanding but **expensive, timeconsuming, cannot be automated**



5. **Describe the Usability Testing feedback loop**
   ![](file:///C:/Users/Glen%20Smith/Desktop/Week%203/Screenshots/08_03_2023/Feedback%20Loop.png)

6. **What are the 3 most commonly used usability testing methods?**
   
   * in person usabilty - observed by test conductor
   
   * monitored usability - observed remotely
   
   * unmonitored usability - recorded and observed later

7. **What are the benefits of each of these testing methods?**
   Unmonitored is likely to be more sucessful as people will act more naturally

8. **What should testers look out for in regards to web usability?**
   ![](file:///C:/Users/Glen%20Smith/Desktop/Week%203/Screenshots/08_03_2023/things_to_look.png)

**Accessibility Testing:**

1. **What is meant by accessibility in the context of software development?**
   Testing to determine the ease by which users with disabilities can use a component or system.

2. **What type of things do we look out for during accessibility testing?**
   ![](file:///C:/Users/Glen%20Smith/Desktop/Week%203/Screenshots/08_03_2023/Things_to_look_Access.png)

3. **What are some examples of accessibility standards?**
   
   * BS8878 - based on WCAG WG but British specific
   
   * WCAG WG - Web Content Accessability Guidlines - Working Group (part of www consortium)
   
   * WAI-ARIA - Use to support WCAG WG

4. **What are the 4 principles of WCAG? Explain each one with an example**
   **Perceivable**- Information no matter what is it, should be shared in as many forms as possible.
   **Operable**- UI and Navigation should be operable.
   **Understandable**- Is it clear from the user perspective.
   **Robust**- Good enough quality so that asissted technolgies can use it well.

5. **What are the the 3 levels of WCAG Conformance?**
   Level A, AA and AAA (Low to High)

6. **What is the difference between WCAG, WAI-ARIA and ARIA?**
   WCAG is the guidlines, WAI_ARIA provides the technical specification and ARIA provides specific attributes on HTML that improve the accessability.

7. **Name some accessibility tools and how they are used.**
   Spectrum - used for perspective of eye conditions.
   Wave - Analyse errors, contrast errors and ARIA issues.
   
   

**File Formats:**

1. XML, JSON and YAML.
   
   

**Intro to RESTful APIs and API Test Strategy**

##### **HTTP Protocol**

* **What is HTTP?**
  Hypertext Transfer Protocol

* **What does a request-response style protocol mean?**
  Web browser communicates with web server

* **What does statelessness mean with HTTP?**
  Each request is independant

* **What is found in an HTTP request?**
  Initiation is usually user on web browser

* **What is included within a HTTP response?**
  User requested information

* **What are cookies?**
  small files that websites put on your PC to store info about your preferences

* **What are they (cookies) used for?**
  Indentify a client on the server side
  Website can now index the client in order to collate any requests from a particular client
  Used extensivley for marketing purposes

* **What are the different types of HTTP response status codes?**
  ![](file:///C:/Users/Glen%20Smith/Desktop/Week%203/Screenshots/09_03_2023/HTTP%20Responce.png)

* **What are the HTTP CRUD request methods we can use?**
  ![](file:///C:/Users/Glen%20Smith/Desktop/Week%203/Screenshots/09_03_2023/CRUD_Rest.png)

* **What is the difference between (POST, ) PUT and PATCH?**
  POST for an item that doesn't exist
  PUT for if it exists, it will be updated in its entirety instead
  PATCH for if it exists, certain elements will be updated instead
  DELETE only works if in the database

* **What is DNS?**
  DNS Domain Name Service Address

* **What is the difference between HTTP and HTTPS?**
  HTTPS is encrypted

**REST APIs**

* **What is a REST API?**
  
  Rest - Representational State Transfer is architectural style
  
  API - Communication between two computer programs
* **What are the REST API criteria and what do they mean?**
  
  What makes a REST service
  * Client Server - Structure
  
  * Statelessness - HTTP is inheritantly stateless.
  
  * Cookies not to be used in REST API
  
  * Cacheability
  
  * Layered system - clear elements - doesn't matter about the back end
  
  * Uniform Interface
* **What is a REST endpoint?**
  
  Endpoint of HTTP URL - Noun as opposed to verbs and plural for endpoint i.e. films
* **What's the relevance of plurals in the urls of REST APIs?**
  
  Collection of so best practice
* **What does CRUD describe?**
  
  Create
  
  Read
  
  Update
  
  Delete
* **What is an API key?**
  
  A way to authenticate an API request
* **What is HATEOAS - Hypertext As The Engine Of Application State**
  
  The model of application changes from one state to another by traversing the hyperlinks present in the current set of resource representations model.

**Performance Testing**

Typically automated

Percieved webpage speed

How fast the application loads

Slow to load, move to another

Google ranking factor, uses performance i.e. page load speed to determine ranking
