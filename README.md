# 🏥 Doctor Hub [![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=flat-square)](https://your-deployed-url.vercel.app)

A comprehensive healthcare management platform built with modern web technologies. Doctor Hub is a multi-role application designed to streamline healthcare operations, improve patient-doctor interactions, and provide administrative oversight for medical institutions.

---

## 📸 Screenshots

### Dashboard Overview
![Dashboard](https://via.placeholder.com/1200x600?text=Doctor+Hub+Dashboard)
*Add your dashboard screenshot here*

### Patient Portal
![Patient Portal](https://via.placeholder.com/1200x600?text=Patient+Portal)
*Add your patient portal screenshot here*

### Doctor Dashboard
![Doctor Dashboard](https://via.placeholder.com/1200x600?text=Doctor+Dashboard)
*Add your doctor dashboard screenshot here*

### Admin Analytics
![Admin Analytics](https://via.placeholder.com/1200x600?text=Admin+Analytics)
*Add your admin dashboard screenshot here*

### Mobile Responsive
![Mobile View](https://via.placeholder.com/500x900?text=Mobile+Responsive+View)
*Add your mobile view screenshot here*

---

## ✨ Features

### **Patient Portal**
- View medical history and appointment details
- Schedule and manage appointments with doctors
- Access medical records and prescriptions
- Real-time appointment status tracking

### **Doctor Dashboard**
- Manage patient appointments and consultations
- View detailed patient medical profiles
- Update patient records and treatment notes
- Access patient statistics and history

### **Medical Assistant Panel**
- Assist in appointment scheduling and management
- Maintain patient databases
- Generate reports and documentation
- Support administrative workflows

### **Admin Dashboard**
- Comprehensive analytics and reporting
- User and role management
- System configuration and monitoring
- Resource allocation and planning
- Generate insights with interactive charts and analytics

### **Super-Admin Management**
- Full system administration capabilities
- User account management and security
- Access control and permissions management
- System-wide settings and configurations
- Audit logs and monitoring

### **Core Features**
- 🔐 **Secure Authentication** - Role-based access control (RBAC)
- 📊 **Advanced Analytics** - Real-time dashboards and reports
- 📱 **Responsive Design** - Works seamlessly on desktop and mobile
- 🔄 **Real-time Updates** - Live data synchronization
- 📄 **PDF Export** - Generate and download medical documents
- 🎨 **Modern UI** - Beautiful and intuitive user interface

---

## 🌐 Live Demo

**Live URL:** [Add your live deployment URL here]  
*Coming soon - Deploy your application and add the link*

---

## ️ Tech Stack

### **Frontend**
- **React 19** - Modern UI library with hooks
- **TypeScript** - Type-safe JavaScript
- **Vite** - Lightning-fast build tool
- **Tailwind CSS** - Utility-first CSS framework
- **React Router** - Client-side routing
- **React Hook Form** - Efficient form management
- **Zod** - TypeScript-first schema validation
- **React Query** - Powerful data fetching and caching
- **Framer Motion** - Smooth animations
- **Recharts** - Interactive charts and visualizations
- **Zustand** - Lightweight state management
- **Lucide React** - Beautiful icon library
- **Hot Toast** - Toast notifications

### **Backend & Database**
- **Supabase** - PostgreSQL database + authentication
- **Real-time Sync** - Live data updates

### **Development**
- **ESLint** - Code quality and linting
- **PostCSS** - CSS processing
- **Vercel** - Deployment platform

---

## 🚀 Getting Started

### Prerequisites
- Node.js 16.x or higher
- npm or yarn package manager
- Supabase account (free tier available)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ZainDevX/doctor-hub.git
   cd doctor-hub
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure environment variables**
   Create a `.env.local` file in the root directory:
   ```env
   VITE_SUPABASE_URL=your_supabase_url
   VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

4. **Start development server**
   ```bash
   npm run dev
   ```
   The application will be available at `http://localhost:5173`

### Build for Production

```bash
npm run build
```

The optimized build will be created in the `dist` directory.

### Preview Production Build

```bash
npm run preview
```

---

## 📁 Project Structure

```
doctor-hub/
├── src/
│   ├── admin/              # Admin dashboard pages and components
│   ├── assistant/          # Medical assistant interface
│   ├── auth/               # Authentication logic and pages
│   ├── components/         # Reusable React components
│   ├── doctor/             # Doctor portal and pages
│   ├── doctors/            # Doctor discovery and management
│   ├── layout/             # Layout components
│   ├── lib/                # Utility functions and helpers
│   ├── pages/              # Main application pages
│   ├── patient/            # Patient portal
│   ├── shared/             # Shared utilities and constants
│   ├── store/              # Zustand state management
│   ├── super-admin/        # Super-admin management interface
│   ├── ui/                 # UI component library
│   ├── App.tsx             # Main application component
│   └── main.tsx            # Application entry point
├── public/                 # Static assets
├── package.json            # Dependencies and scripts
├── vite.config.ts          # Vite configuration
├── tailwind.config.js      # Tailwind CSS configuration
├── tsconfig.json           # TypeScript configuration
└── README.md               # This file
```

---

## 🔐 User Roles

### **Patient**
- Schedule and manage appointments
- View medical history
- Access test results and prescriptions
- Communicate with healthcare providers

### **Doctor**
- Manage patient appointments
- Update patient medical records
- View appointment schedules
- Manage consultations

### **Medical Assistant**
- Support appointment scheduling
- Maintain patient information
- Generate reports
- Assist with administrative tasks

### **Admin**
- View system analytics
- Manage users and permissions
- Generate reports
- Monitor system performance

### **Super-Admin**
- Full system control
- User management
- Security and access control
- System configuration

---

## 📚 API & Database

The application uses **Supabase** for:
- PostgreSQL database for data persistence
- Real-time subscriptions for live updates
- Authentication and authorization
- Row-level security policies

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 👤 Author

**Zain**
- GitHub: [@ZainDevX](https://github.com/ZainDevX)
- Email: fa23-bse-047@cuivehari.edu.pk

---

## 🙏 Acknowledgments

- Built with [React](https://react.dev)
- Styled with [Tailwind CSS](https://tailwindcss.com)
- Backend powered by [Supabase](https://supabase.io)
- Deployed on [Vercel](https://vercel.com)

---

## 📞 Support

If you encounter any issues or have questions, please:
- Open an issue on GitHub
- Check existing documentation
- Review commit history for implementation details

---

## 🗺️ Roadmap

- [ ] Enhanced patient notification system
- [ ] Mobile app for iOS and Android
- [ ] Advanced appointment scheduling with AI
- [ ] Video consultation integration
- [ ] Electronic health records (EHR) system
- [ ] Prescription management system
- [ ] Telemedicine features

---

**Made with ❤️ by Zain**

Last Updated: June 14, 2026
