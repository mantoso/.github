# Security Policies and Procedures

We take all security seriously. We acknowledge that every line of code we write may potentially contain a security risk. We are trying to deal with it responsibly and provide patches as quickly as possible.

We appreciate your effort and responsible disclosure and will make every effort to acknowledge your contributions.

This document outlines security procedures and general policies for the project.

<!-- TOC -->
* [Security Policies and Procedures](#security-policies-and-procedures)
  * [Reporting Security Problems](#reporting-security-problems)
  * [Disclosure Policy](#disclosure-policy)
  * [Vulnerability Management Plans](#vulnerability-management-plans)
    * [Critical Updates And Security Notices](#critical-updates-and-security-notices)
  * [Comments on this Policy](#comments-on-this-policy)
<!-- TOC -->

## Reporting Security Problems

DO NOT CREATE AN ISSUE to report a security problem. Instead, email us direct: [security@mantoso.com](mailto:security@mantoso.com).

To ensure a timely response to your report, ensure the entirety of the report is contained within the email body and not solely behind a web link or an attachment.

A maintainer will acknowledge your email within 24 hours, and will send a more detailed response within 48 hours indicating the next steps in handling your report. After the initial reply to your report, the security team will endeavor to keep you informed of the progress towards a fix and full announcement and may ask for additional information or guidance.

Report security bugs in third-party modules to the person or team maintaining the module.

## Disclosure Policy

When the security team receives a security bug report, they will assign it to a primary handler. This person will coordinate the fix and release process, involving the following steps:

  * Confirm the problem and determine the affected versions.
  * Audit code to find any potential similar problems.
  * Prepare fixes for all releases still under maintenance. These fixes will be released as fast as possible to npm.

## Vulnerability Management Plans

### Critical Updates And Security Notices

We learn about critical software updates and security threats from these sources.

- GitHub Security Alerts
- [Dependabot](https://dependabot.com/) Dependency Updates

## Comments on this Policy

If you have suggestions on how this process could be improved, please submit a pull request.
