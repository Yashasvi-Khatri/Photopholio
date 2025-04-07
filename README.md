# Photopholio

Photopholio is a dynamic photo album application that allows users to create and manage their photo collections in an intuitive and visually appealing interface.

![Photopholio App](https://via.placeholder.com/800x400?text=Photopholio+App)

## Features

- **Album Management**: Create, edit, and delete custom photo albums
- **Image Upload**: Easily upload and organize your photos within albums
- **Responsive Design**: Enjoy a seamless experience across desktop and mobile devices
- **Image Previews**: View your photos with a clean, modern gallery interface
- **Search Functionality**: Quickly find specific photos or albums
- **Drag and Drop**: Intuitive drag and drop interface for organizing photos

## Technologies Used

- React.js for the frontend interface
- Firebase for backend storage and authentication
- CSS3 for styling and animations
- Responsive design principles for cross-device compatibility

## Installation

Follow these steps to set up Photopholio locally:

1. Clone the repository:
   ```
   git clone https://github.com/Yashasvi-Khatri/Photopholio.git
   ```

2. Navigate to the project directory:
   ```
   cd Photopholio
   ```

3. Install dependencies:
   ```
   npm install
   ```

4. Set up your Firebase configuration:
   - Create a Firebase project at [firebase.google.com](https://firebase.google.com)
   - Enable Authentication and Storage services
   - Create a `.env` file in the project root with your Firebase configuration:
     ```
     REACT_APP_FIREBASE_API_KEY=your_api_key
     REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
     REACT_APP_FIREBASE_PROJECT_ID=your_project_id
     REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
     REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
     REACT_APP_FIREBASE_APP_ID=your_app_id
     ```

5. Start the development server:
   ```
   npm start
   ```

6. Open your browser and navigate to `http://localhost:3000`

## Usage

### Creating an Album
1. Click on the "Create Album" button
2. Enter a name for your new album
3. Click "Create" to confirm

### Adding Photos
1. Open the album where you want to add photos
2. Click on the "Add Photos" button
3. Select images from your device to upload
4. Wait for the upload to complete

### Managing Photos
- **View**: Click on any photo to see it in full-screen mode
- **Delete**: Select photos and click the "Delete" button
- **Move**: Drag and drop photos between albums
- **Search**: Use the search bar to find specific photos

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

Yashasvi Khatri - [GitHub Profile](https://github.com/Yashasvi-Khatri)

Project Link: [https://github.com/Yashasvi-Khatri/Photopholio](https://github.com/Yashasvi-Khatri/Photopholio.git)

## Acknowledgments

- Thanks to all contributors who have helped make this project better
- Inspiration from modern photo management applications
- Special thanks to the React and Firebase communities for their excellent documentation
