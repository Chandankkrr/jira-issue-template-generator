# jira-issue-template-generator

Changelog information for Jira Issue Template Generator Google Chrome Extension.

## Version 1.0.10 - 12 July 2020 🎉

- Ability to add custom domains 🔥🔥🔥
- Use desktop version of Jira that has a custom domain? You can now enable the extension to work on your custom domain
- Add your custom domain to the "Allowed domains" list via the options page
- Add in the host of the site url (e.g. jira.mycompany.com without http or https or ending forward slash (/)) into "Allowed domains" input and hit save

## Version 1.0.9 - 05 June 2020 🎉

- Improvements in speed 🔥
- The extension has been updated to use `MutationObserver` api to detect when the Jira issue dialog is visible in the `DOM` and then immediately apply a template 
- Other minor improvements

## Version 1.0.8 - 06 January 2020 🎉

- Enabled the template for desktop version of Jira that has custom url matching `https://jira-software/*` and `http://jira-software/*`
- This is a temporary workaround until a viable solution is developed


## Version 1.0.7 - 12 November 2019

### Jira Service Desk Classic project support

- The template now supports Jira Service Desk Classic project

## Version 1.0.6 - 11 November 2019

### Ability to apply template on Close issue forms

- The template generator works on Jira Close issue screen. The add template toolbar now appears on Close issue, Reopen Issue and Resolve issue forms. 
  
- Other minor improvements
