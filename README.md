# mersys.io Testing

![Static Badge](https://img.shields.io/badge/test-%20pass%20-s?style=for-the-badge&labelColor=darksilver&color=darkgreen)
[![MIT License](https://img.shields.io/badge/licence-%20MIT%20-s?style=for-the-badge&labelColor=darksilver&color=darkgreen)](https://choosealicense.com/licenses/mit/)

This project is created to improve the user experience of mersys.io, an educational application.

Domain : [mersys.io](https://www.mersys.io/)<br>
Domain : [test.mersys.io](https://test.mersys.io//)

While Starting
---------------

### The simplest method :

```gherkin
Feature: While Starting

  Background:
    Given Follow the path
      | File > New > Project From Version Control |
    When  Copy URL and paste
      | https://github.com/Pazzoide/mersys.io_Testing.git |

  Scenario: Open this project at your IDE
    Then Select JDK version for project
      | jdk1.8 |
    And To load the POM with Maven, click on
      | pom.xml > Maven > Reload Project |
    And To run all tests, click on
      | Runners > Runner Classes |

```

Dependencies
---------------

<div align="right">
<body>
  <table style="width: 100%; table-layout: fixed; border-collapse: collapse; height: 100%;">
    <thead>
      <tr>
        <th style="width: 33.33%;">
          <img src="https://img.shields.io/badge/Selenium-%20v4.11.0%20-s?style=for-the-badge&logo=Selenium&labelColor=darksilver&color=darkgreen" alt="TestNG Badge">
        </th>
<th style="width: 33.33%;">
          <img src="https://img.shields.io/badge/Cucumber-%20v7.9.0%20-s?style=for-the-badge&logo=Cucumber&labelColor=darksilver&color=darkgreen" alt="TestNG Badge">
        </th>
<th style="width: 33.33%;">
          <img src="https://img.shields.io/badge/slf4j-%20v1.8.0--Beta2%20-s?style=for-the-badge&logo=ng&labelColor=darksilver&color=darkgreen" alt="TestNG Badge">
        </th>
      </tr>
     <tr>
        <td style="width: 33.33%;">
           Selenium is a powerful automation framework used for automating and testing web browsers..     
        </td><td style="width: 33.33%;">
           Cucumber is a tool that supports BDD and provides collaborative test automation.     
        </td><td style="width: 33.33%;">
           slf4j (Simple Logging Facade for Java) provides a simple and efficient logging facade for Java applications.     
        </td>
      </tr>
      </thead>
      <tbody>
         <tr>

<th style="width: 33.33%;">
          <img src="https://img.shields.io/badge/Apache%20-%20v3.12.0%20-s?style=for-the-badge&logo=apache&labelColor=darksilver&color=darkgreen" alt="TestNG Badge">
        </th>

<th style="width: 33.33%;">
          <img src="https://img.shields.io/badge/Grasshopper%20-%20v1.9.2%20-s?style=for-the-badge&labelColor=darksilver&color=darkgreen" alt="TestNG Badge">
        </th>

<th style="width: 33.33%;">
          <img src="https://img.shields.io/badge/TestNG-%20v6.14.3%20-s?style=for-the-badge&logo=ng&labelColor=darksilver&color=darkgreen" alt="TestNG Badge">
        </th>
      </tr>
<tr>
        <td style="width: 33.33%;">
          Apache Commons is a library that offers file and data processing capabilities. It is part of the Apache Commons project.     
        </td>
 <td style="width: 33.33%;">
          Grasshopper is a tool used for generating HTML and PDF reports, aiding in the effective visualization of test results.     
        </td>
 <td style="width: 33.33%;">
          TestNG is a next-generation testing tool that provides a comprehensive testing framework.    
        </td>
</tr>
      </tbody>
  </table>
</body>
</div>
<div align="right">
<body>
  <table style="width: 100%; table-layout: fixed; border-collapse: collapse; height: 100%;">
    <thead>
      <tr>
        <th style="width: 33.33%;">
          <img src="https://img.shields.io/badge/javafaker-%20v0.15%20-s?style=for-the-badge&labelColor=darksilver&color=darkgreen" alt="TestNG Badge">
        </th>
      </tr>
      </thead>
      <tbody>
         <tr>
        <td style="width: 33.33%;">
           JavaFaker is a Java library that provides<br> realistic fake data for use in project<br> development and presentations.     
        </td>
      </tr>
      </tbody>
  </table>
</body>
</div>

### TEAM

---
<div style="display: flex;">
  <div style="flex: 1;">
   <ul style="list-style-type: disc;" >
     <li><h4>T.Lead <| Burhan SENGUL <br /><strong> <a href="mailto:burhseng@gmail.com"> <img src="https://www.freepnglogos.com/uploads/logo-gmail-png/logo-gmail-png-gmail-icon-download-png-and-vector-1.png" alt="E-Posta" width="31" height="25" /></a></strong></h4></li>
     <li><h4>Tester <| D. Fatihhan KARAHANLI <br /><strong> <a href="mailto:fatihhan.karahanli@gmail.com"> <img src="https://www.freepnglogos.com/uploads/logo-gmail-png/logo-gmail-png-gmail-icon-download-png-and-vector-1.png" alt="E-Posta" width="31" height="25" /></a></strong></h4></li>
     <li><h4>Tester <| Şeyma ASKERZADE <br /><strong> <a href="mailto:4seyma@gmail.com"> <img src="https://www.freepnglogos.com/uploads/logo-gmail-png/logo-gmail-png-gmail-icon-download-png-and-vector-1.png" alt="E-Posta" width="31" height="25" /></a>&nbsp;</strong></h4></li> 
     <li><h4><strong>Tester <| Ramazan INCE </strong><br /><strong><a href="mailto:inceliramazan80@gmail.com"><img src="https://www.freepnglogos.com/uploads/logo-gmail-png/logo-gmail-png-gmail-icon-download-png-and-vector-1.png" alt="E-Posta" width="31" height="25" /></a>&nbsp;</strong></h4></li>
     <li><h4>Tester <| Zafer CANSIZ <br /><strong><a href="mailto:zfrcnsz1@gmail.com"><img src="https://www.freepnglogos.com/uploads/logo-gmail-png/logo-gmail-png-gmail-icon-download-png-and-vector-1.png" alt="E-Posta" width="31" height="25" /></a>&nbsp;</strong></h4></li>
</ul>
  </div>
  <div style="flex: 1; text-align: left;">
    <img alt="gif" height="140" src="https://media.tenor.com/GfSX-u7VGM4AAAAC/coding.gif" width="249"/>
  </div>
</div>

### TODO
* It's crucial to stick to the specified dependencies versions to maintain compatibility and reliability.
  Using different versions can jeopardize project stability and compatibility.
  In case you encounter problems with alternative versions, please note that these
  issues cannot be attributed to the project.<br>
  <br>
* If you experience issues or compatibility problems with a specific version of our project or
  if you are tempted to use different versions, we encourage you to provide feedback. We will
  do our best to assist you.
### LICENSE
This project is an open-source software licensed under the terms of the[ MIT license](https://opensource.org/license/mit/).
