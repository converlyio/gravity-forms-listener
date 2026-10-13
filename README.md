# Gravity Forms Listener

Fires a dataLayer event each time a Gravity Forms submission succeeds, so your conversion tags count real submissions only. Works with AJAX forms and redirect confirmations.

## Setup

Follow the [setup guide](https://converly.io/gtm-templates/gravity-forms).

Fire this tag on All Pages, then trigger your conversion tags on the custom event gravity_form_submitted.

## Event

The listener sends gravity_form_submitted. Use CE - Gravity Forms Submitted as the custom event trigger.

## Script

The template loads https://gtm-templates.converly.io/gravity-forms-listener.js.

## Notes

Sends one gravity_form_submitted event per successful Gravity Forms submission, with the form ID. It reads no personal data. To catch submissions that end in a redirect, it switches each form to Gravity Forms' own AJAX submission method. Full setup guide at https://converly.io/gtm-templates/gravity-forms

## License

Apache License 2.0.
