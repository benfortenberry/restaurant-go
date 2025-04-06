# Restaurant Reviews Web Application

This is a web application for displaying restaurant reviews. Users can view reviews, including ratings, dishes, and comments, in a clean and responsive design.

## Features

- Displays a list of restaurant reviews with user ratings, dish names, and comments.
- Styled using modern CSS with a clean and minimalistic design.
- Responsive layout for better usability on different devices.
- Includes a "Back to Home" button for easy navigation.

## File Structure

- **templates/reviews.html**: The HTML template for displaying reviews.
- **static/styles.css**: The CSS file for styling the application.

## Technologies Used

- **HTML**: For structuring the web pages.
- **CSS**: For styling the application.
- **Go Templates**: For dynamically rendering reviews.


## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```

2. Navigate to the project directory:
   ```bash
   cd your-repo-name
   ```

3. Run the Go server (assuming you have a Go backend serving the templates):
   ```bash
   go run main.go
   ```

4. Open the application in your browser at `http://localhost:8080` (or the port your server is running on).

## Customization

- **Change the font**: Update the `<link>` tag in `reviews.html` to include a different Google Font.
- **Modify the styles**: Edit the `styles.css` file in the `static` directory.

## License

This project is licensed under the MIT License. Feel free to use and modify it as needed.