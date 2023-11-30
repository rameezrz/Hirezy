# Hirezy - Freelance Marketplace Project

## Overview

This open-source project aims to create a comprehensive freelance marketplace platform, providing a space for freelancers and clients to connect, collaborate, and complete various types of freelance work. Leveraging a modern tech stack, the platform facilitates job posting, bidding, contract management, and secure payment transactions.

## Features

- **User Authentication:**
  - Secure user registration and authentication.
  - Support for both email/password and social media login.

- **Job Management:**
  - Seamless job posting with detailed descriptions.
  - Bidding system allowing freelancers to submit proposals.
  - Contract creation and management between clients and freelancers.

- **Messaging System:**
  - Real-time messaging between freelancers and clients.
  - Notification system for updates on job proposals, messages, and contract milestones.

- **Payment Integration:**
  - Secure payment processing using Stripe.
  - Transparent handling of transactions with clear invoicing.

- **Review and Rating System:**
  - User-driven review and rating system for freelancers and clients.
  - Feedback mechanism to enhance trust and reputation.

- **Search and Recommendation:**
  - Advanced search functionality for job discovery.
  - Recommendation engine based on user preferences and job history.

- **Admin Panel:**
  - Admin interface for managing users, jobs, and resolving disputes.
  - Analytics dashboard for monitoring platform performance.

## Technology Stack

- **Frontend:**
  - React for building interactive and dynamic user interfaces.
  - Redux for state management.

- **Backend:**
  - Node.js with Express for the server-side application.
  - PostgreSQL (psql) as the database for storing user profiles, jobs, and contracts.

- **Microservices Architecture:**
  - Utilizes a microservices architecture for scalability and maintainability.
  - Services include user management, job service, messaging, payment, and more.

- **Message Broker:**
  - Kafka for handling asynchronous communication between microservices.

- **Authentication and Authorization:**
  - Firebase for user authentication and access control.

- **Real-time Communication:**
  - Socket.IO for real-time bid updates and messaging.

- **External Services:**
  - Integration with third-party services such as Twilio for OTP, SendGrid for email notifications, and more.

## Deployment

- The project can be deployed on cloud platforms such as AWS or Heroku.
- Docker containers for easy deployment and scaling.

## Contribution

- We welcome contributions from the open-source community.
- Fork the repository, make improvements, and submit pull requests.

## License

This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details.

## Related Documentations

- [Figma Design](https://www.figma.com/file/jYQT4TbH5ZFKQGFLxspJno/second-project?type=design&node-id=0%3A1&mode=design&t=bh6AESJsm3oO5wZu-1)
- [Microservice Diagram](https://drive.google.com/file/d/1nGp8_juwITkzmGvTr7UD2ze0VdExVGcI/view?usp=drive_link)
- [API Documentation](https://documenter.getpostman.com/view/27651295/2s9YeHZAYE)
- [API Documentation](https://rzeee.atlassian.net/wiki/spaces/~71202014c6c55ea82047d38f90997a47a9f050/pages/1474562/Module+Documentation)
- [Entity Relation Diagram](https://drive.google.com/file/d/1KFPdNmzRUR6mX3sZ8ohMQ3zMOggWiXNT/view?usp=drive_link)
- [Module Documentation](https://rzeee.atlassian.net/wiki/spaces/~71202014c6c55ea82047d38f90997a47a9f050/pages/1474562/Module+Documentation)
- [Third-Party Service Integration Documentation](https://rzeee.atlassian.net/wiki/spaces/SD/blog/2023/11/28/65809/Third-Party+Service+Integration+Documentation?atlOrigin=eyJpIjoiZWNmMDA0NDIyOTAzNDI4NDk3MjE3NTNhZjlkY2E2NzQiLCJwIjoiYyJ9)
- [Timeline Documentation](https://rzeee.atlassian.net/wiki/spaces/SD/blog/2023/11/28/262177/Hirezy+-+Timeline+Documentation?atlOrigin=eyJpIjoiMTYwOWU0MDEyMTZhNGFlNmI2NDQzYzQyNTc5ODBmYjIiLCJwIjoiYyJ9)
