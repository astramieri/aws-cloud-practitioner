# IAM Protection

The are two defence mechanims to protect users and groups:

- Password Policy
- Multi Factor Authentication (MFA)

## Password Policy

The stronger the password you use, the more security for your accounts. 

A password policy is really helpful against brute force attacks on accounts.

In AWS you can setup a password policy:
- set a minimum password length
- require specific character types
    - uppercase letter
    - lowercase letter
    - numbers
    - non-alphanumeric characters
- allow all IAM user to change their own password
- require users to change their password after some time (password expiration)
- prevent password reuse

## Multi Factor Authentication (MFA)

MFA = password *you know* + security device *you own*

The main benefit of MFA is that even if a password is stolen or hacked, the account will not be compromised.

MFA device options:
- **virtual MFA device**: supports for multiple tokens on a single device
    - Google Authenticator (phone only)
    - Authy (multi-device)
- **Universal 2nd Factor (U2F) Security Key**: supports for multiple root and IAM users using a single security key
    - YubiKey by Yubico (3rd party) phyisical device
- **Hardware Key Fob MFA Device**
    - Provided by Gemalto (3rd party)
- **Hardware Key Fob MFA Device for AWS GovCloud (US)**
    - Provided by SurePassID (3rd party)