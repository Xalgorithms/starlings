# Licensing

The material in this repository is licensed under a dual license -
[Apache 2.0](./LICENSE.AL) or [GPL 3.0](./LICENSE.GPL). This means
that you may choose which of the licenses most suits your needs and
requirements and use the software under the terms of the selected
license.


# starlings

Free/Libre/Open Employee Payment Validation

The Starlings Pay Validation System (Starlings) is an experimental attempt to create a 100% free/libre/open source independent online service that eventually, employees of any organization will be able to use to independently and anonymously validate their correct pay, based upon the transparent accessible executable expression of all the applicable rules, with rapid iterative diagnosis and documentation of discrepancies. This open participatory collaborative initiative is designed to supply a scalable audit function that can complement any payroll system.

Employees and others interested in helping out are invited to express compensation rules from employment contracts and collective agreements, using the generic Xalgo specification. The most current version of Xalgo is maintained here: https://github.com/Xalgorithms/xa-arch/blob/master/docs/xalgo.md Shortly there will be available a Xalgo authoring interface built on the JupyterHub platform, and integrated with Github, to support streamlined maintenance of algorithms. A live data fabric that we've called an "Internet of Rules" (IoR) will be able to accept algorithms from any well-structured version management system. The data fabric is described here: https://github.com/Xalgorithms/xa-arch/tree/master/docs  Adaptations are being planned for company payroll modules of popular e-commerce platforms, that would enable employees to anonymously enter data about position, years of service, acting appointment, etc.  The payroll module would fetch and run any applicable rules from the IoR and present the results to the user. Here’s the most generic way we can express this:

_An Internet of Rules is designed to solve the general class of problem in which agent A, interacting with agent B, would obtain one or more externally-managed computational rules from agents C..n, where:
* A and B may or may not know about C..n’s rules, or about any updates to them, but either or both would prefer to be notified about relevant rules when interacting.
* C…n may or may not know about A and B in particular, nor about their particular medium of interaction, but can expect A or B or their medium of interaction to be capable of exchanging data with a generic medium common to A..n.
* A and B would tolerate the risk of exposing limited data through the generic medium in order to learn of applicable rules from C..n._  Ref: https://xalgorithms.org/internet-of-rules/

Suppose:
* A is an employee
* B is an employer
* C is a collective agreement

This is just one context. There are innumerable others. For example, suppose: 
* A is a property owner
* B is a municipal revenue office
* C is the state/provincial tax code

Or suppose: 
* A is your purchasing app. 
* B is their sales app. 
* C..n are entities with relevant trade/commerce rules.

Starlings applies the IoR capabilities to the employee pay integrity validation use case:

1. The Starlings Pay System is being designed and implemented to assist interested parties to express their pay rules in simple “Xalgo” tabular form.
2. Pay rules are placed on a distributed “Internet of Rules” (IoR) data fabric, and are used to process anonymous pay records.
3. Payroll jobs are scheduled (e.g. each 2 weeks) and results are validated against expectations. The rules and records are iteratively refined.
4. Once initial validation is achieved, scope, complexity, testing and reporting can then be scaled via “crowd sourcing” amongst employees and beyond, to accommodate the collective agreements and rules. 
5. Employees will be provided an interface to the payroll module(s) of one or more of popular e-commerce platform, to anonymously enter data about a position, years of service, acting appointment, etc.  
6. The payroll module fetches and runs any applicable rules from the IoR and presents the results to the user.

There has also been some thought put towards how use of Starlings can be used not only to identify errors, but to also support a system that would promptly correct errors that occur in an employee pay system with actual payments. To this end, following is some text that might be useful in hypothetical legislation which we've called the "Federal Employee Payment Integrity Liability and Compensation Act". (This is an invented name -- it does not yet exist.) The concept below could be implemented directly by a conscientious employer which self-insures, or in support of commercially offered employee benefits packages.

...

Independent methods of federal employee pay verification

21 (1) The competent minister shall describe in the public registry a set of functional, and periodic audit and test requirements for any independent, transparent and documented methods of federal employee pay verification to be qualified as reliable source. Qualified methods shall be named and briefly described in Schedule 1 to the Federal Employee Payment Integrity Liability and Compensation Act. 

(2) As a matter of policy and principle, one or more methods of federal employee pay verification should be available to federal employees, to be designed, developed and maintained independently of the federal employee pay system.

(3) When a method of pay verification is listed in Schedule 1, the competent Minister must, within 90 days after the method is included in the public registry, publish in the Canada Gazette the audit and test results which substantiated its inclusion. Verification methods are to be renewed in Schedule 1, or removed from it, based on the audit and test requirements referred to in Section 21(1).

Claims

56 (1) A federal employee may use a method of pay verification listed in Schedule 1 to evaluate the integrity of their pay received in previous weeks, months or years. If the amount of pay received by the employee differs from the amount determined by any of the listed methods by a specified error tolerance margin, which shall be specified from time to time by the Tribunal, the employee may file a claim.

Tribunal responsibility for comparing actual pay with verification pay amounts

(2) When a claim is duly filed by an employee under this Act, the Tribunal is responsible for diagnosing the cause of a difference exceeding the error tolerance margin, between the amount of pay actually issued to the employee through the federal government’s pay system, and the identified Schedule 1 pay verification method. 

Automated and comparison of the actual pay and the verification pay amounts

(3) The Tribunal shall seek optimal claims management efficiency and veracity in diagnosing discrepancies by making use of both automated and semi-automated processing methods to evaluate claims.

Rapid response, iterative refinement

(4) The Tribunal shall determine if a discrepancy reveals a flaw in the method of pay verification listed in Schedule 1, or in the system which generated the payment to the employee, or both. Upon determining the source of a discrepancy the Tribunal shall notify the maintainer of that source through a structured issues management system. The maintainer of shall promptly diagnose the cause, and promptly correct the flaw.

(5) If analysis reveals that the employee has been underpaid by an amount exceeding the Tribunal's established tolerance criterion, the Federal Employee Payment Integrity Liability and Compensation Account shall immediately pay the full liability amount of a shortfall to the employee, and promptly initiate a process to determine what compensation payment should also be provided.

Replenishment of the Employee Payment Integrity Account

(6) Following any payment from the Federal Employee Payment Integrity Liability and Compensation Account, the details of the payment shall be documented with all administrative evidence required under the Financial Administration Act.

(7) On a monthly basis the Tribunal shall issue claims to the Receiver General of Canada for replenishment of the Federal Employee Payment Integrity Liability and Compensation Account

Claims officer

(8) The Tribunal may, in order to process claims expeditiously, establish classes of claims that may be determined by the claims officer without an oral hearing and designate as a claims officer anyone that it considers qualified.

Powers and duties

(9) A panel or claims officer must exercise the powers and perform the duties and functions of the Tribunal with respect to claims that are before that panel or claims officer.
