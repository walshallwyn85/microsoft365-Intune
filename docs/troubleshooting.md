# Troubleshooting

## Issue: License assignment cannot be done for user with invalid usage location
### Cause
The user account did not have a valid usage location configured.

### Resolution
Updated the user's usage location in Microsoft Entra ID and retried the license assignment.

---

## Issue: Device not showing in Intune
### Cause
Enrollment was incomplete or licensing/MDM setup was missing.

### Resolution
Verified licensing, MDM authority, and enrollment flow. Retried enrollment after correcting settings.

---

## Issue: Company Portal temporarily unavailable
### Cause
Possible app-side issue, authentication issue, or Intune/Entra configuration issue.

### Resolution
Rechecked sign-in flow, internet access, app updates, and enrollment configuration.
