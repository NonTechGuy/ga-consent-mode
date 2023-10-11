A bare bones example of using consent mode in Google Tag Manager

Keep in mind that this example does not use a valid container id (GTM-XXXX). You will need to get a valid container id from Google Tag Manager

### What is GDPR?
The General Data Protection Regulation is a European Union regulation on information privacy in the European Union and the European Economic Area. The GDPR is an important component of EU privacy law and human rights law, in particular Article 8 of the Charter of Fundamental Rights of the European Union. [read more](https://gdpr.eu/what-is-gdpr/)

### Is Google Analytics GDPR compliant?
By default, Google Analytics is not GDPR compliant. When using Google Analytics on your website, you must first obtain the explicit consent of end-users to activate the Google Analytics cookies, as well as describe all personal data processing in your website's privacy policy.

Consent mode lets you communicate your users’ cookie or app identifier consent status to Google. Tags adjust their behavior and respect users’ choices.

### Basic steps in the code
1. Preload Tag Manager consent by default all storage options are set to denied
  - ad_storage, relates to Google Ads
  - analytics_storage, relates to Google Analytics
  - personalization_storage, recommendation provided to the user based on previous site visits
  - functionality_storage, could include the language the user speaks
  - security_storage, anything relating to authorisation or authentication 
2. If the user has already made selections these are previous selected are loaded from local storage
3. Consent is set based on the selection that the user made and updated from the default denied to the users selection.
