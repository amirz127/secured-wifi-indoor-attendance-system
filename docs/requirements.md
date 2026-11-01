# System Requirements

## Functional Requirements

- FR1: The system shall allow students to log in using their registered accounts.
- FR2: The system shall detect the available classroom WiFi SSID.
- FR3: The system shall verify whether the detected SSID matches the registered classroom WiFi SSID.
- FR4: The system shall generate a SHA-256 hash of the student's Student ID.
- FR5: The system shall generate a SHA-256 hash of the student's IP Address.
- FR6: The system shall allow students to submit attendance after successful verification.
- FR7: The system shall record the attendance date and time.
- FR8: The system shall prevent duplicate attendance submissions for the same class session.
- FR9: The system shall allow lecturers to view student attendance records.
- FR10: The system shall allow administrators to manage attendance information.

## Non-Functional Requirements

- NFR1 – Security: The system shall use SHA-256 hashing when processing Student IDs and Device IDs.
