PROJECT TITLE: 
------------------
Find Travel Insurance Plan for Students

PROBLEM STATEMENT:
-------------------
1. Find travel insurance plan for students, for 2 people (Age 22 & 21) & any European country, fill further dummy details & display three lowest international  travel insurance plan with amount and insurance provider company
2. Get a Car Insurance quote, proceed without  car number, keep filling details, give invalid email or phone number & capture the error message
3.  Retrieve all Health Insurance menu items and store in a List; Display the same
(Suggested Site: policybazaar.com however you are free to use any other legitimate site)

KEY AUTOMATION SCOPE:
-----------------------
Handling alerts, search option
Validation of date controls
Filling simple form, Capture warning message
Extract menu items & store in collections
Navigating back to home page

DEPENDENCIES:
--------------
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 https://maven.apache.org/xsd/maven-4.0.0.xsd">
  <modelVersion>4.0.0</modelVersion>
  <groupId>Hackathon_TravelInsurance</groupId>
  <artifactId>Hackathon_TravelInsurance</artifactId>
  <version>0.0.1-SNAPSHOT</version>

<dependencies>

	<!-- https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-java -->
	<dependency>
	    <groupId>org.seleniumhq.selenium</groupId>
	    <artifactId>selenium-java</artifactId>
	    <version>4.18.1</version>
	</dependency>
	
	<!-- https://mvnrepository.com/artifact/io.github.bonigarcia/webdrivermanager -->
	<dependency>
	    <groupId>io.github.bonigarcia</groupId>
	    <artifactId>webdrivermanager</artifactId>
	    <version>5.8.0</version>
	</dependency>
	
	<!-- https://mvnrepository.com/artifact/org.apache.poi/poi -->
	<dependency>
	    <groupId>org.apache.poi</groupId>
	    <artifactId>poi</artifactId>
	    <version>5.2.5</version>
	</dependency>
	<!-- https://mvnrepository.com/artifact/org.apache.poi/poi-ooxml -->
	<dependency>
	    <groupId>org.apache.poi</groupId>
	    <artifactId>poi-ooxml</artifactId>
	    <version>5.2.5</version>
	</dependency>
	
	<!-- https://mvnrepository.com/artifact/commons-io/commons-io -->
	<dependency>
	    <groupId>commons-io</groupId>
	    <artifactId>commons-io</artifactId>
	    <version>2.16.0</version>
	</dependency>
	
	<!-- https://mvnrepository.com/artifact/org.apache.commons/commons-lang3 -->
	<dependency>
	    <groupId>org.apache.commons</groupId>
	    <artifactId>commons-lang3</artifactId>
	    <version>3.14.0</version>
	</dependency>
	
	<!-- https://mvnrepository.com/artifact/org.apache.logging.log4j/log4j-api -->
	<dependency>
	    <groupId>org.apache.logging.log4j</groupId>
	    <artifactId>log4j-api</artifactId>
	    <version>3.0.0-beta2</version>
	</dependency>
	
	<!-- https://mvnrepository.com/artifact/org.testng/testng -->
	<dependency>
	    <groupId>org.testng</groupId>
	    <artifactId>testng</artifactId>
	    <version>7.9.0</version>
	    <scope>test</scope>
	</dependency>
	
	<!-- https://mvnrepository.com/artifact/com.aventstack/extentreports -->
	<dependency>
	    <groupId>com.aventstack</groupId>
	    <artifactId>extentreports</artifactId>
	    <version>5.1.1</version>
	</dependency>
	<!-- https://mvnrepository.com/artifact/io.cucumber/cucumber-java -->
	<dependency>
	    <groupId>io.cucumber</groupId>
	    <artifactId>cucumber-java</artifactId>
	    <version>7.16.1</version>
	</dependency>
	<!-- https://mvnrepository.com/artifact/io.cucumber/cucumber-testng -->
	<dependency>
	    <groupId>io.cucumber</groupId>
	    <artifactId>cucumber-testng</artifactId>
	    <version>7.16.1</version>
	</dependency>
	<!-- https://mvnrepository.com/artifact/io.cucumber/cucumber-junit -->
	<dependency>
	    <groupId>io.cucumber</groupId>
	    <artifactId>cucumber-junit</artifactId>
	    <version>7.16.1</version>
	    <scope>test</scope>
	</dependency>
	<!-- https://mvnrepository.com/artifact/tech.grasshopper/extentreports-cucumber7-adapter -->
	<dependency>
	    <groupId>tech.grasshopper</groupId>
	    <artifactId>extentreports-cucumber7-adapter</artifactId>
	    <version>1.14.0</version>
	</dependency>

</dependencies>
</project>


OUTPUT ON CONSOLE:
---------------------
@Smoke @Regression
Scenario: Find travel insurance plan for students   # Features/Feature1_TravelInsurance.feature:4
  Given User navigates to the travel insurance page # StepDefinitions.TC_001_TravelInsurance.user_navigates_to_the_travel_insurance_page()

    Embedding Find travel insurance plan for students [image/png 279390 bytes]


  When User enters destination details              # StepDefinitions.TC_001_TravelInsurance.user_enters_destination_details()

    Embedding Find travel insurance plan for students [image/png 203207 bytes]

  And User enters trip date details                 # StepDefinitions.TC_001_TravelInsurance.user_enters_trip_date_details()

    Embedding Find travel insurance plan for students [image/png 128622 bytes]

  And User enters travellers details                # StepDefinitions.TC_001_TravelInsurance.user_enters_travellers_details()

    Embedding Find travel insurance plan for students [image/png 161068 bytes]

  And User enters medical history details           # StepDefinitions.TC_001_TravelInsurance.user_enters_medical_history_details()

    Embedding Find travel insurance plan for students [image/png 332363 bytes]

  And User enters contact details                   # StepDefinitions.TC_001_TravelInsurance.user_enters_contact_details()

    Embedding Find travel insurance plan for students [image/png 234644 bytes]

[Niva Bupa (formerly known as Max Bupa), Reliance, Bajaj Allianz]
[₹1,543, ₹1,686, ₹1,920]
  Then User gets the student insurance plan details # StepDefinitions.TC_001_TravelInsurance.user_gets_the_student_insurance_plan_details()

    Embedding Find travel insurance plan for students [image/png 220256 bytes]

  And User navigates to policy bazaar homepage      # StepDefinitions.TC_001_TravelInsurance.user_navigates_to_policy_bazaar_homepage()

    Embedding Find travel insurance plan for students [image/png 280202 bytes]


@Smoke @Regression
Scenario: Getting a Car Insurance quote                         # Features/Feature2_CarInsurance.feature:4
  Given User navigates to the car insurance page                # StepDefinitions.TC_002_CarInsurance.user_navigates_to_the_car_insurance_page()

    Embedding Getting a Car Insurance quote [image/png 224571 bytes]

  When User selects city and rto                                # StepDefinitions.TC_002_CarInsurance.user_selects_city_and_rto()

    Embedding Getting a Car Insurance quote [image/png 273859 bytes]

  And User selects car details                                  # StepDefinitions.TC_002_CarInsurance.user_selects_car_details()

    Embedding Getting a Car Insurance quote [image/png 195512 bytes]

Please enter valid email address
  Then User fills incorrect user details and gets error message # StepDefinitions.TC_002_CarInsurance.user_fills_incorrect_user_details_and_gets_error_message()

    Embedding Getting a Car Insurance quote [image/png 207527 bytes]

  And User navigates to the policy bazaar homepage              # StepDefinitions.TC_002_CarInsurance.user_navigates_to_the_policy_bazaar_homepage()

    Embedding Getting a Car Insurance quote [image/png 280200 bytes]


@Smoke @Regression
Scenario: Retrieving all Health Insurance menu items # Features/Feature3_HealthInsurance.feature:4
  Given User clicks on health insurance menu         # StepDefinitions.TC_003_HealthInsurance.user_clicks_on_health_insurance_menu()

    Embedding Retrieving all Health Insurance menu items [image/png 159915 bytes]

Family Health Insurance
Senior Citizen Health Insurance
Health Insurance for Parents
Best Health Insurance Plans
Maternity Insurance
Health Insurance Portability
Mediclaim Policy
Critical Illness Insurance
Health Insurance Calculator
Health Insurance Companies
Health Insurance for NRIs
Health Insurance Claim
  Then User displays all health insurance plans      # StepDefinitions.TC_003_HealthInsurance.user_displays_all_health_insurance_plans()

    Embedding Retrieving all Health Insurance menu items [image/png 280202 bytes]

┌──────────────────────────────────────────────────────────────────────────┐
│ View your Cucumber Report at:                                            │
│ https://reports.cucumber.io/reports/60274454-ec24-4b0b-9930-0be8802cb8af │
│                                                                          │
│ This report will self-destruct in 24h.                                   │
│ Keep reports forever: https://reports.cucumber.io/profile                │
└──────────────────────────────────────────────────────────────────────────┘
===============================================
Suite
Total tests run: 3, Passes: 3, Failures: 0, Skips: 0
===============================================
