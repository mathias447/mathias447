def generate_clean_website():
    html_template = """
    <!DOCTYPE html>
    <html>
    <head>
        <title>Clean Website</title>
        <style>
            body {
                font-family: Arial, sans-serif;
                background-color: #f0f0f0;
                margin: 0;
                padding: 0;
            }
            .container {
                max-width: 800px;
                margin: 0 auto;
                padding: 20px;
                background-color: #fff;
                border-radius: 5px;
                box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            }
        </style>
    </head>
    <body>
        <div class="container">
            <h1>Welcome to Our Clean Website</h1>
            <p>This is a sample content section.</p>
        </div>
    </body>
    </html>
    """
    return html_template

# Generate the clean website template
clean_website_code = generate_clean_website()
print(clean_website_code)
