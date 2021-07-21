# Volha Rasokha

![Profile image](https://avatars.githubusercontent.com/u/37101551?s=100&v=4) 
- *The Republic of Belarus, 220000, Minsk, Prgevalskogo str. 2*
- ***E-mail:** rassoha.olga@tut.by*
- ***Skype:** olga.rassoha87*

## Professional skills
* Experience in RUP, Scrum.
* Manual testing of web-applications (TC creation, Regression Testing, Exploratory/Ad-hoc, Domain/Function Testing, e2e, requirements analysis, Test Result Report writing) 
* Root cause analysis of incoming issues from production
* Creation and performing simple SQL queries. 
* Automated Testing  (analysis results of automation tests, fixing automation bugs, writing BDD test cases in Gherkin and Vividus, Karate)
* Participation in SFT Lab as a mentor with positive feedback from the mentees.

## Working experience/career path
05/2014 – Till now–Software Testing Engineer, EPAM Systems, Belarus, Minsk

### Projects

* **EPAM – SupplyOn (05/2014 – 04/2019)**
>SupplyOn offers its customers unique and customizable tools to support and optimize processes for efficient collaboration with partners and suppliers in a global network. Software solutions help companies optimize procurement, ensure top-quality purchased parts, improve logistics and seamlessly integrate financial processes.

**Responsibilities:** Elaboration and test cases writing for support requests, verification of support requests. Initial review of incoming issues from Production. Review results of automation tests. Creation and performing simple SQL queries. Test result report writing, Test result report review, Project report writing. Production bug analysis. Knowledge transfer from SAM to Release team.

* **EPAM – Sephora USA, Retail & Distribution (04/2019 – Till now)**
>Long-term ongoing engagement with the client resulting in creation of new and evolution of existing Sephora applications.

**Responsibilities:** Leading new Initiatives on the project. AT sanity execution on Production during releases. Automation of test cases, execution, maintenance of existing auto tests.

## Tools
SQL Developer, SoapUI, WinSCP, PuTTY, Hermes, Postman, WireMock, Git, Eclipse, IntelliJ IDEA, Jenkins, Jira, Confluence, TestRail

## Education
* 09/2009 – 06/2015 Belarusian State University of Informatics and Radio electronics
Extramural faculty, Engineer of Telecommunication Systems
* 09/2005 – 06/2008 The Highest State college of Telecommunication,
Technician of Telecommunication Systems

## Certificates/Educational programs
* FTM, Automated Testing Mentoring Program #5 (2018Q2) - [Link to the task performed during the Mentoring Program](https://github.com/VolhaRasokha/ATMMODULE13/tree/master/module13)

* Java Basics #24 - [Link to the task performed during the course](https://github.com/VolhaRasokha/JB24_Lesson12_HW/tree/master/src)

Shot example of the code:
```
package by.epam.jb24.hw.lesson8_task2;

import java.util.ArrayList;
import java.util.List;

public class AppTestDrive {

	public static void main(String[] args) {

		double totalSumOfCheck = 0;

		List<Product> payment = new ArrayList<Product>();
		payment.add(new Product("Apples", 2, 100.0));
		payment.add(new Product("Orange", 1, 50.0));
		payment.add(new Product("Strawberry", 3, 25.5));
		payment.add(new Product("Pineapple", 4, 30));

		System.out.println("Name * Price * Count * Total price");
		for (Product x : payment) {
			System.out.print(x);
			System.out.print("        ");
			System.out.print(x.getTotalPriceOfGoods() + "$");
		}
		System.out.println("");
		System.out.println("------------------------------------------");

		for (Product x : payment) {
			totalSumOfCheck = totalSumOfCheck + x.getTotalPriceOfGoods();
		}

		System.out.println("Total sum of your check is  " + totalSumOfCheck + "$");

	}
}
```

## Foreign languages
**English (B2):** able to read technical literature; carry on business correspondence, understand content of audio and video materials according to the level, able to clarify details with colleagues in English