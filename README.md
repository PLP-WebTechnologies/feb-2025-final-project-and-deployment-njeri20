# Final Project and Deployment

## Objectives
Build a fully functional web application.
Apply HTML, CSS, and JavaScript concepts learned.
Deploy the project using GitHub Pages, Netlify, or Vercel.

## Instructions
Choose one of the following project ideas:
Blog Website: Implement a multi-page site with navigation.
Ecommerce Website: Implement a multi-page site with navigation.

>[!NOTE]
> - Include at least:
> - A responsive design.
> - JavaScript interactivity.
> - A deployment link.

## Tasks

Create a well-structured HTML5 document.
Use at least 5 different HTML elements.
Ensure semantic correctness.

Good luck and happy coding! 🚀💻


<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nairobi Waste Watch - Tracking Waste Collection in the City</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>Nairobi Waste Watch</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                </ul>
        </nav>
    </header>

    <main class="container">
        <section class="blog-posts">
            <h2>Latest Waste Collection Insights</h2>

            <article class="blog-post">
                <h3>Mapping Nairobi's Waste Hotspots</h3>
                <p class="post-meta">Published on <time datetime="2023-11-01">November 1, 2023</time> by Njeri Macharia</p>
                <p class="post-preview">Exploring key areas in Nairobi facing significant waste collection challenges and why they become hotspots. This post dives into the geographical and logistical factors...</p>
                <button class="read-more-btn">Read More</button>
                <div class="full-post-content" style="display: none;">
                    <p>Nairobi, like many rapidly growing cities, faces persistent challenges in waste management. Certain areas consistently struggle with timely waste collection, leading to environmental hazards and public health concerns. This post identifies some of these critical hotspots, including [mention specific areas conceptually, e.g., parts of the CBD, informal settlements, market areas].</p>
                    <p>Factors contributing to these hotspots include accessibility issues for collection vehicles, population density, informal dumping practices, and sometimes, breakdowns in scheduled collection services. Understanding these areas is the first step towards developing targeted solutions.</p>
                </div>
                 <p class="comment-count">Comments: <span class="count">0</span></p>
                 <button class="add-comment-btn">Add Comment</button>
            </article>

            <article class="blog-post">
                <h3>The Role of Community in Waste Tracking</h3>
                <p class="post-meta">Published on <time datetime="2023-10-29">October 29, 2023</time> by Njeri Macharia</p>
                <p class="post-preview">How can Nairobi residents contribute to better waste collection? This post looks at the power of community involvement and simple tracking methods...</p>
                <button class="read-more-btn">Read More</button>
                 <div class="full-post-content" style="display: none;">
                    <p>Community participation is vital for effective waste management. Residents can play a crucial role by reporting missed collections, documenting areas with illegal dumping, and organizing local clean-up initiatives. Simple tools, even just a mobile phone camera and location sharing, can help create a clearer picture of collection patterns.</p>
                    <p>By empowering communities to track and report, we can provide valuable data to waste management authorities and private collectors, leading to more responsive and efficient services. This collaborative approach benefits everyone in the neighborhood.</p>
                </div>
                 <p class="comment-count">Comments: <span class="count">0</span></p>
                 <button class="add-comment-btn">Add Comment</button>
            </article>

            </section>

        <aside class="sidebar">
            <h3>About This Project</h3>
            <p>This blog tracks observations and insights into waste collection patterns and challenges across Nairobi. Aiming to raise awareness and encourage data-driven improvements.</p>
            <h3>Topics</h3>
            <ul>
                <li><a href="#">Hotspots</a></li>
                <li><a href="#">Community Action</a></li>
                <li><a href="#">Policy</a></li>
                 <li><a href="#">Technology in Waste</a></li>
            </ul>
        </aside>
    </main>

    <footer>
        <p>&copy; 2023 Nairobi Waste Watch</p>
    </footer>

    <script src="script.js"></script>

</body>
</html>

body {
    font-family: sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

.container {
    max-width: 1200px;
    margin: 20px auto;
    padding: 0 20px;
    display: grid; /* Use Grid for main layout */
    grid-template-columns: 1fr; /* Default single column for mobile */
    gap: 30px; /* Space between main content and sidebar */
}

/* Header and Navigation */
header {
    background-color: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}

header h1 {
    margin-bottom: 0.5rem;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex; /* Use Flexbox for navigation links */
    justify-content: center;
}

nav ul li {
    margin: 0 15px;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    padding: 5px 10px;
    transition: color 0.3s ease;
}

nav a:hover {
    color: #007bff;
}

/* Blog Posts and Sidebar */
.blog-post {
    background-color: #fff;
    padding: 20px;
    margin-bottom: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.blog-post h3 {
    margin-top: 0;
    color: #007bff;
}

.post-meta {
    font-size: 0.9em;
    color: #666;
    margin-bottom: 15px;
}

.read-more-btn {
    display: inline-block;
    margin-top: 10px;
    padding: 8px 15px;
    background-color: #5cb85c;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.read-more-btn:hover {
    background-color: #4cae4c;
}

.full-post-content {
    margin-top: 15px;
    border-top: 1px dashed #eee;
    padding-top: 15px;
}

.comment-count {
    font-size: 0.9em;
    color: #666;
    margin-top: 10px;
}

.add-comment-btn {
     display: inline-block;
     margin-top: 5px;
     padding: 5px 10px;
     background-color: #f0ad4e;
     color: white;
     border: none;
     border-radius: 4px;
     cursor: pointer;
     transition: background-color 0.3s ease;
     font-size: 0.9em;
}

.add-comment-btn:hover {
    background-color: #ec971f;
}


.sidebar {
    background-color: #e9e9e9;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.sidebar h3 {
    margin-top: 0;
    color: #555;
}

.sidebar ul {
    list-style: none;
    padding: 0;
}

.sidebar ul li {
    margin-bottom: 5px;
}

.sidebar a {
    color: #333;
    text-decoration: none;
    transition: color 0.3s ease;
}

.sidebar a:hover {
    color: #007bff;
}

/* About Page Specific Styles (if any needed, otherwise uses general styles) */
.page-content {
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}


/* Footer */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
    margin-top: 30px;
}


/* ===================================== */
/* Responsive Design with Media Queries */
/* ===================================== */

/* Tablet and Desktop Layout */
@media (min-width: 768px) {
    .container {
        grid-template-columns: 2fr 1fr; /* Main content takes 2 parts, sidebar 1 part */
    }

    .blog-posts {
        /* Takes the first grid column */
    }

    .sidebar {
        /* Takes the second grid column */
    }
}

/* Larger Desktop Layout */
@media (min-width: 1024px) {
     .container {
        grid-template-columns: 3fr 1fr; /* Adjust ratio for larger screens */
     }
}

/* Mobile Layout (Default styles apply, but can add specific adjustments) */
@media (max-width: 767px) {
    header {
        padding: 1rem; /* Add horizontal padding */
    }

    nav ul {
        flex-direction: column; /* Stack nav links vertically */
        align-items: center;
        margin-top: 10px;
    }

    nav ul li {
        margin: 5px 0; /* Adjust vertical margin */
    }

    .container {
        padding: 0 15px; /* Slightly less padding on smaller screens */
    }

    .blog-post, .sidebar, .page-content {
         padding: 15px; /* Slightly less padding inside sections */
    }
}
document.addEventListener('DOMContentLoaded', function() {

    // --- JavaScript Interactivity: "Read More" Toggle ---
    // Select all buttons with the class 'read-more-btn'
    const readMoreButtons = document.querySelectorAll('.read-more-btn');

    // Loop through each button and add a click event listener
    readMoreButtons.forEach(button => {
        button.addEventListener('click', function() {
            // Find the parent article element
            const article = this.closest('.blog-post');
            // Find the full content div within this article
            const fullContent = article.querySelector('.full-post-content');
            // Find the preview paragraph within this article
            const preview = article.querySelector('.post-preview');

            // Toggle the display of the full content
            if (fullContent.style.display === 'none') {
                fullContent.style.display = 'block'; // Show the full content
                preview.style.display = 'none'; // Hide the preview
                this.textContent = 'Read Less'; // Change button text
            } else {
                fullContent.style.display = 'none'; // Hide the full content
                preview.style.display = 'block'; // Show the preview
                this.textContent = 'Read More'; // Change button text
            }
        });
    });

    // --- JavaScript Interactivity: Simple Comment Counter ---
     // Select all buttons with the class 'add-comment-btn'
    const addCommentButtons = document.querySelectorAll('.add-comment-btn');

    // Loop through each button and add a click event listener
    addCommentButtons.forEach(button => {
        button.addEventListener('click', function() {
            // Find the parent article element
            const article = this.closest('.blog-post');
            // Find the span that displays the comment count within this article
            const commentCountSpan = article.querySelector('.comment-count .count');

            // Get the current count, convert to a number, increment, and update the text
            let currentCount = parseInt(commentCountSpan.textContent);
            currentCount++;
            commentCountSpan.textContent = currentCount;

            // Optional: Provide visual feedback (e.g., a temporary message)
            console.log(`Comment count for a post updated to: ${currentCount}`);
        });
    });
