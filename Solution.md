HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Student Registration Form</title>
</head>
<body>
  <header>
    <h1>Student Registration</h1>
    <p>Complete the form below to register your student account.</p>
  </header>

  <main>
    <form action="#" method="post">
      <div>
        <label for="full-name">Full Name</label>
        <input
          type="text"
          id="full-name"
          name="fullName"
          placeholder="Enter your full name"
          required
        >
      </div>

      <div>
        <label for="email">Email</label>
        <input
          type="email"
          id="email"
          name="email"
          placeholder="student@example.com"
          required
        >
      </div>

      <div>
        <label for="password">Password</label>
        <input
          type="password"
          id="password"
          name="password"
          minlength="8"
          placeholder="Create a password (min. 8 characters)"
          required
        >
      </div>

      <div>
        <label for="phone-number">Phone Number</label>
        <input
          type="tel"
          id="phone-number"
          name="phoneNumber"
          placeholder="+91 98765 43210"
          required
        >
      </div>

      <div>
        <label for="age">Age</label>
        <input
          type="number"
          id="age"
          name="age"
          min="15"
          max="100"
          required
        >
      </div>

      <div>
        <button type="submit">Register</button>
      </div>
    </form>
  </main>

  <footer>
    <p>&copy; 2026 Student Portal</p>
  </footer>
</body>
</html>