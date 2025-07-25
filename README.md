# 🦷 ENTNT Dental Center Management System

A modern, responsive web application for managing dental clinic operations with separate portals for administrators and patients. Built with React and featuring a clean, intuitive interface for comprehensive dental practice management.
## 🚀 Features

### 👩‍⚕️ Admin Portal
- **🔐 Secure Authentication** - Email and password-based login system
- **📊 Analytics Dashboard** - Real-time KPIs including:
  - Total registered patients
  - Upcoming appointments count
  - Completed treatments summary
  - Monthly revenue tracking
- **👨‍⚕️ Patient Management** - Complete CRUD operations for patient records
- **🦷 Treatment Records** - Comprehensive treatment and incident history tracking
- **📅 Appointment Calendar** - Interactive calendar view for scheduling management
- **📁 File Management** - Upload and view treatment-related documents (invoices, reports, X-rays)

### 🧑 Patient Portal
- **🔐 Patient Authentication** - Secure login for registered patients
- **📅 Appointment Overview** - View scheduled and upcoming appointments
- **👤 Profile Management** - Update personal information and contact details
- **🧾 Treatment History** - Access complete treatment records and medical history
- **📱 Responsive Design** - Optimized for mobile and desktop devices

## 🔐 Demo Credentials

| Role    | Email               | Password     |
|---------|---------------------|--------------|
| **Admin**   | `admin@entnt.in`    | `admin123`   |
| **Patient** | `john@entnt.in`     | `patient123` |

> 💡 **Note**: The system comes pre-loaded with 15 sample patients and treatment records for demonstration purposes.

## 🛠️ Technology Stack

- **⚛️ React 19** - Modern React with latest features
- **🌐 React Router DOM v7** - Client-side routing and navigation
- **🎨 Tailwind CSS** - Utility-first CSS framework for styling
- **💾 LocalStorage** - Client-side data persistence (mock backend)
- **📅 React Calendar** - Interactive calendar component
- **⚙️ PostCSS + Autoprefixer** - CSS processing and vendor prefixing

## 🚀 Quick Start

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Vickym78/Dental-Center-Management.git
   cd Dental-Center-Management
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   ```
   http://localhost:3000
   ```

### Production Build

```bash
npm run build
```

The build folder will contain the production-ready files.

## 📱 Usage

### Admin Workflow
1. Login with admin credentials
2. Access the dashboard to view clinic statistics
3. Manage patient records (add, edit, delete)
4. Record treatments and incidents
5. View appointments in calendar format
6. Upload and manage treatment files

### Patient Workflow
1. Login with patient credentials
2. View upcoming appointments
3. Update profile information
4. Access treatment history
5. Review past appointments and treatments

## 🔧 Development

### Key Features Implementation
- **Authentication**: Role-based access control
- **Data Management**: LocalStorage for persistence
- **Responsive Design**: Mobile-first approach with Tailwind
- **State Management**: React hooks and context
- **Routing**: Protected routes for admin/patient areas

## 🔄 Data Reset

To reinitialize the application with fresh data:

1. Open browser DevTools (F12)
2. Navigate to **Application** → **LocalStorage**
3. Clear the following keys:
   - `users`
   - `patients`
   - `incidents`
4. Refresh the application

The system will automatically regenerate sample data.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Vicky Mahato**
- GitHub: [@Vickym78](https://github.com/Vickym78)

## 🙏 Acknowledgments

- Built as part of the ENTNT Technical Assignment
- Icons provided by Lucide React

---

⭐ **Star this repository if you found it helpful!**
