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
| TC-011 | Register a new user with valid details | User account is created successfully | Not Executed |
| TC-012 | Register with an existing email | Appropriate error message is displayed | Not Executed |
| TC-013 | Register with empty required fields | Validation messages are displayed | Not Executed |
| TC-014 | Access Admin Dashboard after login | Admin dashboard loads successfully | Not Executed |
| TC-015 | Access User Dashboard after login | User dashboard loads successfully | Not Executed |
| TC-016 | Add a new staff member | Staff member is added successfully | Not Executed |
| TC-017 | Edit staff information | Updated information is saved | Not Executed |
| TC-018 | Delete a staff member | Staff member is removed successfully | Not Executed |
| TC-019 | Add a medical record | Medical record is saved successfully | Not Executed |
| TC-020 | View a patient's medical records | Records are displayed correctly | Not Executed |
| TC-021 | Search for a registered pet | Matching pet records are displayed | Not Executed |
| TC-022 | Search using a non-existent pet name | No matching records are found | Not Executed |
| TC-023 | Update an existing medical record | Changes are saved successfully | Not Executed |
| TC-024 | Delete a medical record | Medical record is removed successfully | Not Executed |
| TC-025 | Schedule an appointment with valid details | Appointment is created successfully | Not Executed |
| TC-026 | Schedule an appointment with missing required fields | Validation message is displayed | Not Executed |
| TC-027 | Edit an appointment | Appointment details are updated successfully | Not Executed |
| TC-028 | Cancel an appointment | Appointment is removed or marked as cancelled | Not Executed |
| TC-029 | View all staff members | Staff list is displayed correctly | Not Executed |
| TC-030 | Search for a staff member | Matching staff member is displayed | Not Executed |
| TC-031 | Logout from the system | User is logged out and redirected to the login page | Not Executed |
| TC-032 | Access a protected page without logging in | User is redirected to the login page | Not Executed |
| TC-033 | Register a pet with an invalid date of birth | Validation message is displayed | Not Executed |
| TC-034 | Register a pet with all required fields | Pet is registered successfully | Not Executed |
| TC-035 | View owner information | Owner details are displayed correctly | Not Executed |
| TC-036 | Update owner information | Changes are saved successfully | Not Executed |
| TC-037 | Delete owner information | Owner record is removed successfully | Not Executed |
| TC-038 | Navigate between dashboard modules | Navigation works without errors | Not Executed |
| TC-039 | Refresh the dashboard page | Dashboard reloads successfully | Not Executed |
| TC-040 | Verify dashboard statistics are displayed | Dashboard statistics load correctly | Not Executed |