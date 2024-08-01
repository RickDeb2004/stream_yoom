# Streaming Platform

This project is a feature-rich streaming platform that implements authentication and authorization using Clerk, providing users with a secure and seamless experience for hosting and joining meetings. The platform offers a range of meeting controls, scheduling options, and secure real-time functionality.

## Features

- **Authentication**: Implements authentication and authorization features using Clerk, allowing users to securely log in via social sign-on or traditional email and password methods, while ensuring appropriate access levels and permissions within the platform.
- **New Meeting**: Quickly start a new meeting, configuring camera and microphone settings before joining.
- **Meeting Controls**: Participants have full control over meeting aspects, including recording, emoji reactions, screen sharing, muting/unmuting, sound adjustments, grid layout, participant list view, and individual participant management (pinning, muting, unmuting, blocking, allowing video share).
- **Exit Meeting**: Participants can leave a meeting, or creators can end it for all attendees.
- **Schedule Future Meetings**: Input meeting details (date, time) to schedule future meetings, accessible on the 'Upcoming Meetings' page for sharing the link or immediate start.
- **Past Meetings List**: Access a list of previously held meetings, including details and metadata.
- **View Recorded Meetings**: Access recordings of past meetings for review or reference.
- **Personal Room**: Users have a personal room with a unique meeting link for instant meetings, shareable with others.
- **Join Meetings via Link**: Easily join meetings created by others by providing a link.
- **Secure Real-time Functionality**: All interactions within the platform are secure and occur in real-time, maintaining user privacy and data integrity.
- **Responsive Design**: Follows responsive design principles to ensure optimal user experience across devices, adapting seamlessly to different screen sizes and resolutions.
- **Code Architecture and Reusability**: Ensures a clean and maintainable codebase with a focus on reusable components and modular design.

## Quick Start

Follow these steps to set up the project locally on your machine.

### Prerequisites

Make sure you have the following installed on your machine:
- Git
- Node.js
- npm (Node Package Manager)

### Cloning the Repository

Clone the project repository and navigate into the project directory:

```sh
git clone https://github.com/adrianhajdin/zoom-clone.git
cd zoom-clone
```

### Installation

Install the project dependencies using npm:

```sh
npm install
```

### Set Up Environment Variables

Create a new file named `.env` in the root of your project and add the following content:

```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

NEXT_PUBLIC_STREAM_API_KEY=your_stream_api_key
STREAM_SECRET_KEY=your_stream_secret_key
```

Replace the placeholder values with your actual Clerk and Stream credentials. You can obtain these credentials by signing up on the [Clerk website](https://clerk.dev/) and [GetStream website](https://getstream.io/).

### Running the Project

```sh
npm run dev
```

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## Contact

For any questions or inquiries, please contact the project maintainers.

---

Thank you for using our streaming platform project. Happy coding!
