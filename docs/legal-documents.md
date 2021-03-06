# Legal Documents and Security

There are a number of legal documents that every exposure notification app will need to have prepared for launch. Please consult with your legal team to have them review any documents you choose to release with your app. LFPH is not providing legal advice here, but are just providing pointers to various documents that are available for reference. 

## Privacy
* **Canada**
    * [Privacy notice](https://www.canada.ca/en/public-health/services/diseases/coronavirus-disease-covid-19/covid-alert/privacy-policy.html)
    * [Privacy assessment](https://github.com/cds-snc/covid-alert-documentation/blob/main/COVIDAlertPrivacyAssessment.md) by Health Canada
    * [Privacy review](https://priv.gc.ca/en/privacy-topics/health-genetic-and-other-body-information/health-emergencies/rev_covid-app/) from the Office of the Privacy Commissioner
* **Ireland**
    * [General privacy and data terms, website](https://covidtracker.gov.ie/privacy-and-data/) 
* **Delaware**
    * [Data and Privacy Policy](https://coronavirus.delaware.gov/wp-content/uploads/sites/177/2020/09/COVID-Alert-Terms-082720-.pdf)
* **Pennsylvania**
    * [Data and Privacy Summary](https://www.health.pa.gov/topics/disease/coronavirus/Pages/COVID-Alert-Data.aspx)
    * [Data and Privacy Policy](https://www.health.pa.gov/topics/Documents/Diseases%20and%20Conditions/COVID%20Alert%20App_Data%20and%20Privacy.pdf)
    * [General privacy and data terms, website](https://covidtracker.gov.ie/privacy-and-data/)
* **District of Columbia**
    * [Privacy Policy](https://coronavirus.dc.gov/dccan/privacy)
* **Colorado**
    * [EN Privacy Policy](https://covid19.colorado.gov/exposure-notifications/privacy-policy)
* **New York**
    * [COVID Alert NY Privacy](https://coronavirus.health.ny.gov/covidalert-privacy)
* **UK**
    * [NHS COVID-19 app: privacy notice](https://www.gov.uk/government/publications/nhs-covid-19-app-privacy-information/nhs-test-and-trace-app-early-adopter-trial-august-2020-privacy-notice)
    * [An easy read version of the privacy notice](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/920962/NHS_COVID-19_app_privacy_information__easy_read_.pdf)
* **Academic Research**
    * [Contact Tracing App Privacy: What Data Is Shared By Europe’s GAEN Contact Tracing Apps](https://www.scss.tcd.ie/Doug.Leith/pubs/contact_tracing_app_traffic.pdf)

## Data Use
* **Ireland**
    * [Data protection information notice COVID tracker app](https://covidtracker.gov.ie/privacy-and-data/data-protection/); [GitHub version](https://github.com/HSEIreland/covidtracker-documentation/blob/master/documentation/privacy/DPINV1.1.mdown)
    * [Data protection impact assessment](https://github.com/HSEIreland/covidtracker-documentation/blob/master/documentation/privacy/Data%20Protection%20Impact%20Assessment%20for%20the%20COVID%20Tracker%20App%20-%2026.06.2020.pdf)
    * [Data protection impact assessment review](https://github.com/HSEIreland/covidtracker-documentation/blob/master/documentation/privacy/DPC%20review%20of%20CTI%20App%20DPIA%20June%202020.pdf)
* **UK**
    * [NHS COVID-19 app: data protection impact assessment](https://www.gov.uk/government/publications/nhs-covid-19-app-privacy-information/the-nhs-test-and-trace-app-early-adopter-trial-august-2020-data-protection-impact-assessment)

## Accessibility
* **Canada**
    * [Accessibility statement](https://www.canada.ca/en/public-health/services/diseases/coronavirus-disease-covid-19/covid-alert/accessibility-statement.html)
    * [Accessibility report](https://github.com/cds-snc/covid-alert-documentation/blob/main/AccessibilityReport.md)

## Other Terms and Conditions
* **Canada**
    * [Vulnerability disclosure policy](https://github.com/cds-snc/covid-alert-documentation/blob/main/VulnerabilityDisclosurePolicy.md)
* **Alabama**
    * [General legal disclaimers and privacy FAQ](https://github.com/lfph/implementers-forum/blob/master/docs/resources/guidesafe_legal.md) (Please note that Alabama's privacy policy links directly to the app sponsor's, [the University of Alabama](https://www.ua.edu/privacy), and is not EN-specific.)
    
## FAQ
* **Delaware**
   * [FAQ](https://coronavirus.delaware.gov/covidalert/faqs/)
* **Pennsylvania**
   * [FAQ](https://www.health.pa.gov/topics/disease/coronavirus/Pages/COVID-Alert-FAQs.aspx)
* **District of Columbia**
   * [FAQ](https://coronavirus.dc.gov/dccan/faq)
* **Colorado**
   * [FAQ](https://covid19.colorado.gov/Exposure-notifications)

## Security
* [**Balancing Privacy and Security: Google Apple Contact Tracing**](https://duo.com/labs/research/balancing-privacy-and-security-google-apple-contact-tracing) - Duo, June 25, 2020

## Minors

A US state provided the following information about expanding their app to include people ages 13-18: 

> Essentially, we have users on-board after downloading the app. After several legal discussions, we landed on just adding a notice on the on-boarding screen indicating that parents/guardians should approve the use for ages 13-17. Additionally, if we learn that we took information from anyone under 18 -- which is only 2 ways we could potentially collect 1) the de-identifiable aggregate stats via symptom check-in and 2) when someone requests a call-back number after they received an exposure alert through the app and we conduct contact tracing. On #2, we usually ask if they are under 18. If they are then we ask for a parent/guardian. Without consent, it is very unlikely we will ever have collected any information. We then updated our data and privacy policy and the age group during app downloads.

> In our Current workflow, Case Investigators will not continue case investigation with a minor in the absence of a parent/legal guardian. For minors, we send 6-digit codes to the phone that have the app installed. Plus, we also have the option to verbally provide the code over the phone. However, this is all done in the presence of the parent/legal guardian.
