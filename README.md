# Aspire Academy

A comprehensive educational community platform for tutors and learners to connect, share resources, and collaborate effectively.

*Empowering education through technology.*

---

## Table of Contents

1. [About the Project](#about-the-project)
2. [Features](#features)
3. [Tech Stack](#tech-stack)
4. [Getting Started](#getting-started)
5. [Contributing](#contributing)
6. [Future Improvements](#future-improvements)
7. [License](#license)
8. [Contact](#contact)
9. [Connect with Me](#ConnectwithMe)

---

## About the Project

Aspire Academy is an innovative educational platform designed to bridge the gap between tutors and learners. It provides a space for collaboration, resource sharing, and interactive learning experiences.

---

## Features

- **User Authentication**: Secure registration and login functionality using JWT.
- **Role-Based Access**: Separate functionalities for Tutors and Students.
- **Homepage Feed**: Announcements, comments, reactions, and more.

---

## Tech Stack

- **Frontend**: React.js, React Router, Redux Toolkit, Tailwind CSS
- **Backend**: Node.js, Express.js, MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Version Control**: Git, GitHub
- **Deployment**: Vercel (Frontend), Render (Backend)

---

## Getting Started

To get a local copy of this project up and running, follow these steps:

### Prerequisites

- Node.js and npm installed
- MongoDB database set up locally or remotely

### Installation

1. **Clone the repository**

```
git clone https://github.com/amanpandey3956/Aspire-Academy.git
cd Aspire-Academy
```

2. **Install Dependencies**

Frontend:
```
cd client
npm install
```

Backend:
```
cd server
npm install
```

3. **Environment Variables**

Create `.env` files in both client and server directories.

Frontend `.env`

```
REACT_APP_API_URL= `http://localhost:5000`
```

Backend `.env`

```
PORT=5000
MONGO_URI=<Your MongoDB URI>
JWT_SECRET=<Your Secret Key>
```

4. **Run the Application**

Start Backend:

```
cd server
npm run dev
```

Start Frontend:

```
cd client
npm run dev
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes with detailed messages.
4. Submit a pull request.

## Future Improvements

- Add calendar view for events.
- Enhance performance with server-side rendering (SSR).

## License

This project is licensed under the MIT License.

## Contact

For queries or support, please email: [amanpandey39563@gmail.com](mailto:amanpandey39563@gmail.com).

## Connect with Me

- My [Links for Socials](https://linktr.ee/Aman.Pandey).