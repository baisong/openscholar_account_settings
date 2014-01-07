## OpenScholar Account Settings

Contains a snapshot of default email texts from `user` and `vsite` modules in OpenScholar 7.x-3.9.3

### Frequent templates

* Site created (notify admin)
<br/>**Trigger**: whenever a site is created.
<br/>**Summary**: Reports new site details to configurable sitewide administrator email

* Site created (notify author, no reset required)
<br/>**Trigger**: whenever a site is created by an existing user
<br/>**Summary**: Confirms site creation with link to log in on new site

* Site created (notify author, reset required)
<br/>**Trigger**: whenever a site is created by a new user (or created on behalf of new user)
<br/>**Summary**: Confirms site creation with link to log in on new site and password instructions.

* Password recovery
<br/>**Trigger**: whenever a visitor submits their email or username to the lost password form
<br/>**Summary**: Sends a one-time login link to allow user to reset password.

### Infrequent templates

* Account activation
<br/>**Trigger**: When a super administrator user enables a previously cancelled user account
<br/>**Summary**: Provides a log in link and a username/password reminder.

* Account cancellation confirmation
<br/>**Trigger**: When a super administrator cancels a user account with confirmation (i.e. if a user wants their own user account deleted)

* Welcome (new user created by an administrator)
<br/>**Trigger**: When a new user account is created by a super administrator (i.e. for a non-harvard affiliated special user)

### Unavailable templates

* Welcome (awating approval)
<br/>**Trigger**: whenever a user registers themselves a new account (Forbidden on production) and requires approval

* Welcome (no approval required)
<br/>**Trigger**: whenever a user registers themeselves a new account (Forbidden on production)
