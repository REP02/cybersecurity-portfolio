# Linux File Permission Management Project

## 📌 Objective

This project demonstrates how to use Linux commands to manage file permissions and enforce proper access control within an organization.

## 🛠 Tools Used

- Linux CLI
- chmod
- ls -la

## 📖 Steps Taken

- Checked existing file permissions using `ls -la`
- Modified file permissions using `chmod`
- Applied role-based access control (user, group, others)
- Restricted unauthorized access to sensitive files

## 🔍 Key Commands Used

- chmod g-rw project_m.txt
- chmod o-w project_k.txt
- chmod ug-w project_x.txt

## 🔐 Key Concepts

- File permission types (read, write, execute)
- User categories (user, group, others)
- Principle of least privilege

💡 Outcome
Successfully implemented access control by modifying file permissions to ensure only authorized users have the required access.

🚀 Key Takeaways
- Proper permission management is critical for system security
- Small misconfigurations can lead to major vulnerabilities
- Linux provides powerful tools for enforcing access control
