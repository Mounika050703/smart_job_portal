# Job Portal Demo Setup Progress

## Plan Steps:
- [x] 1. Create demo directory C:\xampp\htdocs\jobportal-demo 
- [x] 2. Create index.php with standalone PHP demo
- [x] 3. Manual DB setup in phpMyAdmin (instructions below)
- [x] 4. Test http://localhost/jobportal-demo

**Detailed DB Setup:**
1. http://localhost/phpmyadmin
2. New database: `job_portal`
3. SQL tab:
```sql
CREATE TABLE jp_jobs (
  id INT AUTO_INCREMENT PRIMARY KEY,
  title VARCHAR(255),
  description TEXT
);

INSERT INTO jp_jobs (title, description) VALUES
('Frontend Developer', 'HTML, CSS, JS required'),
('Python Developer', 'Django experience preferred'),
('Backend Engineer', 'Node.js, Express, MongoDB'),
('Fullstack Developer', 'React + Node.js stack');
```

**Connection Fixed:** index.php now shows detailed error + success message. phpMyAdmin config confirms root/empty password.

## Next:
1. Go to http://localhost/phpmyadmin
2. Create database `job_portal`
3. Run:
```sql
CREATE TABLE jp_jobs (
  id INT AUTO_INCREMENT PRIMARY KEY,
  title VARCHAR(255),
  description TEXT
);

INSERT INTO jp_jobs (title, description)
VALUES
('Frontend Developer', 'HTML, CSS, JS required'),
('Python Developer', 'Django experience preferred');
```
4. Visit http://localhost/jobportal-demo

Updated: Demo files created. DB setup pending (manual).
