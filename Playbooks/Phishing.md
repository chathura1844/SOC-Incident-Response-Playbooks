# Phishing Incident Response Playbook

## Detection

- User-reported suspicious email
- Email security gateway alert
- Microsoft Defender alert
- Suspicious login attempt
- Multiple users receiving similar emails

## Analysis

- Review sender address
- Analyze email headers
- Check embedded URLs
- Inspect attachments safely
- Identify affected users
- Confirm whether credentials were entered

## Containment

- Quarantine the email
- Block sender domain
- Block malicious URLs
- Reset affected user passwords
- Revoke active sessions
- Enforce MFA

## Eradication

- Remove emails from mailboxes
- Delete malicious files
- Remove suspicious inbox rules
- Update email filtering rules

## Recovery

- Restore account access
- Monitor login activity
- Confirm no further malicious activity
- Educate affected users

## Lessons Learned

- What allowed the phishing email through?
- Were users trained to report it?
- Were controls effective?
- What can be improved?
