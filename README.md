# Labour-Management-System
# Labour Management System (LabourMS)

A comprehensive workforce management platform built with React and Firebase, designed to streamline labor operations for construction and similar industries. The system supports role-based access for administrators, supervisors, and workers, enabling efficient task assignment, attendance tracking, leave management, and payroll processing.

## 🚀 Features

### For Workers
- **Attendance Tracking**: Clock in/out with real-time hour calculation
- **Task Management**: View and update assigned tasks with status tracking
- **Leave Requests**: Submit and track leave/absence requests
- **Profile Management**: Update personal information and contact details
- **Notifications**: Real-time notifications for task updates and approvals

### For Supervisors
- **Worker Management**: Oversee assigned workers, set salaries, and manage accounts
- **Task Assignment**: Create and assign tasks to workers with deadlines and locations
- **Leave Approval**: Review and approve/reject leave requests from workers
- **Registration Management**: Approve new worker registration requests
- **Performance Monitoring**: Track worker attendance and task completion

### For Administrators
- **User Management**: Create and manage all user accounts across the system
- **Project Management**: Create and track projects with budgets and timelines
- **Payroll Processing**: Generate monthly payroll reports with automated calculations
- **System Settings**: Configure company information and upload logos
- **Registration Oversight**: Approve supervisor registration requests

## 🛠️ Tech Stack

- **Frontend**: React 19.1.1 with React Router DOM
- **Styling**: Tailwind CSS with PostCSS and Autoprefixer
- **Backend**: Firebase (Authentication, Firestore, Storage)
- **Build Tool**: Create React App
- **Testing**: Jest and React Testing Library
- **Deployment**: Firebase Hosting (recommended)

## 📋 Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- Firebase project with Firestore, Authentication, and Storage enabled

## 🔧 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/labourms.git
   cd labourms
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure Firebase**
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/)
   - Enable Authentication, Firestore Database, and Storage
   - Copy your Firebase config to `src/firebase.js`

4. **Set up Firestore Security Rules**
   - Copy the rules from `firestore.rules` to your Firebase project
   - Deploy the rules to your Firestore database

5. **Start the development server**
   ```bash
   npm start
   ```

   The application will open at [http://localhost:3000](http://localhost:3000)

## 🚀 Deployment

### Build for Production
```bash
npm run build
```

### Deploy to Firebase Hosting
```bash
npm install -g firebase-tools
firebase login
firebase init hosting
firebase deploy
```

## 📖 Usage

### First-Time Setup
1. Register as an Admin user through the application
2. Create Supervisor accounts
3. Supervisors can then approve Worker registrations

### User Roles and Permissions
- **Admin**: Full system access, user management, project creation, payroll
- **Supervisor**: Manage workers, assign tasks, approve leaves, monitor attendance
- **Worker**: Clock in/out, view tasks, submit leave requests, update profile

## 🗂️ Project Structure

```
labourms/
├── public/
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   └── manifest.json
├── src/
│   ├── App.css
│   ├── App.js
│   ├── App.test.js
│   ├── firebase.js
│   ├── index.css
│   ├── index.js
│   ├── logo.svg
│   ├── reportWebVitals.js
│   └── setupTests.js
├── .firebaserc
├── .gitignore
├── firebase.json
├── firestore.indexes.json
├── firestore.rules
├── package.json
├── postcss.config.js
├── README.md
└── tailwind.config.js
```

## 🔒 Security Features

- Role-based access control (RBAC)
- Firebase Authentication for secure login
- Firestore security rules to protect data access
- Real-time data validation and sanitization

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request


## 📞 Support

For support and questions, please open an issue on GitHub or contact the development team.

## 🔄 Recent Updates

- ✅ Real-time notifications for leave requests and registrations
- ✅ Enhanced admin dashboard with project and payroll management
- ✅ Improved user registration flow with supervisor approval
- ✅ Task assignment and tracking system
- ✅ Automated payroll generation based on attendance

---

**Built with ❤️ for efficient workforce management by Ganesh deore**


