# NatureLandApplication

------------------------------------Setup Steps---------------------------------------------
Step 1 —
------Prerequisites---
---Install these first:
          * Java JDK (8 or higher)
          * Eclipse IDE (with Maven support)
          * Maven (usually bundled with Eclipse)
 Step 2 —         
*Verify Java & Maven
*java -version   # Expected: openjdk 25 or higher
*mvn -version    # Expected: Apache Maven 3.9.14

Step 3 — 
      Install Dependencies
       downloads all dependencies declared in pom.xml to your local .m2 repository.
Step 4 — 
      Configure the Application
      Edit src/test/resources/config/config.properties:
      base.url=https://dev.outlet.natureland.hipster-virtual.com/login
      browser=chrome          # Options: chrome | firefox | edge
      headless=false          # Set true for CI/CD pipelines
      implicit.wait=10        # Seconds
      explicit.wait=20        # Seconds

/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////      

------------------------------------------- How to run Testes----------------------------------------------------------

 * Download all the dependencies and declare it in POM
 * Create Test Runner class
 * Cucumber Feature file
 * Create Step defination file

   Right-click Runner - Right-click TestRunner.java → Run As → TestNG Test
   Feature file - Right-click .feature file → Run As → Cucumber Feature
   Maven CLI - mvn test in terminal

   //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

   -------------------------------------------Tools Version Used--------------------------------------------------------

   Selenium - 4.41.0 v
   Java- 26 v
   Maven - 3.9.14 v
   Cucumber- 7.34.3
   TestNG- 7.12.0

   
    
