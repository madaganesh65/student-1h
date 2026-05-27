# student-1h
<!DOCTYPE html>
<html>
<head>
    <title>Student Feedback System</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<h2>Student Feedback System</h2>
<h4>Select Details</h4>
<div class="form-box">

<label>Branch:</label>
<select id="branch">
    <option value="">Select Branch</option>
    <option value="CSE">CSE</option>
    <option value="ECE">ECE</option>
    <option value="IOT">IOT</option>
    <option value="CYBER">CYBER</option>
    <option value="EEE">EEE</option>
    <option value="MECH">MECH</option>
</select>

<br><br>

<label>Section:</label>
<select id="section">
    <option value="">Select Section</option>
    <option value="A">A</option>
    <option value="B">B</option>
    <option value="C">C</option>
</select>

<hr>

<div class="subject-container">

<div class="subject-box">
<h3>Compiler Design</h3>
<select class="rating">
<option value="">Select Rating</option>
<option value="5">5 EXCELLENT</option>
<option value="4">4 GOOD</option>
<option value="3">3 AVERAGE</option>
<option value="2">2 POOR</option>
<option value="1">1 VERY POOR</option>
</select>
</div>

<div class="subject-box">
<h3>Cloud Computing</h3>
<select class="rating">
<option value="">Select Rating</option>
<option value="5">5 EXCELLENT</option>
<option value="4">4 GOOD</option>
<option value="3">3 AVERAGE</option>
<option value="2">2 POOR</option>
<option value="1">1 VERY POOR</option>
</select>
</div>

<div class="subject-box">
<h3>Cryptography & Network Security</h3>
<select class="rating">
<option value="">Select Rating</option>
<option value="5">5 EXCELLENT</option>
<option value="4">4 GOOD</option>
<option value="3">3 AVERAGE</option>
<option value="2">2 POOR</option>
<option value="1">1 VERY POOR</option>
</select>
</div>

<div class="subject-box">
<h3>Natural Language Processing</h3>
<select class="rating">
<option value="">Select Rating</option>
<option value="5">5 EXCELLENT</option>
<option value="4">4 GOOD</option>
<option value="3">3 AVERAGE</option>
<option value="2">2 POOR</option>
<option value="1">1 VERY POOR</option>
</select>
</div>

<div class="subject-box">
<h3>Machine Learning</h3>
<select class="rating">
<option value="">Select Rating</option>
<option value="5">5 EXCELLENT</option>
<option value="4">4 GOOD</option>
<option value="3">3 AVERAGE</option>
<option value="2">2 POOR</option>
<option value="1">1 VERY POOR</option>
</select>
</div>
<div class="subject-box">
<h3>Disaster Management</h3>
<select class="rating">
<option value="">Select Rating</option>
<option value="5">5 EXCELLENT</option>
<option value="4">4 GOOD</option>
<option value="3">3 AVERAGE</option>
<option value="2">2 POOR</option>
<option value="1">1 VERY POOR</option>
</select>
</div>
<div class="subject-box">
<h3>Cloud Computing lab</h3>
<select class="rating">
<option value="">Select Rating</option>
<option value="5">5 EXCELLENT</option>
<option value="4">4 GOOD</option>
<option value="3">3 AVERAGE</option>
<option value="2">2 POOR</option>
<option value="1">1 VERY POOR</option>
</select>
</div>
<div class="subject-box">
<h3>Cryptography and Network Security lab</h3>
<select class="rating">
<option value="">Select Rating</option>
<option value="5">5 EXCELLENT</option>
<option value="4">4 GOOD</option>
<option value="3">3 AVERAGE</option>
<option value="2">2 POOR</option>
<option value="1">1 VERY POOR</option>
</select>
</div>

</div>

<br>
<button onclick="submitAllFeedback()">Submit All Feedback </button>

</div>
<div class="footer">
  <p>&copy||GANESH||23ME1A05F8</p>
</div>

<script type="module" src="script.js"></script>

</body>
</html>
