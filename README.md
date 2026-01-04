# QuizApp - Mini Project

## Functional Requirements – Implementation Status

### Section 1: Application Setup and Theme Management
- **Implemented**: Multiple themes (Light, Dark, Custom color).  
- **Implemented**: Theme switching at runtime using Options Menu.  
- **Implemented**: Selected theme persisted using SharedPreferences.  
- **Implemented**: Saved theme applied on app restart.

### Section 2: User State and Authentication
- **Implemented**: Login screen with hard-coded credentials.  
- **Implemented**: Authentication flag (`isLoggedIn`) stored in SharedPreferences.  
- **Implemented**: App checks login status on launch and redirects to HomeActivity if already logged in.  
- **Implemented**: Login state maintained during screen rotation.

### Section 3: Menu Implementation and Navigation
- **Implemented**: Options Menu for theme switching.  
- **Implemented**: Navigation between activities using Intents:  
  - Login → HomeActivity (on successful login)  
  - Login → SignupActivity (Register)  
  - Login → ForgotPasswordActivity → ResetPasswordActivity  
- **Implemented**: Clickable buttons/text links for Register and Forgot Password.  


### Section 4: Input Controls and UI Interaction
- **Implemented**: Standard input controls used (EditText, Button, TextView).  
- **Implemented**: User input validated for login.  
- **Implemented**: UI updates reflect user actions (Toast messages for success/failure).

### Section 5: Activity Lifecycle and State Management
- **Implemented**: Configuration changes handled (screen rotation).  
- **Implemented**: UI state preserved on rotation.  
- **Implemented**: No unnecessary re-fetching; login state maintained.

---

## Non-Functional Requirements
- **Implemented**: App works offline (limited to login, registration screens).  
- **Implemented**: Clean UI using Material Design principles (buttons, card layout, colors).  
- **Implemented**: Proper separation of concerns (separate activities for login, registration, forgot/reset password, and home).  
- **Implemented**: Code commented and readable.  

---

## Screenshots (Attach in submission document)
1. Login Screen  
2. HomeActivity (Landing Screen)  
3. Registration Screen  
4. Forgot / Reset Password Screens  
5. Options Menu for theme switching  

---

## Navigation Flow
