> [!IMPORTANT]
> The [Qlik Cloud Monitoring Apps](https://github.com/qlik-oss/qlik-cloud-monitoring-apps) project is _community supported_.
> Qlik does not support these apps. See below for additional information
> on how to raise issues on this repository to ask for help.

# Qlik Cloud Access Evaluator

> **Note**
> This application provides access information for users based on their assigned roles. It does this using a snapshot of role
> permissions correct at time of release, and does not consider user entitlements as a factor when evaluating what the user can
> access. Do not use this tool for audit or regulatory needs.

The Access Evaluator is a Qlik Sense application built for Qlik Cloud, which helps
you to analyze user roles, access, and permissions across a tenant.

![Sheets in the Access Evaluator](/images/readme_sheets.png)

It provides information such as:

* User and group access to spaces
* User, group, and share access to apps
* User roles and associated role permissions
* Group assignments to roles

It does not consider the entitlement assigned to the user (for example, full/basic user, or professional/analyzer user), nor the
state of that entitlement, which may restrict the user from being able to access content that their roles would otherwise provide
access to.

## Installing / Updating

These applications can be installed via an interactive Qlik Application Automation [installer](https://community.qlik.com/t5/Official-Support-Articles/Qlik-Cloud-Monitoring-Apps-Workflow-Guide/ta-p/2134140) or [manually](/../../releases) using the PDF guide.

## Subscription Compatibility

Some monitoring apps are designed for specific Qlik Cloud subscription types. Refer to the compatibility matrix within the [Qlik Cloud Monitoring Apps](https://github.com/qlik-oss/qlik-cloud-monitoring-apps?tab=readme-ov-file#applications) repository.

## Support policy

This app is provided as-is and is not supported by Qlik. Over time, the APIs and
metrics used by the app may change, so it is advised to monitor this repository
for updates, and to update the app promptly when new versions are available.

If you have issues while using this app, support is provided on a best-efforts
basis by contributors to this project.

If you have an issue:

* Review the FAQ section in this readme to see if your issue is a common one
* Review open and closed [issues](/../../issues)
* Open a [new issue](/../../issues/new), following the issue template

If you are able to resolve the issue, then close your issue with the resolution,
and if you feel inclined, open a PR with your proposed changes so that we can
consider including the improvement in the next release of the app.

Thank you for your support!
