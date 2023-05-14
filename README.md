# Secure Labs Access

Secure Labs Access is an application that provides a secure and automated way of accessing labs using face recognition and QR code scanning technology. The application has been designed to ensure that only authorized personnel can access the labs and provides an easy and convenient way for users to register and gain access.

## Features

- User registration and authentication using face recognition and QR code scanning.
- Admin dashboard for managing user access and viewing logs.
- Access granted and denied screens displayed based on user authentication status.
- Secure login credentials for admin access.
- Logs are generated automatically at every event.

## Technologies Used

- Figma software for UI design
- draw.io for flowchart creation
- VS Code IDE for code writing
- Face recognition using Python
- QR code generation using Python
- SQLite3 for database management

## How to Use

### User Use Case
Title: User Access Control

Actor: User

Description: The user wants to access the lab securely.

Precondition: User has installed the application and registered their details along with their facial image.

Postcondition: User can either be granted access or denied access.

#### Main Flow:

1. User opens the application.
2. User goes to the home screen and selects the option to scan their face.
3. Application opens the camera and scans the user's face.
4. If the user's face is recognised, the user can scan the QR code to enter the lab.
5. User scans the QR code.
6. If the QR code is verified, the user is granted access to the lab.
7. If the QR code is not verified, the user is denied access to the lab.

Alternate Flow:
  - If the user's face is not recognised, the user is denied access to the lab.
  - If the QR code is not scanned within 10 seconds, the user is denied access to the lab.
  - If the QR code is wrong, the user is denied access to the lab.

### Admin Use Case
Title: Admin Access Control

Actor: Admin

Description: The admin wants to monitor and control user access to the lab.

Precondition: Admin has installed the application and has the login credentials.

Postcondition: Admin can toggle user authorization and view logs of user access.

#### Main Flow:

1. Admin opens the application and logs in with their credentials.
2. Admin goes to the dashboard.
3. Admin can toggle user authorization to grant or deny access to the lab.
4. Admin can view logs of user access to the lab.

Alternate Flow:
  - If the admin credentials are wrong, the admin is denied access to the dashboard.

## Future Scope

- Integration with other lab access control systems such as card readers and biometric systems.
- Implementation of a real-time notification system for admin alerts.
- Integration with cloud-based storage solutions for storing logs and user data.

## Conclusion

Secure Labs Access provides an innovative solution to lab access control and management, ensuring that only authorized personnel can gain access. The application provides a user-friendly and secure way of managing access and is an essential tool for labs that require strict access control measures.
