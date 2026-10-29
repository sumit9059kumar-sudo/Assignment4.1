File: registration.html
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Registration Form</title>
    <style>
        body { font-family: Arial, sans-serif; background-color: #f4f7f6; margin: 0; padding: 20px; display: flex; justify-content: center; align-items: center; min-height: 100vh; }
        .form-container { background: #ffffff; padding: 30px; border-radius: 8px; box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1); width: 100%; max-width: 400px; }
        h2 { color: #2c3e50; text-align: center; margin-top: 0; margin-bottom: 20px; }
        .form-group { margin-bottom: 15px; }
        label { display: block; margin-bottom: 5px; font-weight: bold; color: #333; }
        input { width: 100%; padding: 10px; border: 1px solid #ccc; border-radius: 4px; box-sizing: border-box; font-size: 14px; }
        input:focus { border-color: #3498db; outline: none; }
        button { width: 100%; background-color: #3498db; color: white; padding: 12px; border: none; border-radius: 4px; font-size: 16px; font-weight: bold; cursor: pointer; margin-top: 10px; }
        button:hover { background-color: #2980b9; }
    </style>
</head>
<body>

    <div class="form-container">
        <h2>Student Registration</h2>
        
        <!-- Student Registration Form -->
        <form action="#" method="POST">
            
            <!-- Full Name Field -->
            <div class="form-group">
                <label for="fullname">Full Name:</label>
                <input type="text" id="fullname" name="fullname" placeholder="Enter your full name" required>
            </div>

            <!-- Email Field -->
            <div class="form-group">
                <label for="email">Email Address:</label>
                <input type="email" id="email" name="email" placeholder="student@example.com" required>
            </div>

            <!-- Password Field -->
            <div class="form-group">
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" placeholder="Create a password" required>
            </div>

            <!-- Phone Number Field -->
            <div class="form-group">
                <label for="phone">Phone Number:</label>
                <input type="tel" id="phone" name="phone" placeholder="123-456-7890" required>
            </div>

            <!-- Age Field -->
            <div class="form-group">
                <label for="age">Age:</label>
                <input type="number" id="age" name="age" min="5" max="100" placeholder="Enter your age" required>
            </div>

            <!-- Submit Button -->
            <button type="submit">Register</button>

        </form>
    </div>

</body>
</html>
Requirements Checklist for Submission:
File Name: Saved as registration.html.

Form Tag: Built entirely inside a <form> element.

Labels: Each input has a corresponding <label> linked via the for and id attributes for accessibility.

Input Types: Used correct types (text, email, password, tel, and number).

Attributes: Each input has unique id and meaningful name attributes, along with the required validation attribute on mandatory fields.

Submit Button: Included at the bottom of the form to submit student data.