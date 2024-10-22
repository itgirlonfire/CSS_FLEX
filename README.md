index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Product Layout</title>
</head>
<body>
    <div class="product-container">
        <div class="product-card">Product 1</div>
        <div class="product-card">Product 2</div>
        <div class="product-card">Product 3</div>
        <div class="product-card">Product 4</div>
    </div>
</body>
</html>

employees.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Employee Cards</title>
</head>
<body>
    <div class="employee-container">
        <div class="employee-card">Employee 1</div>
        <div class="employee-card">Employee 2</div>
        <div class="employee-card">Employee 3</div>
        <div class="employee-card">Employee 4</div>
    </div>
</body>
</html>

students.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Student Profiles</title>
</head>
<body>
    <div class="student-container">
        <div class="student-card">Student 1</div>
        <div class="student-card">Student 2</div>
        <div class="student-card">Student 3</div>
        <div class="student-card">Student 4</div>
    </div>
</body>
</html>

gallery.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Image Gallery</title>
</head>
<body>
    <div class="gallery-container">
        <div class="gallery-item">Image 1</div>
        <div class="gallery-item">Image 2</div>
        <div class="gallery-item">Image 3</div>
        <div class="gallery-item">Image 4</div>
    </div>
</body>
</html>

blog.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Blog Posts</title>
</head>
<body>
    <div class="blog-container">
        <div class="blog-post">Post 1</div>
        <div class="blog-post">Post 2</div>
        <div class="blog-post">Post 3</div>
        <div class="blog-post">Post 4</div>
    </div>
</body>
</html>

style.css
body {
    font-family: Arial, sans-serif;
}

.product-container,
.employee-container,
.student-container,
.gallery-container,
.blog-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    padding: 20px;
}

.product-card,
.employee-card,
.student-card,
.gallery-item,
.blog-post {
    flex: 1 1 calc(25% - 20px);
    margin: 10px;
    background-color: #f0f0f0;
    padding: 20px;
    text-align: center;
}
