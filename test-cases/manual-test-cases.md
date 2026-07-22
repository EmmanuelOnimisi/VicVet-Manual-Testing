# Manual Test Cases – VicVet Clinic Management System

| Test ID | Test Scenario | Test Steps | Expected Result | Status |
|---------|---------------|------------|-----------------|--------|
| TC-001 | Login with valid credentials | Enter valid username and password, then click Login | User is redirected to the dashboard | Pass |
| TC-002 | Login with invalid password | Enter a valid username and an incorrect password | Error message is displayed | Pass |
| TC-003 | Login with empty fields | Leave username and password blank, then click Login | Validation message is displayed | Pass |
| TC-004 | Register a new pet | Fill in all required pet details and submit | Pet is successfully registered | Pass |
| TC-005 | Register a pet with missing required fields | Leave one or more required fields empty and submit | Validation message is displayed | Pass |
| TC-006 | View registered pets | Open the Pet Management page | List of registered pets is displayed | Pass |
| TC-007 | Update pet information | Edit an existing pet's details and save | Updated information is saved successfully | Pass |
| TC-008 | Delete a pet | Delete an existing pet | Pet is removed from the list after confirmation | Pass |
| TC-009 | Schedule an appointment | Create a new appointment with valid details | Appointment is successfully created | Pass |
| TC-010 | View appointments | Open the Appointments page | All appointments are displayed | Pass |