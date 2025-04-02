
# Medicare App

**Medicare** is a Flutter-based mobile application designed for healthcare environments to improve communication and coordination between head nurses, pharmacies, and nurses. The app allows head nurses or pharmacies to create reminder requests for nurses, who can then accept these tasks and receive notifications at the scheduled time.

---

## Features

- **Signup & Login**: Secure role-based access for head nurses, pharmacies, and nurses.
- **Create Reminder Requests**: Head nurses or pharmacies can create time-sensitive reminder requests.
- **Accept Reminder Requests**: Nurses can view and accept tasks.
- **Notifications**: Nurses receive notifications at the scheduled time for accepted tasks.
- **Role-Based Access**: Different user roles with separate responsibilities to ensure smooth task delegation.

---

## Technologies Used

- **Flutter**: For building cross-platform mobile applications (Android).
- **Dart**: Programming language for Flutter.
- **Firebase (Optional)**: For backend services like authentication, real-time database, and notifications (if integrated).
- **Local Notifications**: For task reminders and notifications.

---

## Getting Started

### Prerequisites

Before you begin, make sure you have the following installed:

- [Flutter](https://flutter.dev/docs/get-started/install)
- [Dart](https://dart.dev/get-dart)

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Jaskirat6773/Medicare.git
   cd Medicare
2. Install Dependencies

Run the following command to install all required dependencies: flutter pub get

3. Run the App

You can run the app on an emulator or a connected device using the following command:  flutter run

### Usage
1. Signup & Login
When the app launches, users can either sign up as a head nurse, pharmacy, or nurse.

After signup, users can log in using their credentials.

2. Head Nurse or Pharmacy Features
Head nurses and pharmacies can create reminder requests by providing details such as task description, time, and other relevant information.

These requests will be visible to all nurses, who can choose to accept them.

3. Nurse Features
Nurses can view all available reminder requests.

They can accept a reminder request and will receive a notification at the scheduled time to remind them of the task.

### Notifications
Once a nurse accepts a task, they will receive a local notification when the task is due.

Notifications will help ensure that no important tasks are missed.

### Future Enhancements
More Security: Implement additional security features to enhance user data protection and ensure privacy.

Separate Login for Patients: Add a dedicated login for patients, allowing them to track their medications, appointments, and health-related tasks.

Real-Time Updates: Implement real-time updates for a more dynamic user experience.

