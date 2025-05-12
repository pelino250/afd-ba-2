# CSS Fundamentals Breakout Activity (30 minutes)

## Activity: Styling a Personal Profile Card

This 30-minute breakout activity will help students practice core CSS fundamentals including:
- Selectors and specificity
- Colors and backgrounds
- Typography
- Box model (margin, padding, border)
- Display properties
- Pseudo-classes

## Starter Code

### index.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Fundamentals - Profile Card</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="profile-card">
        <header>
            <!-- TODO: Add a profile image with class 'profile-img' -->
            <h1 class="profile-name">Alex Johnson</h1>
            <p class="profile-title">Frontend Developer</p>
        </header>
        
        <section class="profile-details">
            <!-- TODO: Add a short bio with class 'profile-bio' -->
            <ul class="profile-skills">
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
                <!-- TODO: Add 2 more skills -->
            </ul>
        </section>
        
        <footer class="profile-footer">
            <!-- TODO: Add social links with class 'social-link' -->
        </footer>
    </div>
</body>
</html>
```

### styles.css
```css
/* TODO: Add a Google Font import (choose any font you like) */

/* TODO: Set up basic reset styles (margin, padding, box-sizing) */

/* TODO: Style the body with a background color and font family */

.profile-card {
    /* TODO: Add width, margin, background color, border-radius, and box-shadow */
    /* TODO: Add padding and set overflow to hidden */
}

.profile-card header {
    /* TODO: Style the header with text alignment, padding, and background color */
}

.profile-img {
    /* TODO: Add styles for the profile image (width, height, border-radius, etc.) */
}

.profile-name {
    /* TODO: Style the name with font size, weight, color, and margin */
}

.profile-title {
    /* TODO: Style the title with font size, color, and margin */
}

.profile-details {
    /* TODO: Add padding to the details section */
}

.profile-bio {
    /* TODO: Style the bio with font size, line height, and color */
}

.profile-skills {
    /* TODO: Style the skills list (remove list style, add padding) */
    /* TODO: Style the skills list items (display, background, margin, etc.) */
}

.profile-footer {
    /* TODO: Style the footer with background color, padding, and text alignment */
}

.social-link {
    /* TODO: Style social links (display, color, margin, etc.) */
    /* TODO: Add hover effect for social links */
}
```

## Activity Instructions

1. **Fork the repository** (automatically done via GitHub Classroom)
2. **Open in Codespaces** (GitHub Classroom will provide this option)
3. **Complete the TODOs** in both HTML and CSS files:
   - Add missing HTML elements where indicated
   - Implement all CSS styles following the TODO comments
4. **Customize the design** - Feel free to go beyond the basic requirements:
   - Experiment with different colors, borders, and shadows
   - Add transitions or animations if time permits
   - Try different font combinations

## Success Criteria

Students should have a complete profile card that demonstrates:
- Proper use of CSS selectors
- Thoughtful color scheme and typography
- Correct application of box model properties
- Basic interactive elements (hover states)
- Clean, organized CSS code
