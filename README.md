# Syncing and sending HTML email templates with Pipedream workflows

You can send emails in Pipedream workflows using your Email Service Provider (ESP) of choice, such as MailChimp, SendGrid, Postmark, etc.

However, managing the HTML templates for emails can be challenging if you're managing the HTML templates in Node.js or Python code steps in workflows.

Instead, you can leverage the flexibility of your IDE to code the HTML templates, and use a Pipedream workflow to synchronize the HTML files to your **File Store**. Then you can set up workflows to read the HTML templates from the **File Store** and pass them to the ESP for handling.

## Getting Started

The `html-templates` directory contains email HTML templates. You can view the examples or simple add your own.

Then copy this workflow to your Pipedream account: https://pipedream.com/new?h=tch_O6LfRN

This workflow will sync the files within `html-templates` to the **File Store**.
