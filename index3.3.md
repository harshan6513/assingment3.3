# Assignment 3.3 — Ordered, Unordered & Nested Lists

**Topic:** College Information Webpage  
**File Name:** `college-info.html`

## 1. Objective

The objective of this assignment is to create a college information webpage using different types of HTML lists. This webpage includes an introduction, a list of subjects, an admission process, a nested list of course topics, and details of courses and teachers.

## 2. HTML Code

Copy the following code into a file named `college-info.html`.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>College Information</title>
</head>
<body>

    <header>
        <h1>College Information Portal</h1>
        <p>Welcome to our College Information Webpage</p>
    </header>

    <hr>

    <main>

        <!-- College Introduction -->
        <section id="introduction">
            <h2>Introduction</h2>

            <p>
                A college is an educational institution that provides
                higher education and helps students develop knowledge,
                practical skills, and professional abilities.
                Students can choose courses according to their interests
                and career goals.
            </p>
        </section>

        <hr>

        <!-- List of Subjects -->
        <section id="subjects">
            <h2>Departments and Subjects</h2>

            <ul>
                <li>Computer Science</li>
                <li>Electrical Engineering</li>
                <li>Mechanical Engineering</li>
                <li>Civil Engineering</li>
                <li>Business Administration</li>
            </ul>
        </section>

        <hr>

        <!-- Admission Process -->
        <section id="admission">
            <h2>Admission Process</h2>

            <ol>
                <li>Choose a suitable course.</li>
                <li>Check the eligibility requirements.</li>
                <li>Fill out the admission application form.</li>
                <li>Upload the required documents.</li>
                <li>Pay the application fee, if applicable.</li>
                <li>Complete document verification.</li>
                <li>Confirm admission according to college instructions.</li>
            </ol>
        </section>

        <hr>

        <!-- Nested List -->
        <section id="course-topics">
            <h2>Topics Covered in Computer Science</h2>

            <ul>
                <li>Programming
                    <ul>
                        <li>C Programming</li>
                        <li>Java Programming</li>
                        <li>Python Programming</li>
                    </ul>
                </li>

                <li>Web Development
                    <ul>
                        <li>HTML</li>
                        <li>CSS</li>
                        <li>JavaScript</li>
                    </ul>
                </li>

                <li>Database Management
                    <ul>
                        <li>Introduction to Databases</li>
                        <li>SQL Basics</li>
                    </ul>
                </li>
            </ul>
        </section>

        <hr>

        <!-- Description List -->
        <section id="course-details">
            <h2>Course and Teacher Details</h2>

            <dl>
                <dt><strong>HTML</strong></dt>
                <dd>
                    HTML stands for HyperText Markup Language.
                    It is used to structure content on webpages.
                </dd>

                <dt><strong>CSS</strong></dt>
                <dd>
                    CSS stands for Cascading Style Sheets.
                    It is used to style and design webpages.
                </dd>

                <dt><strong>JavaScript</strong></dt>
                <dd>
                    JavaScript adds interactive features
                    and dynamic behaviour to webpages.
                </dd>

                <dt><strong>Course Instructor</strong></dt>
                <dd>
                    The course instructor guides students,
                    explains concepts, and helps them develop
                    practical skills.
                </dd>
            </dl>
        </section>

    </main>

    <hr>

    <footer>
        <p>Created for HTML Assignment 3.3</p>
        <p>College Information Webpage</p>
    </footer>

</body>
</html>
```

## 3. Explanation of HTML Lists

### A. Unordered List — `<ul>`

An unordered list displays items using bullet points. It is useful for listing departments or subjects.

### B. Ordered List — `<ol>`

An ordered list displays items in a numbered sequence. It is useful for explaining steps such as an admission process.

### C. Nested List

A nested list is a list inside another list. It helps organize subjects and their related topics.

### D. Description List — `<dl>`

- `<dl>` creates a description list.
- `<dt>` specifies the term or title.
- `<dd>` provides the description of that term.

## 4. Steps to Run the Webpage

1. Open Notepad or Visual Studio Code.
2. Copy the HTML code provided above.
3. Save the file as `college-info.html`.
4. In Notepad, select **Save as type: All Files** and use UTF-8 encoding.
5. Open the file in Google Chrome or Microsoft Edge.
6. Verify that all headings, lists, and descriptions are visible.

## 5. Screenshot for Submission

Take an actual screenshot of the webpage open in your browser. Make sure the screenshot clearly shows the college introduction and the different HTML lists. If everything does not fit on one screen, take additional screenshots after scrolling.

## 6. Result

Successfully created a college information webpage using HTML. The webpage includes an introduction, unordered list, ordered list, nested list, and description list.

## 7. Conclusion

This assignment helped me understand how to use different HTML list elements to organize information clearly and create a structured webpage.

**Assignment 3.3 Completed Successfully.**