# Leadwise International Consultancy - Working Prototype

## Overview
This is a fully connected prototype for Leadwise International Consultancy Services, featuring three main components with seamless navigation and interactive features.

## Files Included

1. **index.html** - Public Website (START HERE)
   - Landing page with company information
   - Services showcase
   - Contact form with submission feedback
   - Smooth scrolling navigation
   - Login button to access portal

2. **login.html** - Login Portal
   - Automatic role detection based on email
   - Admin emails route to admin panel
   - Regular emails route to applicant dashboard
   - Demo credentials provided

3. **applicant-dashboard.html** - Applicant Portal
   - Dashboard with application statistics
   - Application tracking with timeline
   - Document management
   - Interactive buttons with notifications

4. **admin-panel.html** - Admin Management System
   - Application management dashboard
   - Comprehensive statistics
   - Filter and export functionality
   - Update modal for application status
   - Bulk actions

## How to Use

### Getting Started
1. Open **index.html** to start (public home page)
2. Browse the website and explore services
3. Click "Login" in the navigation menu
4. Enter credentials (system automatically detects if you're admin or applicant)
   - Use **admin@leadwise.com** to access admin panel
   - Use **john@email.com** to access applicant dashboard
   - Any password works in demo mode

### Navigation Flow
```
index.html (Public Website - START HERE)
    └── login.html (Login Portal)
        ├── applicant-dashboard.html (Applicant View)
        │   ├── Logo → index.html
        │   └── Logout → login.html
        └── admin-panel.html (Admin View)
            ├── Logo → index.html
            └── Logout → login.html
```

### Interactive Features

#### Home Page (index.html)
- Smooth scrolling navigation
- Working contact form with success message
- Responsive design
- Login button redirects to login portal

#### Login Portal (login.html)
- Automatic user type detection based on email
- Emails containing "admin" or "@leadwise.com" → Admin Panel
- All other emails → Applicant Dashboard
- Demo credentials provided for testing

#### Applicant Dashboard (applicant-dashboard.html)
- Real-time statistics display
- Application timeline visualization
- Document list with download buttons
- Notification system for actions
- Sidebar navigation (demo mode)

#### Admin Panel (admin-panel.html)
- Application management table
- Filter controls by status and country
- Working update modal for application status
- Export functionality (demo)
- Quick action buttons
- Pagination controls
- Success notifications

### Key Features

✅ **Fully Connected Navigation**
- All pages link to each other
- Consistent header navigation
- Logout returns to login page
- Logo returns to home page

✅ **Interactive Elements**
- Working modals
- Form submissions with feedback
- Hover effects and animations
- Button click notifications

✅ **Responsive Design**
- Mobile-friendly layouts
- Adaptive grids
- Collapsible sidebars on mobile

✅ **Professional UI/UX**
- Gradient designs
- Modern color schemes
- Smooth transitions
- Clear visual hierarchy

## Demo Mode Notes

This is a prototype, so:
- Forms show success messages but don't submit data
- Buttons trigger notifications to show interactivity
- All data is static (for demonstration)
- No backend server required

### Authentication Logic
The login system automatically routes users based on their email:
- **Admin access**: Emails containing "admin" OR ending with "@leadwise.com"
- **Applicant access**: All other email addresses
- Password validation is not enforced in demo mode
- In production, replace with proper authentication service

## Browser Compatibility

Works best in modern browsers:
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## Customization

To customize for production:
1. Replace email-based routing with proper authentication API
2. Add secure password validation and session management
3. Connect forms to backend services
4. Implement actual file upload/download
5. Add data persistence and database integration

## Color Scheme

Primary Colors:
- Blue: #1e3a8a
- Cyan: #0ea5e9
- Green: #22c55e (success)
- Orange: #f59e0b (warning)
- Red: #ef4444 (error)

## Support

For questions or issues with this prototype, please contact the development team.

---
**Leadwise International Consultancy Services**
*Bridging Talent with Opportunity Worldwide*
