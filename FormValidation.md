#what methods of form validation are taught in class


At Higher level, the form validation taught is fairly basic and is usually implemented using HTML form attributes and simple JavaScript validation. The specification includes an appendix dedicated to HTML forms and another for JavaScript, indicating that candidates are expected to use both technologies in web solutions.
sqa

Typical validation methods that align with the Higher course include:

HTML Validation
Using built-in HTML attributes such as:




<input type="text" required>



<input type="email">



<input type="number" min="1" max="100">



<input maxlength="20">
These allow candidates to enforce:

Required fields
Email format
Numeric ranges
Minimum and maximum lengths
These are simple, standards-based techniques consistent with the HTML forms content in the specification.
sqa

JavaScript Validation
Candidates are also expected to use JavaScript for interactivity, so validation commonly includes checks such as:



if (name === "") {
    alert("Please enter your name");
}


if (age < 16 || age > 120) {
    alert("Invalid age");
}


if (!email.includes("@")) {
    alert("Invalid email address");
}
These demonstrate:

Presence checks
Range checks
Format checks
Decision-making using selection statements
which are core Higher Computing Science skills.
sqa

Test Data Expected
When validating forms, candidates should test using:

Test Type	Example
Normal	ian@example.com
Exceptional	ianexample.com
Extreme	Maximum permitted field length
The specification explicitly requires understanding and use of normal, exceptional and extreme (boundary) test data.
sqa

What is not taught
I found no evidence in the specification that candidates are expected to use:

Regular expressions
jQuery Validation
React Hook Form
Yup
Zod
Server-side validation
PHP validation
Node.js validation libraries
Those techniques would generally be beyond Higher Computing Science. The course focuses on demonstrating the principles of validation, testing and error checking rather than modern framework-based solutions.
sqa

In practice, a Grade A candidate's website would typically use a combination of HTML5 validation attributes and simple JavaScript checks, then provide testing evidence showing valid, invalid and boundary inputs