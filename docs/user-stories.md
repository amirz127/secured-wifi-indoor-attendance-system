# User Stories

## User Story 1: Student Login

As a student, I want to log in to the attendance application, so that I can access the attendance check-in function.

Acceptance Criteria:
- The student must provide valid login credentials.
- The system must allow access after successful authentication.

Related Requirement: FR1

## User Story 2: WiFi Attendance Verification

As a student, I want the system to verify the classroom WiFi SSID, so that I can record attendance when I am connected to the registered classroom network.

Acceptance Criteria:
- The system must detect the WiFi SSID.
- The system must compare the detected SSID with the registered classroom SSID.
- The system must reject attendance if the SSID does not match.

Related Requirements: FR2, FR3, FR6

## User Story 3: View Attendance Records

As a lecturer, I want to view student attendance records, so that I can monitor student attendance for each class session.

Acceptance Criteria:
- The lecturer must be able to view the attendance list.
- The attendance record must display the student's information, date and time.

Related Requirements: FR7, FR9
