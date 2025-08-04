## Bank Feed Account Expiry Reminder Flow

Production
<a href="https://githubsfdeploy.herokuapp.com?owner=FinDockLabs&repo=bank-feed-expry-reminder&ref=main">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png">
</a>


Sandbox
<a href="https://githubsfdeploy.herokuapp.com?owner=FinDockLabs&repo=bank-feed-expry-reminder&ref=main">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png">
</a>


A simple scheduled Flow template that sends emails when a Bank Feed account authorization is expiring soon (within two weeks) or has expired, meaning no transactions can be imported.


## Requirements

- The optional Bank Feed feature needs to be activated to use this flow.
- By default, the flow uses the Support & product contact email(s) defined in the FinDock Setup on the Contact settings page. You an override this by manually defining email receiver(s) in the flow configuration.


## Installation

Simply install and activate the flow (Scheduled Flow - Bank Feed Accounts Expiration Date Reminder). The flow includes Start Date and Frequency options.  Before activating the flow, be sure to the Contacts settings are correct in FinDock Setup and/or manually define email receiver(s) in the flow. Then, activate the flow as normal from the Flow page in Salesforce Setup.

To deploy the flow to your Salesforce environment, you can:
- use `sfdx`.
- press the "Deploy to Salesforce" button at the top of this README and then press "Login to Salesforce" in the top right of your screen.
- any other deployment method you prefer.

## Contributing

When contributing to this repository, please first discuss the change you wish to make via an issue or any other method with FinDock before making a change.

## Support

FinDock Labs is a non-supported group in FinDock that releases applications. Despite the name, assistance for any of these applications is not provided by FinDock Support because they are not officially supported features. For a list of these apps, visit the FinDock Labs account on Github. 

## License

This project is licensed under the MIT License - see the [LICENSE](/LICENSE) file for details# bank-feed-expiry-date-reminder
