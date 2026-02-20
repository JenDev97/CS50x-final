<div align="center">

<h1>🔐 CS50x Final Project</h1>

<p><strong>Final Project for CS50x</strong></p>

<p>
To view the live preview, please click on the
<strong>“Password Generator”</strong> link below 👇
</p>

<a href="https://jendev97.github.io/CS50x-final/" target="_blank" style="
display: inline-block;
padding: 12px 24px;
margin-top: 10px;
background-color: #0d6efd;
color: white;
text-decoration: none;
border-radius: 6px;
font-weight: bold;
">
Password Generator
</a>

<br><br>

<p><strong>🎥 Demo Video</strong></p>

<a href="https://youtube.com/shorts/MeAQSTwcIdM?feature=share" target="_blank" style="
color: #0d6efd;
font-weight: bold;
text-decoration: none;
">
Click here to watch the demo video
</a>

</div>

<br>

<hr style="border-top: 2px dotted #999;">

<div align="center">
<h2>📄 Project Overview</h2>
</div>

<p style="font-size: 16px; line-height: 1.8;">
This project is a customizable <strong>Password Generator</strong> built as my final submission for CS50x.
The purpose of this web application is to allow users to generate secure,
random passwords based on specific criteria selected by the user.
</p>

<p style="font-size: 16px; line-height: 1.8;">
The application was developed using <strong>HTML, CSS, and JavaScript</strong>,
focusing on DOM manipulation, input validation, conditional logic,
and algorithmic random generation.
</p>

<hr style="border-top: 1px solid #ddd;">

<div align="center">
<h2>⚙️ Page Functionality</h2>
</div>

<p style="font-size: 16px; line-height: 1.8;">
This password generator allows users to fully customize the characteristics
of the password before generating it. The system dynamically builds a character
pool depending on the selected options and ensures that all validation
rules are satisfied before producing the final result.
</p>

<hr style="border-top: 1px dashed #ccc;">

<div align="center">
<h2>✨ Features</h2>
</div>

<ul style="font-size: 16px; line-height: 1.8;">
  <li>Select a password length between <strong>4 and 32 characters</strong></li>
  <li>Choose between uppercase, lowercase, numbers, and symbols</li>
  <li>Generate a password instantly based on selected criteria</li>
  <li>Validation system to prevent invalid inputs</li>
  <li>Dynamic character pool creation</li>
</ul>

<hr style="border-top: 1px dashed #ccc;">

<div align="center">
<h2>🔐 Password Requirements</h2>
</div>

<ul style="font-size: 16px; line-height: 1.8;">
  <li>The length must be between <strong>4 and 32</strong> characters</li>
  <li>At least <strong>one character type</strong> must be selected:</li>
</ul>

<ul style="font-size: 16px; line-height: 1.8; margin-left: 40px;">
  <li>Uppercase letters (A–Z)</li>
  <li>Lowercase letters (a–z)</li>
  <li>Numbers (0–9)</li>
  <li>Symbols (!@#$%^&* etc.)</li>
</ul>

<p style="font-size: 16px; line-height: 1.8;">
If no character type is selected, the generator will prevent execution.
This avoids creating an empty character pool and prevents runtime errors.
</p>

<hr style="border-top: 1px solid #ddd;">

<div align="center">
<h2>🧠 Technical Implementation</h2>
</div>

<h3>HTML Structure</h3>

<p style="font-size: 16px; line-height: 1.8;">
The HTML provides the structural foundation of the application.
It includes an input field for password length, checkboxes for character
type selection, a generation button, and an output field where
the generated password is displayed.
</p>

<h3>CSS Styling</h3>

<p style="font-size: 16px; line-height: 1.8;">
The design follows a clean and minimal approach. The layout is centered,
the button includes hover effects, and visual contrast ensures readability.
The styling prioritizes usability and clarity over visual complexity.
</p>

<h3>JavaScript Logic</h3>

<p style="font-size: 16px; line-height: 1.8;">
JavaScript handles the core logic of the application. When the user clicks
the generate button, the script:
</p>

<ol style="font-size: 16px; line-height: 1.8;">
  <li>Retrieves the selected length and character types</li>
  <li>Validates all inputs</li>
  <li>Builds a character pool dynamically</li>
  <li>Uses <code>Math.random()</code> to select random characters</li>
  <li>Loops until the desired length is reached</li>
  <li>Displays the final password in the DOM</li>
</ol>

<p style="font-size: 16px; line-height: 1.8;">
The logic is separated into validation, pool creation,
and generation steps to maintain clean and readable code.
</p>

<hr style="border-top: 1px dashed #ccc;">

<div align="center">
<h2>⚠ Challenges Faced</h2>
</div>

<p style="font-size: 16px; line-height: 1.8;">
One of the main challenges was handling cases where no character type
was selected. This initially caused errors when attempting to randomly
select from an empty string.
</p>

<p style="font-size: 16px; line-height: 1.8;">
The solution was to implement a validation condition that prevents
generation until at least one checkbox is selected.
</p>

<p style="font-size: 16px; line-height: 1.8;">
Another challenge involved ensuring consistent random distribution.
Each character is independently selected using <code>Math.random()</code>
from the dynamically generated pool.
</p>

<hr style="border-top: 1px solid #ddd;">

<div align="center">
<h2>🔐 Security Considerations</h2>
</div>

<p style="font-size: 16px; line-height: 1.8;">
This project uses <code>Math.random()</code> for password generation.
While suitable for educational purposes, production-grade applications
should use <code>crypto.getRandomValues()</code> for cryptographic security.
</p>

<hr style="border-top: 1px dashed #ccc;">

<div align="center">
<h2>🚀 Future Improvements</h2>
</div>

<ul style="font-size: 16px; line-height: 1.8;">
  <li>Copy-to-clipboard functionality</li>
  <li>Password strength indicator</li>
  <li>Toggle password visibility</li>
  <li>Dark/light mode</li>
  <li>Mobile optimization</li>
  <li>Use of secure cryptographic randomness</li>
</ul>

<hr style="border-top: 2px dotted #999;">

<div align="center">
<h2>🏁 Conclusion</h2>

<p style="font-size: 16px; line-height: 1.8;">
This Password Generator is a complete front-end web application that integrates
user input handling, validation logic, algorithmic random generation,
and dynamic DOM manipulation.
</p>

<p style="font-size: 16px; line-height: 1.8;">
Despite its simple interface, it demonstrates core programming concepts
learned throughout CS50x and reflects the ability to design,
implement, and debug an interactive web application from scratch.
</p>

<br>

<em>Built with HTML, CSS, and JavaScript</em>

</div>
