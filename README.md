# Status
The Development is in progress. Will announce the progress in this section

# Vaccine Search App

Vaccine Search App allows you to set notification for vaccine availability. The idea behind the solution is to be least privacy invasive by not storing any information.

# Salient Features
1. Allows user to lookup for vaccine near area of their choice. Selection of area by Postal Code or by District selection.
2. Set/unset notifications on an a Mobile or Desktop Device via Browser Notification.

# Technical Details
The intention was to be least privacy invasive , so a Service Worker is Installed on the device post users consent and requests the API to check for availability every [X] minutes.
The X is kept configurable in file which is in Config folder in repo.
Also the SW apart from checking the polling interval also considers the enabled flag set in configuration, this is done to stop the app anytime due to heavy load on the API.


# Coming Up
1. Technical Block diagram
2. Issues fixes if any
