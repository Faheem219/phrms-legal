# PHRMS — Privacy Policy

**Effective date:** [12 May 2026]

**Last updated:** [12 May 2026]

## 1. Who this app is for

PHRMS (Patient Health Records Management System) is a restricted
clinical workflow application used by nurses and unit administrators
at Sassoon General Hospital to track post-operative recovery of
patients who have undergone Total Knee or Total Hip Replacement
surgery. It is not available to the general public and is not
intended for patient self-use. Patients do not interact with the app
directly; nurses enter clinical data on their behalf as part of
routine post-operative documentation.

## 2. Who controls the data

The data controller is Dr. Mrudula Phule from Sassoon General Hospital, Pune, India.
For privacy questions, contact: **[phulevaishali@gmail.com]**.

## 3. What we collect

**From the nurse or administrator using the app:**
- Username, full name, hashed password (we never store passwords in
  plain text)
- The hospital you are affiliated with
- The Firebase Cloud Messaging device token for the phone you sign
  in on (used solely to deliver assessment-due notifications)
- The timestamps of your sign-ins and the assessments you complete

**About the patients under your care (entered by you):**
- Demographic information (name, age, sex, contact, socioeconomic)
- Clinical baseline (medical history, vital signs, mobility scores,
  pain scores, muscle strength, dependency scales, deformity,
  pressure-ulcer risk, observations)
- Periodic outcome assessments (vital signs, self-reported survey
  responses, recovery progress)
- Audit forms completed by administrators at the unit level

We do not collect any data from patients directly through the app.
We do not access your phone's contacts, photos, microphone, camera,
location, calendar, SMS, or call history.

## 4. How we use the data

The data is used solely to:
- Authenticate you and route you to the correct dashboard
- Display the patients assigned to you
- Schedule and deliver the next periodic assessment reminder
- Allow administrators to monitor unit-level compliance and complete
  required audits
- Generate institutional Excel exports for offline clinical review

We do not use the data for advertising, profiling, analytics,
training of AI models, or any commercial purpose.

## 5. Push notifications

PHRMS uses Firebase Cloud Messaging (Google LLC) to deliver
assessment reminders. The push payload contains only an assessment
identifier, an in-app route, and a short clinical reminder string
(for example: "Assessment due: <patient name>"). Notification
content reaches Google's FCM servers solely for delivery and is not
retained by Google for any other purpose. You can disable
notifications at any time from your phone's system settings.

## 6. How long we keep it

Clinical records are retained for the period mandated by Indian
medical record retention rules and Sassoon General Hospital's
institutional policy. Authentication records (sign-ins, FCM tokens)
are retained for as long as your account is active and deleted on
sign-out or account removal.

## 7. Who we share it with

We do not sell, rent, or trade any data. Data is shared only:
- With Firebase Cloud Messaging (Google) for the limited purpose of
  delivering push notifications (see Section 5)
- With MongoDB Atlas (MongoDB, Inc.), our database provider, which
  stores the data encrypted at rest and in transit on our behalf
- Where required by Indian law, court order, or regulatory authority

No data is shared with advertisers, data brokers, or unrelated
third parties.

## 8. Security

- Passwords are hashed with bcrypt; we never store or transmit
  plain-text passwords.
- All traffic between the app and the backend uses HTTPS/TLS.
- Bearer tokens used for authentication expire and must be
  refreshed by re-signing in.
- Access to the administrator dashboard is restricted to credentials
  issued at the hospital level.

## 9. Children

The app is not directed at, nor available to, anyone under 18. It is
a workforce tool used by qualified nursing staff and administrators.

## 10. Your rights

If you are a member of nursing staff using PHRMS, you may:
- Request a copy of the personal data we hold about you
- Request correction of inaccurate data
- Request deletion of your account and associated authentication
  records (clinical data linked to patient care may be retained for
  the legally mandated retention period)

If you are a patient whose data has been entered by nursing staff,
please direct requests at **[phulevaishali@gmail.com]**.

## 11. Changes to this policy

We may update this policy from time to time. Material changes will
be announced on this page and dated above. The current version is
always at this URL.

## 12. Contact

**[Dr. Mrudula Phule - Sassoon General Hospital]**

**[Jai Prakash Narayan Road, Railway Station Rd, Agarkar Nagar, Pune, Maharashtra 411001]**

**Email: [phulevaishali@gmail.com]**
