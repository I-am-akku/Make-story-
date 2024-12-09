<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instagram-like Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>Instagram</h1>
        </div>
        <div class="search-bar">
            <input type="text" placeholder="Search">
        </div>
        <div class="user-icon">
            <img src="profile-pic.jpg" alt="User Profile" />
        </div>
    </header>

    <main>
        <div class="profile">
            <div class="profile-info">
                <img class="profile-img" src="profile-pic.jpg" alt="Profile Picture">
                <div class="profile-details">
                    <h2>username</h2>
                    <p>Full Name</p>
                    <p>Location</p>
                </div>
            </div>
        </div>

        <div class="posts-feed">
            <!-- Post 1 -->
            <div class="post">
                <div class="post-header">
                    <img class="post-user-img" src="profile-pic.jpg" alt="User">
                    <span class="username">username</span>
                </div>
                <img class="post-image" src="your-image.jpg" alt="Post Image">
                <div class="post-actions">
                    <button class="like-btn" onclick="toggleLike(this)">❤️ Like</button>
                    <button class="comment-btn" onclick="toggleCommentBox(this)">💬 Comment</button>
                </div>
                <div class="post-info">
                    <span class="likes-count">10 Likes</span>
                    <p class="post-caption">This is the caption of the post!</p>
                </div>
                <div class="comment-section">
                    <textarea class="comment-input" placeholder="Write a comment..."></textarea>
                    <button class="post-comment">Post Comment</button>
                </div>
            </div>
        </div>
    </main>

    <footer>
        <p>© 2024 Instagram Clone</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
