## What is Active Directory?

Active Directory (AD) is a Microsoft directory service used in Windows Server environments to manage users, computers, groups, and other network resources.  
It helps organizations:
- Control access to resources  
- Enforce security policies  
- Simplify administration
  
![Screenshot](https://github.com/TechWithCJ/IT-Documentation-with-CJ/blob/c88b788c417cf53ce23fb6c284d936f7c98493c8/Windows%20Server/images/AD%20Photo)

---
## Active Directory Domain Services Installation

**Before you begin:**
![Screenshot](https://github.com/TechWithCJ/IT-Documentation-with-CJ/blob/08e5982d34e065fb37fa06fee44b242c45d8f576/Windows%20Server/images/Screenshot%202026-03-01%20145000.png)
1. Open **Server Manager**.
2. Click **Next**.
3. Select **Role-based or feature-based installation**.
4. Click **Next**.
5. Click on **Active Directory Domain Services**.
6. Click **Add Features**.
7. Click **Next**, then **Install** (wait for it to succeed).
8. Click **Promote this server to a domain controller**.
9. Select **Add a new forest**.
10. Enter the **Root domain name** (e.g., helpdeskcj.com).
11. Create a password (e.g., Coolkid123$).
12. Click **Next**.
13. Wait for **Prerequisites check**.
14. Click **Install**  it will restart your computer.

> **Note:** Active Directory Users & Computers are now installed in the server.

---
## Creating a New Account in Active Directory

1. From the **Start Menu**, click on **Windows Administrative Tools**.
2. Go to **Active Directory Users & Computers**.
3. Right-click on **Users**.
4. Scroll down to **New** → **User**.
5. Fill in:
   - User's name  
   - Password (check "User must change password at next login")  
6. Click **Finish**.
![Screenshot](https://github.com/TechWithCJ/IT-Documentation-with-CJ/blob/2455ab10a27e46f01e96a9614c39b2af37cda71d/Windows%20Server/images/Screenshot%202026-03-03%20193219.png)
---
## Show More Details About a User

If you want more features displayed (like showing more details about a user):

- Right-click on **View** (in the top menu).
- Scroll down to **Advanced Features** and check it.
---
