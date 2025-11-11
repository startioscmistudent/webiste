<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to ICS 110</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="container">
            <h1 class="logo">Welcome to ICS 110</h1>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Main Content -->
    <main class="container">
        <section class="blog-posts">
            <!-- Blog Post 1 -->
            <article class="post">
                <h2 class="post-title">Blog Post Title</h2>
                <p class="post-meta">Posted on <span class="date">Month Day, Year</span> by <span class="author">Author Name</span></p>
                <p class="post-content">
                    <!-- Your blog content goes here -->
                </p>
                <a href="#" class="read-more">Read More →</a>
            </article>

            <!-- Blog Post 2 -->
            <article class="post">
                <h2 class="post-title">Another Blog Post</h2>
                <p class="post-meta">Posted on <span class="date">Month Day, Year</span> by <span class="author">Author Name</span></p>
                <p class="post-content">
                    <!-- Your blog content goes here -->
                </p>
                <a href="#" class="read-more">Read More →</a>
            </article>
        </section>

        <!-- Sidebar -->
        <aside class="sidebar">
            <h3>About Me</h3>
            <p><!-- Short bio or intro goes here --></p>

            <h3>Categories</h3>
            <ul>
                <li><a href="#">Technology</a></li>
                <li><a href="#">Lifestyle</a></li>
                <li><a href="#">Travel</a></li>
            </ul>

            <h3>Follow Me</h3>
            <ul class="social-links">
                <li><a href="#">Twitter</a></li>
                <li><a href="#">Instagram</a></li>
                <li><a href="#">GitHub</a></li>
            </ul>
        </aside>
    </main>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; <span id="year"></span> My Blog. All rights reserved.</p>
        </div>
    </footer>

    <script>
        // Automatically update footer year
        document.getElementById('year').textContent = new Date().getFullYear();
    </script>
</body>
</html>
