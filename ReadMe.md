# Healthcare Eligibility Accelerator

This rule application demonstrates the basic strategies and patters for determining healthcare and Medicaid eligibility. It contains the following capabilities.
* The Healthcare Accelerator application provides an annotated schema based on the Health Insurance Marketplace Application for Health Coverage & Help Paying Costs (Form OMB No. 0938-1191). 
* This application provides an example of modeling the business process integral for a Medicaid eligibility determination.
* Performs basic application validation.
* Checks verifications including citizenship, alienage, SSN, and income verification.
* Calculates household size using both MAGI and relationship-based models.
* Calculates countable income and deductions based on the household calculation used.
* Determines program eligibility for pregnancy-related services, child health program and the Medicaid expansion populations.

Three scenarios with sample JSON files are provided. This will need to be tested in the context of the Application entity and can be tested in irVerify. Use the "Apply Rules" button to run.  The three scenarios for testing incude the following:

* A single pregnant applicant who is eligible for services;
* A family needing additional verification; and 
* Housheholding calculations by relationship.

### NOTE 
Medicaid rules vary by state and this rule application does not cover every variance.
