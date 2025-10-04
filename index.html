<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>DANSH Grading System</title>
  
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html, body {
      height: 100%;
      width: 100%;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #87CEEB 0%, #FFD700 100%);
    }

    .container {
      display: none;
      height: 100vh;
    }

    .container.active {
      display: flex;
      flex-direction: column;
    }

    #auth-container {
      justify-content: center;
      align-items: center;
      padding: 20px;
    }

    .auth-form {
      display: none;
      background: white;
      padding: 40px;
      border-radius: 15px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.2);
      max-width: 500px;
      width: 100%;
      animation: fadeIn 0.3s ease;
    }

    .auth-form.active {
      display: block;
    }

    .auth-form h1 {
      color: #2196F3;
      text-align: center;
      margin-bottom: 10px;
      font-size: 28px;
    }

    .auth-form h2 {
      color: #333;
      text-align: center;
      margin-bottom: 30px;
      font-size: 22px;
    }

    .form-group {
      margin-bottom: 20px;
    }

    .form-row {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 15px;
    }

    .form-group label {
      display: block;
      margin-bottom: 8px;
      color: #555;
      font-weight: 500;
    }

    .form-group input,
    .form-group select,
    .form-group textarea {
      width: 100%;
      padding: 12px;
      border: 2px solid #ddd;
      border-radius: 8px;
      font-size: 14px;
      transition: border-color 0.3s;
    }

    .form-group input:focus,
    .form-group select:focus,
    .form-group textarea:focus {
      outline: none;
      border-color: #2196F3;
    }

    .password-input {
      position: relative;
    }

    .toggle-password {
      position: absolute;
      right: 10px;
      top: 50%;
      transform: translateY(-50%);
      background: none;
      border: none;
      cursor: pointer;
      font-size: 18px;
      padding: 5px;
    }

    .password-strength {
      margin-top: 5px;
      font-size: 12px;
      font-weight: 500;
    }

    .password-strength.weak { color: #f44336; }
    .password-strength.medium { color: #ff9800; }
    .password-strength.strong { color: #4caf50; }

    .checkbox-label {
      display: flex;
      align-items: center;
      cursor: pointer;
      font-weight: normal;
    }

    .checkbox-label input {
      margin-right: 8px;
      width: auto;
    }

    .btn-primary {
      width: 100%;
      padding: 14px;
      background: #2196F3;
      color: white;
      border: none;
      border-radius: 8px;
      font-size: 16px;
      font-weight: 600;
      cursor: pointer;
      transition: background 0.3s;
    }

    .btn-primary:hover {
      background: #1976D2;
    }

    .btn-secondary {
      padding: 10px 20px;
      background: #757575;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      margin-left: 10px;
    }

    .btn-secondary:hover {
      background: #616161;
    }

    .toggle-form {
      text-align: center;
      margin-top: 20px;
      color: #666;
    }

    .toggle-form a {
      color: #2196F3;
      text-decoration: none;
      font-weight: 600;
    }

    .toggle-form a:hover {
      text-decoration: underline;
    }

    #dashboard-container {
      position: relative;
    }

    .header {
      background: linear-gradient(135deg, #2196F3, #1976D2);
      color: white;
      padding: 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }

    .hamburger {
      background: none;
      border: none;
      color: white;
      font-size: 28px;
      cursor: pointer;
      padding: 5px 10px;
      display: none;
    }

    .header h1 {
      font-size: 20px;
      flex: 1;
      text-align: center;
    }

    .btn-logout {
      background: #f44336;
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 8px;
      cursor: pointer;
      font-weight: 600;
    }

    .btn-logout:hover {
      background: #d32f2f;
    }

    .sidebar {
      position: fixed;
      left: 0;
      top: 60px;
      width: 250px;
      height: calc(100vh - 60px);
      background: white;
      box-shadow: 2px 0 10px rgba(0,0,0,0.1);
      z-index: 100;
      transition: transform 0.3s ease;
    }

    .sidebar-content {
      padding: 20px;
    }

    .sidebar h3 {
      color: #2196F3;
      margin-bottom: 20px;
    }

    .nav-menu {
      display: flex;
      flex-direction: column;
      gap: 10px;
    }

    .nav-menu a {
      padding: 12px 15px;
      color: #333;
      text-decoration: none;
      border-radius: 8px;
      transition: background 0.3s;
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .nav-menu a:hover {
      background: #e3f2fd;
      color: #2196F3;
    }

    .main-content {
      margin-left: 250px;
      padding: 30px;
      min-height: calc(100vh - 60px);
    }

    .panel {
      display: none;
      animation: fadeIn 0.3s ease;
    }

    .panel.active {
      display: block;
    }

    .panel-header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 20px;
    }

    .panel-header h2 {
      color: #2196F3;
      font-size: 28px;
    }

    .zoom-buttons {
      display: flex;
      gap: 10px;
    }

    .btn-zoom {
      background: transparent;
      border: none;
      font-size: 24px;
      cursor: pointer;
      padding: 5px;
      position: absolute;
      top: 10px;
      right: 10px;
      z-index: 100;
    }

    .btn-zoom-out {
      background: transparent;
      border: none;
      font-size: 24px;
      cursor: pointer;
      padding: 5px;
      position: absolute;
      top: 10px;
      right: 10px;
      z-index: 1001;
      display: none;
    }

    .table-container.zoomed .btn-zoom {
      display: none;
    }

    .table-container.zoomed .btn-zoom-out {
      display: block;
    }

    .sidebar.active ~ .main-content .btn-zoom,
    .sidebar.active ~ .main-content .btn-zoom-out {
      display: none;
    }

    .search-container {
      margin-bottom: 20px;
    }

    .search-container input {
      width: 100%;
      max-width: 400px;
      padding: 12px;
      border: 2px solid #ddd;
      border-radius: 8px;
      font-size: 14px;
    }

    .table-container {
      background: white;
      border-radius: 10px;
      overflow: auto;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      transition: all 0.3s ease;
      position: relative;
    }

    .table-container.zoomed {
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      width: 95vw;
      height: 90vh;
      z-index: 1000;
      max-width: none;
    }

    table {
      width: 100%;
      border-collapse: collapse;
    }

    thead {
      background: linear-gradient(135deg, #2196F3, #1976D2);
      color: white;
      position: sticky;
      top: 0;
      z-index: 10;
    }

    th {
      padding: 15px;
      text-align: left;
      font-weight: 600;
    }

    tbody tr {
      border-bottom: 1px solid #eee;
      transition: background 0.2s;
    }

    tbody tr:hover {
      background: #f5f5f5;
    }

    td {
      padding: 15px;
    }

    .status-passed {
      color: #4caf50;
      font-weight: 600;
    }

    .status-failed {
      color: #f44336;
      font-weight: 600;
    }

    .btn-edit,
    .btn-delete {
      padding: 6px 12px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      margin-right: 5px;
      font-size: 12px;
      font-weight: 600;
    }

    .btn-edit {
      background: #2196F3;
      color: white;
    }

    .btn-edit:hover {
      background: #1976D2;
    }

    .btn-delete {
      background: #f44336;
      color: white;
    }

    .btn-delete:hover {
      background: #d32f2f;
    }

    .profile-form,
    .grade-form,
    .admin-form {
      background: white;
      padding: 30px;
      border-radius: 10px;
      max-width: 600px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }

    .form-actions {
      display: flex;
      align-items: center;
      margin-top: 20px;
    }

    .loading-overlay {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0,0,0,0.5);
      display: none;
      justify-content: center;
      align-items: center;
      z-index: 9999;
    }

    .loading-overlay.active {
      display: flex;
    }

    .spinner {
      width: 50px;
      height: 50px;
      border: 5px solid #f3f3f3;
      border-top: 5px solid #2196F3;
      border-radius: 50%;
      animation: spin 1s linear infinite;
    }

    @keyframes spin {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    .alert {
      position: fixed;
      top: 20px;
      right: 20px;
      padding: 15px 20px;
      border-radius: 8px;
      color: white;
      font-weight: 600;
      z-index: 10000;
      opacity: 0;
      transform: translateX(100px);
      transition: all 0.3s ease;
    }

    .alert.show {
      opacity: 1;
      transform: translateX(0);
    }

    .alert-success {
      background: #4caf50;
    }

    .alert-error {
      background: #f44336;
    }

    @media (max-width: 768px) {
      .hamburger {
        display: block;
      }

      .sidebar {
        transform: translateX(-100%);
      }

      .sidebar.active {
        transform: translateX(0);
      }

      .main-content {
        margin-left: 0;
        padding: 15px;
      }

      .header h1 {
        font-size: 14px;
      }

      .form-row {
        grid-template-columns: 1fr;
      }

      .auth-form {
        padding: 25px;
      }

      table {
        font-size: 12px;
      }

      th, td {
        padding: 8px;
      }

      .panel-header {
        flex-direction: column;
        gap: 10px;
        align-items: flex-start;
      }

      .zoom-buttons {
        flex-direction: column;
        width: 100%;
      }

      .btn-zoom,
      .btn-zoom-out {
        width: 100%;
      }
    }

    @media (max-width: 480px) {
      .header h1 {
        font-size: 12px;
      }

      .btn-logout {
        padding: 8px 12px;
        font-size: 12px;
      }
    }
  </style>
  </head>
<body>

    <div id="auth-container" class="container active">
    <div id="login-form" class="auth-form active">
      <h1>DANSH Grading System</h1>
      <h2>Login</h2>
      <form id="loginForm">
        <div class="form-group">
          <label>Email</label>
          <input type="email" id="login-email" required>
        </div>
        <div class="form-group">
          <label>Password</label>
          <div class="password-input">
            <input type="password" id="login-password" required>
            <button type="button" class="toggle-password" onclick="togglePassword('login-password')">👁️</button>
          </div>
        </div>
        <div class="form-group">
          <label class="checkbox-label">
            <input type="checkbox" id="remember-me">
            Remember Me
          </label>
        </div>
        <button type="submit" class="btn-primary">Login</button>
        <p class="toggle-form">Don't have an account? <a href="#" onclick="toggleAuthForm()">Sign Up</a></p>
      </form>
    </div>

    <div id="signup-form" class="auth-form">
      <h1>DANSH Grading System</h1>
      <h2>Student Sign Up</h2>
      <form id="signupForm">
        <div class="form-group">
          <label>Full Name *</label>
          <input type="text" id="signup-fullname" required>
        </div>
        <div class="form-group">
          <label>Email *</label>
          <input type="email" id="signup-email" required>
        </div>
        <div class="form-group">
          <label>Verification Code *</label>
          <div style="display: flex; gap: 10px;">
            <input type="text" id="signup-verification-code" required style="flex: 1;">
            <button type="button" class="btn-secondary" onclick="sendVerificationCode()" style="margin: 0; width: auto; white-space: nowrap;">Get Code</button>
          </div>
        </div>
        <div class="form-group">
          <label>Password *</label>
          <div class="password-input">
            <input type="password" id="signup-password" required minlength="6">
            <button type="button" class="toggle-password" onclick="togglePassword('signup-password')">👁️</button>
          </div>
          <div class="password-strength" id="password-strength"></div>
        </div>
        <div class="form-group">
          <label>Confirm Password *</label>
          <div class="password-input">
            <input type="password" id="signup-confirm-password" required minlength="6">
            <button type="button" class="toggle-password" onclick="togglePassword('signup-confirm-password')">👁️</button>
          </div>
        </div>
        <div class="form-row">
          <div class="form-group">
            <label>Grade Level *</label>
            <select id="signup-grade" required>
              <option value="">Select Grade</option>
              <option value="7">Grade 7</option>
              <option value="8">Grade 8</option>
              <option value="9">Grade 9</option>
              <option value="10">Grade 10</option>
              <option value="11">Grade 11</option>
              <option value="12">Grade 12</option>
            </select>
          </div>
          <div class="form-group">
            <label>Section *</label>
            <select id="signup-section" required>
              <option value="">Select Section</option>
              <option value="A">A</option>
              <option value="B">B</option>
              <option value="C">C</option>
              <option value="D">D</option>
            </select>
          </div>
        </div>
        <div class="form-group">
          <label>Parent/Guardian Name *</label>
          <input type="text" id="signup-parent-name" required>
        </div>
        <div class="form-group">
          <label>Parent/Guardian Phone Number *</label>
          <input type="tel" id="signup-parent-phone" required>
        </div>
        <div class="form-group">
          <label>Student's Address *</label>
          <textarea id="signup-address" required rows="3"></textarea>
        </div>
        <button type="submit" class="btn-primary">Sign Up</button>
        <p class="toggle-form">Already have an account? <a href="#" onclick="toggleAuthForm()">Login</a></p>
      </form>
    </div>
  </div>

  <div id="dashboard-container" class="container">
    <header class="header">
      <button class="hamburger" onclick="toggleSidebar()">☰</button>
      <h1 id="welcome-message">WELCOME TO DANSH GRADING SYSTEM</h1>
    </header>

    <aside id="sidebar" class="sidebar">
      <div class="sidebar-content">
        <h3>Navigation</h3>
        <nav id="student-nav" class="nav-menu">
          <a href="#" onclick="showPanel('grades')">📊 Grades</a>
          <a href="#" onclick="showPanel('profile')">👤 Profile</a>
          <a href="#" onclick="logout()">🚪 Logout</a>
        </nav>
        <nav id="admin-nav" class="nav-menu" style="display:none;">
          <a href="#" onclick="showPanel('grades')">📊 Grades List</a>
          <a href="#" onclick="showPanel('users')">👥 User List</a>
          <a href="#" onclick="showPanel('profile')">👤 Profile</a>
          <a href="#" onclick="showPanel('add-grades')">➕ Add Grades</a>
          <a href="#" onclick="showPanel('add-admin')">👨‍💼 Add Admin Account</a>
          <a href="#" onclick="showPanel('delete-users')">🗑️ Delete Members</a>
          <a href="#" onclick="logout()">🚪 Logout</a>
        </nav>
      </div>
    </aside>

    <main class="main-content">

            <div id="grades-panel" class="panel active">
        <div class="panel-header">
          <h2>Grades</h2>
        </div>
        
        <h3 style="color: #2196F3; margin-top: 20px; margin-bottom: 10px;">QUARTER 1</h3>
        <div id="grades-table-q1-container" class="table-container">
          <button class="btn-zoom" onclick="zoomIn('grades-table-q1-container')">🔍</button>
          <button class="btn-zoom-out" onclick="zoomOut('grades-table-q1-container')">🔍</button>
          <table id="grades-table-q1">
            <thead>
              <tr>
                <th>Student Name</th>
                <th>Level</th>
                <th>Section</th>
                <th>Subject</th>
                <th>Grade</th>
                <th>Status</th>
                <th class="admin-only" style="display:none;">Actions</th>
              </tr>
            </thead>
            <tbody id="grades-tbody-q1">
              <tr><td colspan="7">Loading...</td></tr>
            </tbody>
          </table>
        </div>

        <h3 style="color: #2196F3; margin-top: 20px; margin-bottom: 10px;">QUARTER 2</h3>
        <div id="grades-table-q2-container" class="table-container">
          <button class="btn-zoom" onclick="zoomIn('grades-table-q2-container')">🔍</button>
          <button class="btn-zoom-out" onclick="zoomOut('grades-table-q2-container')">🔍</button>
          <table id="grades-table-q2">
            <thead>
              <tr>
                <th>Student Name</th>
                <th>Level</th>
                <th>Section</th>
                <th>Subject</th>
                <th>Grade</th>
                <th>Status</th>
                <th class="admin-only" style="display:none;">Actions</th>
              </tr>
            </thead>
            <tbody id="grades-tbody-q2">
              <tr><td colspan="7">Loading...</td></tr>
            </tbody >
          </table>
        </div>

        <h3 style="color: #2196F3; margin-top: 20px; margin-bottom: 10px;">QUARTER 3</h3>
        <div id="grades-table-q3-container" class="table-container">
          <button class="btn-zoom" onclick="zoomIn('grades-table-q3-container')">🔍</button>
          <button class="btn-zoom-out" onclick="zoomOut('grades-table-q3-container')">🔍</button>
          <table id="grades-table-q3">
            <thead>
              <tr>
                <th>Student Name</th>
                <th>Level</th>
                <th>Section</th>
                <th>Subject</th>
                <th>Grade</th>
                <th>Status</th>
                <th class="admin-only" style="display:none;">Actions</th>
              </tr >
            </thead>
            <tbody id="grades-tbody-q3">
              <tr><td colspan="7">Loading...</td></tr>
            </tbody>
          </table>
        </div>

        <h3 style="color: #2196F3; margin-top: 20px; margin-bottom: 10px;">QUARTER 4</h3>
        <div id="grades-table-q4-container" class="table-container">
          <button class="btn-zoom" onclick="zoomIn('grades-table-q4-container')">🔍</button>
          <button class="btn-zoom-out" onclick="zoomOut('grades-table-q4-container')">🔍</button>
          <table id="grades-table-q4">
            <thead>
              <tr>
                <th>Student Name</th>
                <th>Level</th>
                <th>Section</th>
                <th>Subject</th>
                <th>Grade</th>
                <th>Status</th>
                <th class="admin-only" style="display:none;">Actions</th>
              </tr>
            </thead>
            <tbody id="grades-tbody-q4">
              <tr><td colspan="7">Loading...</td></tr>
            </tbody>
          </table>
        </div>
      </div>

      <div id="users-panel" class="panel">
        <div class="panel-header">
          <h2>User Management</h2>
        </div>
        <div class="search-container">
          <input type="text" id="user-search" placeholder="Search users..." oninput="filterUsers()">
        </div>
        <div id="users-table-container" class="table-container">
          <button class="btn-zoom" onclick="zoomIn('users-table-container')">🔍</button>
          <button class="btn-zoom-out" onclick="zoomOut('users-table-container')">🔍</button>
          <table id="users-table">
            <thead>
              <tr>
                <th>Name</th>
                <th>Email</th>
                <th>Level</th>
                <th>Section</th>
                <th>Role</th>
              </tr>
            </thead>
            <tbody id="users-tbody">
              <tr><td colspan="5">Loading...</td></tr>
            </tbody>
          </table>
        </div>
      </div>

      <div id="profile-panel" class="panel">
        <div class="panel-header">
          <h2>Profile</h2>
        </div>
        <form id="profile-form" class="profile-form">
          <div class="form-group">
            <label>Full Name</label>
            <input type="text" id="profile-fullname" required>
          </div>
          <div class="form-group">
            <label>Mobile Number</label>
            <input type="tel" id="profile-mobile">
          </div>
          <div class="form-group">
            <label>Purok</label>
            <input type="text" id="profile-purok">
          </div>
          <div class="form-group">
            <label>Address</label>
            <textarea id="profile-address" rows="3"></textarea>
          </div>
          <div class="form-group">
            <label>Parent/Guardian Name</label>
            <input type="text" id="profile-parent-name">
          </div>
          <div class="form-group">
            <label>Parent/Guardian Phone</label>
            <input type="tel" id="profile-parent-phone">
          </div>
          <button type="submit" class="btn-primary">Update Profile</button>
        </form>
      </div>

      <div id="add-grades-panel" class="panel">
        <div class="panel-header">
          <h2>Add/Edit Grades</h2>
        </div>
        <form id="add-grade-form" class="grade-form">
          <input type="hidden" id="edit-grade-id">
          <div class="form-group">
            <label>Select Student</label>
            <select id="grade-student" required>
              <option value="">Select Student</option>
            </select>
          </div>
          <div class="form-group">
            <label>Quarter</label>
            <select id="grade-quarter" required>
              <option value="">Select Quarter</option>
              <option value="1">Quarter 1</option>
              <option value="2">Quarter 2</option>
              <option value="3">Quarter 3</option>
              <option value="4">Quarter 4</option>
            </select>
          </div>
          <div class="form-group">
            <label>Subject</label>
            <input type="text" id="grade-subject" required>
          </div>
          <div class="form-group">
            <label>Grade (0-100)</label>
            <input type="number" id="grade-value" min="0" max="100" required>
          </div>
          <div class="form-actions">
            <button type="submit" class="btn-primary">Save Grade</button>
            <button type="button" class="btn-secondary" onclick="cancelEditGrade()">Cancel</button>
          </div>
        </form>
      </div>

      <div id="add-admin-panel" class="panel">
        <div class="panel-header">
          <h2>Create Admin Account</h2>
        </div>
        <form id="add-admin-form" class="admin-form">
          <div class="form-group">
            <label>Admin Email</label>
            <input type="email" id="admin-email" required>
          </div>
          <div class="form-group">
            <label>Password</label>
            <div class="password-input">
              <input type="password" id="admin-password" required minlength="6">
              <button type="button" class="toggle-password" onclick="togglePassword('admin-password')">👁️</button>
            </div>
            <div class="password-strength" id="admin-password-strength"></div>
          </div>
          <div class="form-group">
            <label>Full Name</label>
            <input type="text" id="admin-fullname" required>
          </div>
          <button type="submit" class="btn-primary">Create Admin</button>
        </form>
      </div>

      <div id="delete-users-panel" class="panel">
        <div class="panel-header">
          <h2>Delete Members</h2>
          <div class="zoom-buttons">
            <button class="btn-zoom" onclick="zoomIn('delete-users-table-container')">🔍 Zoom In</button>
            <button class="btn-zoom-out" onclick="zoomOut('delete-users-table-container')" style="display:none;">↩️ Zoom Out</button>
          </div>
        </div>
        <div id="delete-users-table-container" class="table-container">
          <table id="delete-users-table">
            <thead>
              <tr>
                <th>Name</th>
                <th>Email</th>
                <th>Role</th>
                <th>Actions</th>
              </tr>
            </thead>
            <tbody id="delete-users-tbody">
              <tr><td colspan="4">Loading...</td></tr>
            </tbody>
          </table>
        </div>
      </div>
    </main>
  </div>

  <div id="loading-overlay" class="loading-overlay">
    <div class="spinner"></div>
  </div>

  <script src="https://www.gstatic.com/firebasejs/10.7.1/firebase-app-compat.js"></script>
  <script src="https://www.gstatic.com/firebasejs/10.7.1/firebase-auth-compat.js"></script>
  <script src="https://www.gstatic.com/firebasejs/10.7.1/firebase-firestore-compat.js"></script>
  
  <script>

        // --- UPDATED FIREBASE CONFIGURATION (Remains the same as per user's input) ---
    const firebaseConfig = {
      apiKey: "AIzaSyCYPONQgJC33Lp2OmMyKw4hssDStEwvPlQ",
      authDomain: "test-9c727.firebaseapp.com",
      projectId: "test-9c727",
      storageBucket: "test-9c727.firebasestorage.app",
      messagingSenderId: "198578631587",
      appId: "1:198578631587:web:c0831122f964d46149e016"
    };

    firebase.initializeApp(firebaseConfig);
    const auth = firebase.auth();
    const db = firebase.firestore();

    let currentUser = null;
    let currentUserProfile = null;
    let secondaryApp = null;

    auth.onAuthStateChanged(async (user) => {
      if (user) {
        currentUser = user;
        await loadUserProfile();
        showDashboard();
      } else {
        showAuth();
      }
    });

    async function loadUserProfile() {
      try {
        const doc = await db.collection('profiles').doc(currentUser.uid).get();
        if (doc.exists) {
          currentUserProfile = { id: doc.id, ...doc.data() };
          updateWelcomeMessage();
          if (currentUserProfile.role === 'admin') {
            showAdminNav();
          } else {
            showStudentNav();
          }
        }
      } catch (error) {
        console.error('Error loading profile:', error);
      }
    }

    function updateWelcomeMessage() {
      const welcomeMsg = document.getElementById('welcome-message');
      if (currentUserProfile) {
        const role = currentUserProfile.role === 'admin' ? 'ADMIN' : 'STUDENT';
        welcomeMsg.textContent = `WELCOME TO DANSH GRADING SYSTEM – ${currentUserProfile.fullName.toUpperCase()} / ${role}`;
      }
    }

    function showAuth() {
      document.getElementById('auth-container').classList.add('active');
      document.getElementById('dashboard-container').classList.remove('active');
      hideLoading();
    }

    function showDashboard() {
      document.getElementById('auth-container').classList.remove('active');
      document.getElementById('dashboard-container').classList.add('active');
      showPanel('grades');
      hideLoading();
    }

    function showAdminNav() {
      document.getElementById('student-nav').style.display = 'none';
      document.getElementById('admin-nav').style.display = 'block';
      document.querySelectorAll('.admin-only').forEach(el => el.style.display = '');
    }

    function showStudentNav() {
      document.getElementById('student-nav').style.display = 'block';
      document.getElementById('admin-nav').style.display = 'none';
      document.querySelectorAll('.admin-only').forEach(el => el.style.display = 'none');
    }

    function toggleAuthForm() {
      const loginForm = document.getElementById('login-form');
      const signupForm = document.getElementById('signup-form');
      loginForm.classList.toggle('active');
      signupForm.classList.toggle('active');
    }

    function togglePassword(inputId) {
      const input = document.getElementById(inputId);
      input.type = input.type === 'password' ? 'text' : 'password';
    }

    function checkPasswordStrength(password) {
      let strength = 'weak';
      if (password.length >= 8) {
        if (/[A-Z]/.test(password) && /[0-9]/.test(password) && /[^A-Za-z0-9]/.test(password)) {
          strength = 'strong';
        } else if (/[A-Z]/.test(password) || /[0-9]/.test(password)) {
          strength = 'medium';
        }
      }
      return strength;
    }

    document.getElementById('signup-password').addEventListener('input', (e) => {
      const strength = checkPasswordStrength(e.target.value);
      const strengthEl = document.getElementById('password-strength');
      strengthEl.textContent = `Password strength: ${strength}`;
      strengthEl.className = 'password-strength ' + strength;
    });

    document.getElementById('admin-password').addEventListener('input', (e) => {
      const strength = checkPasswordStrength(e.target.value);
      const strengthEl = document.getElementById('admin-password-strength');
      strengthEl.textContent = `Password strength: ${strength}`;
      strengthEl.className = 'password-strength ' + strength;
    });

    document.getElementById('loginForm').addEventListener('submit', async (e) => {
      e.preventDefault();
      const email = document.getElementById('login-email').value;
      const password = document.getElementById('login-password').value;
      const rememberMe = document.getElementById('remember-me').checked;
      
      showLoading();
      try {
        const persistence = rememberMe ? firebase.auth.Auth.Persistence.LOCAL : firebase.auth.Auth.Persistence.SESSION;
        await auth.setPersistence(persistence);
        await auth.signInWithEmailAndPassword(email, password);
        showAlert('Login successful!', 'success');
      } catch (error) {
        hideLoading();
        showAlert(error.message, 'error');
      }
    });

    document.getElementById('signupForm').addEventListener('submit', async (e) => {
      e.preventDefault();
      
      const verificationCode = document.getElementById('signup-verification-code').value;
      
      if (!window.currentVerificationCode) {
        showAlert('Please get a verification code first!', 'error');
        return;
      }
      
      if (verificationCode !== window.currentVerificationCode) {
        showAlert('Invalid verification code!', 'error');
        return;
      }
      
      const password = document.getElementById('signup-password').value;
      const confirmPassword = document.getElementById('signup-confirm-password').value;
      
      if (password !== confirmPassword) {
        showAlert('Passwords do not match!', 'error');
        return;
      }
      
      const userData = {
        email: document.getElementById('signup-email').value,
        fullName: document.getElementById('signup-fullname').value,
        gradeLevel: document.getElementById('signup-grade').value,
        section: document.getElementById('signup-section').value,
        parentName: document.getElementById('signup-parent-name').value,
        parentPhone: document.getElementById('signup-parent-phone').value,
        address: document.getElementById('signup-address').value,
        role: 'student'
      };
      
      showLoading();
      try {
        const userCredential = await auth.createUserWithEmailAndPassword(userData.email, password);
        await db.collection('profiles').doc(userCredential.user.uid).set(userData);
        window.currentVerificationCode = null;
        showAlert('Account created successfully!', 'success');
      } catch (error) {
        hideLoading();
        showAlert(error.message, 'error');
      }
    });

    document.getElementById('profile-form').addEventListener('submit', async (e) => {
      e.preventDefault();
      
      const profileData = {
        fullName: document.getElementById('profile-fullname').value,
        mobile: document.getElementById('profile-mobile').value,
        purok: document.getElementById('profile-purok').value,
        address: document.getElementById('profile-address').value,
        parentName: document.getElementById('profile-parent-name').value,
        parentPhone: document.getElementById('profile-parent-phone').value
      };
      
      showLoading();
      try {
        await db.collection('profiles').doc(currentUser.uid).update(profileData);
        currentUserProfile = { ...currentUserProfile, ...profileData };
        updateWelcomeMessage();
        await loadGrades();
        showAlert('Profile updated successfully!', 'success');
        hideLoading();
      } catch (error) {
        hideLoading();
        showAlert(error.message, 'error');
      }
    });

    document.getElementById('add-grade-form').addEventListener('submit', async (e) => {
      e.preventDefault();
      
      const studentId = document.getElementById('grade-student').value;
      const quarter = document.getElementById('grade-quarter').value;
      const subject = document.getElementById('grade-subject').value;
      const grade = parseInt(document.getElementById('grade-value').value);
      const editId = document.getElementById('edit-grade-id').value;
      
      if (grade < 0 || grade > 100) {
        showAlert('Grade must be between 0 and 100!', 'error');
        return;
      }
      
      const studentDoc = await db.collection('profiles').doc(studentId).get();
      const studentData = studentDoc.data();
      
      const gradeData = {
        studentId,
        studentName: studentData.fullName,
        gradeLevel: studentData.gradeLevel,
        section: studentData.section,
        quarter: quarter,
        subject,
        grade,
        status: grade >= 75 ? 'Passed' : 'Failed'
      };
      
      showLoading();
      try {
        if (editId) {
          await db.collection('grades').doc(editId).update(gradeData);
          showAlert('Grade updated successfully!', 'success');
        } else {
          await db.collection('grades').add(gradeData);
          showAlert('Grade added successfully!', 'success');
        }
        document.getElementById('add-grade-form').reset();
        document.getElementById('edit-grade-id').value = '';
        await loadGrades();
        hideLoading();
      } catch (error) {
        hideLoading();
        showAlert(error.message, 'error');
      }
    });

    document.getElementById('add-admin-form').addEventListener('submit', async (e) => {
      e.preventDefault();
      
      const email = document.getElementById('admin-email').value;
      const password = document.getElementById('admin-password').value;
      const fullName = document.getElementById('admin-fullname').value;
      
      showLoading();
      try {
        if (!secondaryApp) {
          secondaryApp = firebase.initializeApp(firebaseConfig, 'secondary');
        }
        
        const secondaryAuth = secondaryApp.auth();
        const userCredential = await secondaryAuth.createUserWithEmailAndPassword(email, password);
        
        await db.collection('profiles').doc(userCredential.user.uid).set({
          email,
          fullName,
          role: 'admin'
        });
        
        await secondaryAuth.signOut();
        
        showAlert('Admin account created successfully!', 'success');
        document.getElementById('add-admin-form').reset();
        hideLoading();
      } catch (error) {
        hideLoading();
        showAlert(error.message, 'error');
      }
    });

    async function loadGrades() {
      for (let q = 1; q <= 4; q++) {
        const tbody = document.getElementById(`grades-tbody-q${q}`);
        tbody.innerHTML = '<tr><td colspan="7">Loading...</td></tr>';
        
        try {
          let query = db.collection('grades').where('quarter', '==', String(q));
          
          if (currentUserProfile.role === 'student') {
            query = query.where('gradeLevel', '==', currentUserProfile.gradeLevel)
                         .where('section', '==', currentUserProfile.section);
          }
          
          const snapshot = await query.get();
          
          if (snapshot.empty) {
            tbody.innerHTML = '<tr><td colspan="7">No grades found</td></tr>';
            continue;
          }
          
          tbody.innerHTML = '';
          snapshot.forEach(doc => {
            const grade = doc.data();
            const row = tbody.insertRow();
            row.innerHTML = `
              <td>${grade.studentName}</td>
              <td>Grade ${grade.gradeLevel}</td>
              <td>${grade.section}</td>
              <td>${grade.subject}</td>
              <td>${grade.grade}</td>
              <td class="${grade.status === 'Passed' ? 'status-passed' : 'status-failed'}">${grade.status}</td>
              <td class="admin-only" style="${currentUserProfile.role === 'admin' ? '' : 'display:none;'}">
                <button class="btn-edit" onclick="editGrade('${doc.id}')">Edit</button>
                <button class="btn-delete" onclick="deleteGrade('${doc.id}')">Delete</button>
              </td>
            `;
          });
        } catch (error) {
          tbody.innerHTML = '<tr><td colspan="7">Error loading grades</td></tr>';
          console.error('Error loading grades:', error);
        }
      }
    }

    async function editGrade(gradeId) {
      try {
        const doc = await db.collection('grades').doc(gradeId).get();
        const grade = doc.data();
        
        document.getElementById('edit-grade-id').value = gradeId;
        document.getElementById('grade-student').value = grade.studentId;
        document.getElementById('grade-quarter').value = grade.quarter;
        document.getElementById('grade-subject').value = grade.subject;
        document.getElementById('grade-value').value = grade.grade;
        
        showPanel('add-grades');
      } catch (error) {
        showAlert('Error loading grade for editing', 'error');
      }
    }

    async function sendVerificationCode() {
      const email = document.getElementById('signup-email').value;
      if (!email) {
        showAlert('Please enter your email address first!', 'error');
        return;
      }
      
      const verificationCode = Math.floor(100000 + Math.random() * 900000).toString();
      
      showLoading();
      try {
        const response = await fetch('https://api.resend.com/emails', {
          method: 'POST',
          headers: {
            // --- UPDATED RESEND API KEY ---
            'Authorization': 'Bearer re_DPQ3wFTq_FJPdwBB7UGJNtmA7srRQbJBZ', 
            'Content-Type': 'application/json'
          },
          body: JSON.stringify({
            // --- SENDER EMAIL (Remains the same as per user's input) ---
            from: 'danshgradingsystem@gmail.com', 
            to: email,
            subject: 'DANSH Grading System - Verification Code',
            html: `
              <div style="font-family: Arial, sans-serif; padding: 20px; max-width: 600px; margin: 0 auto;">
                <h2 style="color: #2196F3;">DANSH Grading System</h2>
                <p>Your verification code is:</p>
                <h1 style="color: #2196F3; font-size: 36px; letter-spacing: 5px;">${verificationCode}</h1>
                <p>Please enter this code in the signup form to verify your email address.</p>
                <p style="color: #666; font-size: 12px; margin-top: 30px;">If you didn't request this code, please ignore this email.</p>
              </div>
            `
          })
        });
        
        if (response.ok) {
          window.currentVerificationCode = verificationCode;
          hideLoading();
          alert('Please check your email for the verification code.');
        } else {
          hideLoading();
          showAlert('Failed to send verification code. Please try again.', 'error');
        }
      } catch (error) {
        hideLoading();
        showAlert('Error sending verification code: ' + error.message, 'error');
      }
    }

        async function deleteGrade(gradeId) {
      if (!confirm('Are you sure you want to delete this grade?')) return;
      
      showLoading();
      try {
        await db.collection('grades').doc(gradeId).delete();
        showAlert('Grade deleted successfully!', 'success');
        await loadGrades();
        hideLoading();
      } catch (error) {
        hideLoading();
        showAlert(error.message, 'error');
      }
    }

    function cancelEditGrade() {
      document.getElementById('add-grade-form').reset();
      document.getElementById('edit-grade-id').value = '';
    }

    async function loadUsers() {
      const tbody = document.getElementById('users-tbody');
      tbody.innerHTML = '<tr><td colspan="5">Loading...</td></tr>';
      
      try {
        const snapshot = await db.collection('profiles').get();
        
        if (snapshot.empty) {
          tbody.innerHTML = '<tr><td colspan="5">No users found</td></tr>';
          return;
        }
        
        tbody.innerHTML = '';
        snapshot.forEach(doc => {
          const user = doc.data();
          const row = tbody.insertRow();
          row.innerHTML = `
            <td>${user.fullName || 'N/A'}</td>
            <td>${user.email}</td>
            <td>${user.gradeLevel ? 'Grade ' + user.gradeLevel : 'N/A'}</td>
            <td>${user.section || 'N/A'}</td>
            <td>${user.role === 'admin' ? 'Admin' : 'Student'}</td>
          `;
        });
      } catch (error) {
        tbody.innerHTML = '<tr><td colspan="5">Error loading users</td></tr>';
        console.error('Error loading users:', error);
      }
    }

    async function loadDeleteUsers() {
      const tbody = document.getElementById('delete-users-tbody');
      tbody.innerHTML = '<tr><td colspan="4">Loading...</td></tr>';
      
      try {
        const snapshot = await db.collection('profiles').get();
        
        if (snapshot.empty) {
          tbody.innerHTML = '<tr><td colspan="4">No users found</td></tr>';
          return;
        }
        
        tbody.innerHTML = '';
        snapshot.forEach(doc => {
          const user = doc.data();
          if (doc.id === currentUser.uid) return;
          
          const row = tbody.insertRow();
          row.innerHTML = `
            <td>${user.fullName || 'N/A'}</td>
            <td>${user.email}</td>
            <td>${user.role === 'admin' ? 'Admin' : 'Student'}</td>
            <td>
              <button class="btn-delete" onclick="deleteUser('${doc.id}')">Delete</button>
            </td>
          `;
        });
      } catch (error) {
        tbody.innerHTML = '<tr><td colspan="4">Error loading users</td></tr>';
        console.error('Error loading users:', error);
      }
    }

    async function deleteUser(userId) {
      if (!confirm('Are you sure you want to delete this user and all their grades?')) return;
      
      showLoading();
      try {
        await db.collection('profiles').doc(userId).delete();
        
        const gradesSnapshot = await db.collection('grades').where('studentId', '==', userId).get();
        const batch = db.batch();
        gradesSnapshot.forEach(doc => {
          batch.delete(doc.ref);
        });
        await batch.commit();
        
        showAlert('User and their grades deleted successfully!', 'success');
        await loadDeleteUsers();
        await loadUsers();
        hideLoading();
      } catch (error) {
        hideLoading();
        showAlert(error.message, 'error');
      }
    }

    function filterUsers() {
      const searchTerm = document.getElementById('user-search').value.toLowerCase();
      const rows = document.querySelectorAll('#users-tbody tr');
      
      rows.forEach(row => {
        const text = row.textContent.toLowerCase();
        row.style.display = text.includes(searchTerm) ? '' : 'none';
      });
    }

    async function loadStudentsForGrades() {
      const select = document.getElementById('grade-student');
      select.innerHTML = '<option value="">Select Student</option>';
      
      try {
        const snapshot = await db.collection('profiles').where('role', '==', 'student').get();
        snapshot.forEach(doc => {
          const student = doc.data();
          const option = document.createElement('option');
          option.value = doc.id;
          option.textContent = `${student.fullName} - Grade ${student.gradeLevel}${student.section}`;
          select.appendChild(option);
        });
      } catch (error) {
        console.error('Error loading students:', error);
      }
    }

    async function loadProfileData() {
      if (!currentUserProfile) return;
      
      document.getElementById('profile-fullname').value = currentUserProfile.fullName || '';
      document.getElementById('profile-mobile').value = currentUserProfile.mobile || '';
      document.getElementById('profile-purok').value = currentUserProfile.purok || '';
      document.getElementById('profile-address').value = currentUserProfile.address || '';
      document.getElementById('profile-parent-name').value = currentUserProfile.parentName || '';
      document.getElementById('profile-parent-phone').value = currentUserProfile.parentPhone || '';
    }

    function showPanel(panelName) {
      document.querySelectorAll('.panel').forEach(panel => panel.classList.remove('active'));
      
      const panels = {
        'grades': 'grades-panel',
        'users': 'users-panel',
        'profile': 'profile-panel',
        'add-grades': 'add-grades-panel',
        'add-admin': 'add-admin-panel',
        'delete-users': 'delete-users-panel'
      };
      
      const panelId = panels[panelName];
      if (panelId) {
        const panel = document.getElementById(panelId);
        if (panel) {
          panel.classList.add('active');
          
          if (panelName === 'users') {
            loadUsers();
          } else if (panelName === 'delete-users') {
            loadDeleteUsers();
          } else if (panelName === 'profile') {
            loadProfileData();
          } else if (panelName === 'add-grades') {
            loadStudentsForGrades();
          }
        }
      }
    }

    function toggleSidebar() {
      document.getElementById('sidebar').classList.toggle('active');
    }

    function logout() {
      auth.signOut();
    }

    function zoomIn(containerId) {
      const container = document.getElementById(containerId);
      container.classList.add('zoomed');
    }

    function zoomOut(containerId) {
      const container = document.getElementById(containerId);
      container.classList.remove('zoomed');
    }

    function showLoading() {
      document.getElementById('loading-overlay').classList.add('active');
    }

    function hideLoading() {
      document.getElementById('loading-overlay').classList.remove('active');
    }

    function showAlert(message, type) {
      const alertEl = document.createElement('div');
      alertEl.textContent = message;
      alertEl.className = 'alert alert-' + type + ' show';
      document.body.appendChild(alertEl);
      
      setTimeout(() => {
        alertEl.classList.remove('show');
        setTimeout(() => {
          document.body.removeChild(alertEl);
        }, 300); // Wait for fade-out animation
      }, 3000);
    }
  </script>
</body>
</html>
