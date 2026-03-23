# Smart Job Portal - WordPress Plugin

## Overview
Complete job portal plugin for WordPress with:
- Job listing shortcode `[job_list]`
- Job application with resume upload `[apply_job]`
- Admin dashboard for job management
- Responsive design with CSS/JS

## Features
- ✅ Add/Edit/Delete jobs (Admin)
- ✅ View job applications (Admin)
- ✅ Public job listings
- ✅ Resume upload for applications
- ✅ User authentication required for applications

## 🚀 Quick Setup (5 minutes)

### Prerequisites
- Local WordPress (XAMPP, LocalWP, or any WP install)
- PHP 7.4+, MySQL 5.7+

### Step 1: Install WordPress Plugin
```
1. Copy `job-portal` folder to `/wp-content/plugins/smart-job-portal/`
2. Go to WP Admin → Plugins → Activate "Smart Job Portal"
```
**Tables auto-created on activation!**

### Step 2: Add Test Jobs (Admin)
```
WP Admin → Jobs → Add New Job
Title: "Frontend Developer"
Description: "Build amazing UIs..."
```

### Step 3: Create Job List Page
```
1. WP Admin → Pages → Add New
2. Title: "Jobs"
3. Add shortcode: `[job_list]`
4. Publish
```

### Step 4: Test Application Flow
```
1. Visit Jobs page → Click "Apply"
2. Create WP user account & login
3. Fill application form → Upload resume
4. Check Admin → Applications
```

## 📱 Live Demo Flow
```
Homepage → [job_list] → Click Apply → Login → Upload Resume → Success!
Admin: Jobs → Add jobs | Applications → View submissions
```

## Shortcodes
```
[job_list]          - Shows all jobs
[apply_job]         - Application form (login required)
```

## File Structure
```
smart-job-portal/
├── job-portal.php      ← Main plugin file
├── includes/           ← Core functions
├── admin/             ← Admin dashboard
├── public/            ← Frontend shortcodes
├── assets/            ← CSS + JS
└── templates/         ← Dashboard templates
```

## Admin Menu
```
Jobs → Manage jobs
Applications → View applicants
```

## Customization
- Edit `assets/css/style.css`
- Modify shortcodes in `public/*.php`
- Extend database in `job-portal.php`

## Troubleshooting
```
Q: No jobs showing?
A: Add jobs first via Admin → Jobs

Q: Apply not working?
A: Must be logged in WP user

Q: Tables not created?
A: Deactivate → Reactivate plugin
```

**Plugin ready for production!** 🎉
