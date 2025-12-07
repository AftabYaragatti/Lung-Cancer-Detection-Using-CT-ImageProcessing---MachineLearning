# How to Test Registration Data Storage

## Quick Test Steps:

### 1. Open User_Dashboard.html in Browser
- Open `User_Dashboard.html` in your browser
- Press `F12` to open Developer Tools
- Go to **Console** tab

### 2. Create a User Account First
- Click "New User Registration"  
- Email: `test@example.com`
- Password: `test123`
- Click "Create Account"
- You'll see: ✅ User account created
- Login with those credentials

### 3. Complete Registration Form
- Fill in all required fields:
  - Full Name: `John Doe`
  - Age: `30`
  - Gender: `Male`
  - City: `New York`
  - Contact: `9876543210` (exactly 10 digits)
  - Email: `test@example.com`
  - Emergency Contact: `9876543211` (optional)
  - Address: (optional)
  - Profile Photo: **SELECT A PHOTO** (required!)

### 4. Watch Console for Logs
When you click "Complete Registration", you'll see in Console:
```
🔵 Registration form submitted for email: test@example.com
📋 Form data collected: {...}
📷 Processing photo: filename.jpg 12345 bytes
✅ Photo converted to base64, size: 123456 chars
💾 Registration data prepared: {...}
✅ Registration saved to localStorage, total: 1
🎉 Registration successful!
```

### 5. Verify Data Saved
In the **Console**, run this command:
```javascript
JSON.parse(localStorage.getItem('userRegistrations'))
```

You should see an array with your registration object:
```javascript
[{
  uniqueId: "MD123456ABCD",
  registrationDate: "2025-11-22",
  registrationTime: "14:30",
  fullName: "John Doe",
  age: "30",
  gender: "Male",
  city: "New York",
  contact: "9876543210",
  email: "test@example.com",
  emergencyContact: "9876543211",
  address: "Your address",
  userPhoto: "data:image/jpeg;base64,/9j/4AAQSkZJRg...",
  registrationTimestamp: "2025-11-22T14:30:45.123Z"
}]
```

### 6. Check Admin Dashboard
- Open `Admin_Dashboard.html`
- Login as Admin:
  - Email: `admin@test.com`
  - Password: `admin123`
  - Access Code: `ADMIN2024`
- Go to "User Management" section
- You should see your registered user in the table

## Troubleshooting

### If nothing saves:
1. Check **Console** for errors (F12)
2. Make sure you selected a **photo file** - this is required
3. Make sure all required fields are filled
4. Make sure contact number is exactly 10 digits

### If data appears but Admin doesn't see it:
1. Open Admin Dashboard
2. Click "User Management"
3. Click "🔄 Refresh Data" button
4. Data should appear after 2 seconds

### To clear all test data:
Run this in Console:
```javascript
localStorage.clear();
location.reload();
```

---

**All data is stored in browser localStorage automatically!**
No additional server needed for local testing.
