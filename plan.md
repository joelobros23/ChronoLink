# Project Plan: ChronoLink

**Description:** A social network focused on sharing moments and experiences tied to specific points in time. Users can create 'chronicles' of their lives, connect with others, and explore timelines of shared interests.


## Development Goals

- [ ] Set up the database: Create the database and import the schema from database.sql.
- [ ] Implement database connection: Create api/config.php to handle database connection.
- [ ] User Authentication: Develop user registration (api/register.php) and login (api/login.php) functionality. Implement logout (api/logout.php).
- [ ] Frontend Authentication: Create register.html, login.html, and corresponding JavaScript (assets/js/auth.js) to handle user authentication.
- [ ] Home Page: Design the home page (home.html) with Tailwind CSS. Implement post creation (api/create_post.php) and retrieval (api/get_posts.php).
- [ ] Post Display: Display posts on the home page using components/post.html. Use JavaScript (assets/js/main.js) to dynamically load and render posts.
- [ ] Profile Page: Create a profile page (profile.html). Implement functionality to retrieve user profile data (api/get_profile.php) and update profile information (api/update_profile.php) with assets/js/profile.js.
- [ ] Friend Management: Implement friend request sending (api/add_friend.php), accepting (api/accept_friend.php), and rejecting (api/reject_friend.php). Develop a friends page (friends.html) to display friends (api/get_friends.php) and handle friend requests, with friends.js.
- [ ] Search Functionality: Add search functionality (search.html) to find other users (api/search_users.php) with assets/js/search.js.
- [ ] Post Interactions: Implement liking (api/like_post.php, api/unlike_post.php) and commenting (api/comment_post.php, api/get_comments.php) features. Use components/comment.html to display comments and update them dynamically.
- [ ] Styling: Implement Tailwind CSS styling across all pages and components to ensure a consistent and visually appealing design.
- [ ] Error Handling: Implement robust error handling and validation on both the frontend and backend to provide a smooth user experience.
