# Creating a zip file containing the basic HTML and CSS structure for the requested website "Ishakshop".



from zipfile import ZipFile



# Define the HTML and CSS content for each page



# Index page content (home page)

index_html = """

<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Ishakshop - Home</title>

    <link rel="stylesheet" href="styles.css">

</head>

<body>

    <header>

        <h1>Welcome to Ishakshop</h1>

    </header>

    <section id="featured-products">

        <h2>Featured Products</h2>

        <p>Discover our exclusive range of products!</p>

    </section>

    <footer>

        <p>Contact us at info@ishakshop.com</p>

    </footer>

</body>

</html>

"""



# Products page content

products_html = """

<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Ishakshop - Products</title>

    <link rel="stylesheet" href="styles.css">

</head>

<body>

    <header>

        <h1>Our Products</h1>

    </header>

    <section id="product-list">

        <h2>Explore our range</h2>

        <p>Here you will find all our available products.</p>

    </section>

    <footer>

        <p>Contact us at info@ishakshop.com</p>

    </footer>

</body>

</html>

"""



# About Us page content

about_html = """

<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>About Us - Ishakshop</title>

    <link rel="stylesheet" href="styles.css">

</head>

<body>

    <header>

        <h1>About Ishakshop</h1>

    </header>

    <section id="about-section">

        <p>We are dedicated to providing the best products and services to our customers.</p>

    </section>

    <footer>

        <p>Contact us at info@ishakshop.com</p>

    </footer>

</body>

</html>

"""



# Blog page content

blog_html = """

<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Blog - Ishakshop</title>

    <link rel="stylesheet" href="styles.css">

</head>

<body>

    <header>

        <h1>Ishakshop Blog</h1>

    </header>

    <section id="blog-posts">

        <h2>Latest Tips and News</h2>

        <p>Stay tuned for updates and product tips!</p>

    </section>

    <footer>

        <p>Contact us at info@ishakshop.com</p>

    </footer>

</body>

</html>

"""



# Contact Us page content

contact_html = """

<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Contact Us - Ishakshop</title>

    <link rel="stylesheet" href="styles.css">

</head>

<body>

    <header>

        <h1>Contact Us</h1>

    </header>

    <section id="contact-form">

        <form action="#" method="POST">

            <label for="name">Name:</label><br>

            <input type="text" id="name" name="name" required><br>

            <label for="email">Email:</label><br>

            <input type="email" id="email" name="email" required><br>

            <label for="message">Message:</label><br>

            <textarea id="message" name="message" required></textarea><br>

            <button type="submit">Send Message</button>

        </form>

    </section>

    <footer>

        <p>Contact us at info@ishakshop.com</p>

    </footer>

</body>

</html>

"""



# CSS content (styles.css)

styles_css = """

body {

    font-family: Arial, sans-serif;

    background-color: #000;

    color: #fff;

    margin: 0;

    padding: 0;

}



header {

    background-color: #111;

    padding: 20px;

    text-align: center;

}



h1 {

    color: #ff0000;

}



h2 {

    color: #fff;

}



#featured-products, #product-list, #about-section, #blog-posts, #contact-form {

    padding: 20px;

    text-align: center;

}



footer {

    background-color: #111;

    padding: 10px;

    text-align: center;

    color: #fff;

}

"""



# Create a zip file and add all files to it

zip_path = '/mnt/data/Ishakshop_website_template.zip'

with ZipFile(zip_path, 'w') as zip_file:

    zip_file.writestr("index.html", index_html)

    zip_file.writestr("products.html", products_html)

    zip_file.writestr("about.html", about_html)

    zip_file.writestr("blog.html", blog_html)

    zip_file.writestr("contact.html", contact_html)
# Creating a zip file containing the basic HTML and CSS structure for the requested website "Ishakshop".



from zipfile import ZipFile



# Define the HTML and CSS content for each page



# Index page content (home page)

index_html = """

<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Ishakshop - Home</title>

    <link rel="stylesheet" href="styles.css">

</head>

<body>

    <header>

        <h1>Welcome to Ishakshop</h1>

    </header>

    <section id="featured-products">

        <h2>Featured Products</h2>

        <p>Discover our exclusive range of products!</p>

    </section>

    <footer>

        <p>Contact us at info@ishakshop.com</p>

    </footer>

</body>

</html>

"""



# Products page content

products_html = """

<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Ishakshop - Products</title>

    <link rel="stylesheet" href="styles.css">

</head>

<body>

    <header>

        <h1>Our Products</h1>

    </header>

    <section id="product-list">

        <h2>Explore our range</h2>

        <p>Here you will find all our available products.</p>

    </section>

    <footer>

        <p>Contact us at info@ishakshop.com</p>

    </footer>

</body>

</html>

"""



# About Us page content

about_html = """

<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>About Us - Ishakshop</title>

    <link rel="stylesheet" href="styles.css">

</head>

<body>

    <header>

        <h1>About Ishakshop</h1>

    </header>

    <section id="about-section">

        <p>We are dedicated to providing the best products and services to our customers.</p>

    </section>

    <footer>

        <p>Contact us at info@ishakshop.com</p>

    </footer>

</body>

</html>

"""



# Blog page content

blog_html = """

<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Blog - Ishakshop</title>

    <link rel="stylesheet" href="styles.css">

</head>

<body>

    <header>

        <h1>Ishakshop Blog</h1>

    </header>

    <section id="blog-posts">

        <h2>Latest Tips and News</h2>

        <p>Stay tuned for updates and product tips!</p>

    </section>

    <footer>

        <p>Contact us at info@ishakshop.com</p>

    </footer>

</body>

</html>

"""



# Contact Us page content

contact_html = """

<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Contact Us - Ishakshop</title>

    <link rel="stylesheet" href="styles.css">

</head>

<body>

    <header>

        <h1>Contact Us</h1>

    </header>

    <section id="contact-form">

        <form action="#" method="POST">

            <label for="name">Name:</label><br>

            <input type="text" id="name" name="name" required><br>

            <label for="email">Email:</label><br>

            <input type="email" id="email" name="email" required><br>

            <label for="message">Message:</label><br>

            <textarea id="message" name="message" required></textarea><br>

            <button type="submit">Send Message</button>

        </form>

    </section>

    <footer>

        <p>Contact us at info@ishakshop.com</p>

    </footer>

</body>

</html>

"""



# CSS content (styles.css)

styles_css = """

body {

    font-family: Arial, sans-serif;

    background-color: #000;

    color: #fff;

    margin: 0;

    padding: 0;

}



header {

    background-color: #111;

    padding: 20px;

    text-align: center;

}



h1 {

    color: #ff0000;

}



h2 {

    color: #fff;

}



#featured-products, #product-list, #about-section, #blog-posts, #contact-form {

    padding: 20px;

    text-align: center;

}



footer {

    background-color: #111;

    padding: 10px;

    text-align: center;

    color: #fff;

}

"""



# Create a zip file and add all files to it

zip_path = '/mnt/data/Ishakshop_website_template.zip'

with ZipFile(zip_path, 'w') as zip_file:

    .writestr("index.html", index_html)

    zip_file.writestr("products.html", products_html)

    zip_file.writestr("about.html", about_html)

    zip_file.writestr("blog.html", blog_html)

    zip_file.writestr("contact.html", contact_html)

    zip_file.writestr("styles.css", styles_css)



zip_path

    zip_file.writestr("styles.css", styles_css)



zip_path
