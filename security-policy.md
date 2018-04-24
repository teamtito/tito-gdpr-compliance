# Tito Security Policy

## General Web Security

All Tito services that store data are hosted by Amazon Web Services, in Ireland.

All applications use SSL for HTTP transport, without support for compromised cryptographic mechanisms.

Outside access to services other than those hosted on port 80 and 443 are disabled. All insecure HTTP requests on port 80 are automatically redirected to HTTPS on port 443.

All passwords are stored in a one-way hash using strong (bcrypt) cryptography and multiple stretches.

## Audit Policy

Tito will commission a detailed penetration test every 2 years, and an interim test every 6 months.

## Breach Policy

In the event of a data breach, upon investigation, Tito will notify all individuals affected by the breach with:

- details of what happened
- personal information compromised
- recommendations of a follow-on action

If there is evidence of a breach, all passwords will be reset, even those not specifically targetted by the breach.