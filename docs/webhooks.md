# Managing Webhooks

## Synchronous vs Asynchronous
Weferral allows for "synchronous" webhooks. Using synchronous webhooks, when a client makes a request which triggers a webhook, the process will wait until the endpoint responds and attach whatever data the client responded with to the payload the client receives.

## Participant-Invitation
#### Description
This hook is called when a user is invited to a campaign in order to sign-up as a participant.

## New-Participant
#### Description
This hook is called when a user signed up as an affiliate or being manually added as an affiliate or participant.

## Updated-Participant
#### Description
This hook is called when a participant updates their profile or details.

## Participant-Approved
#### Description
This hook is called when a participant is automatically or manually approved for a campaign.

## Participant-Disapproved
#### Description
This hook is called when a participant is disapproved for a campaign.

## New-Customer
#### Description
This hook is called when a customer is created through an affiliate or participant.

## New-Commission
#### Description
This hook is called when a commission is created. This can be as a result of a conversion, recurring commission or comission added through an API.