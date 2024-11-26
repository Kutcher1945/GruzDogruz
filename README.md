
# GruzDogruz Application

GruzDogruz is a comprehensive logistics application that enables users to share their locations and request truck services for the delivery of goods. The application provides a seamless platform for connecting customers with delivery providers, streamlining the logistics process.

## Features

- **User Authentication**: Secure login and account management.
- **Interactive Map**: Users can view and share their location using an integrated Google Maps interface.
- **Order Creation**: Customers can create delivery requests with detailed specifications.
- **Real-Time Tracking**: Track deliveries in real-time through the application.
- **Payment Integration**: Seamless payment options for a hassle-free experience.
- **Multilingual Support**: The app supports multiple languages for a wider user base.

## Technologies Used

- **Backend**: Django
- **Frontend**: React
- **Mobile Application**: React Native
- **Database**: PostgreSQL with PostGIS for geospatial data
- **Mapping Service**: Google Maps API
- **Containerization**: Docker for streamlined deployment

## Installation and Setup

### Prerequisites
- Docker
- PostgreSQL with PostGIS
- Python 3.10
- Node.js 20.x
- React Native CLI

### Steps to Run Locally
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repo/gruzdogruz.git
   cd gruzdogruz
   ```

2. **Backend Setup**:
   - Navigate to the backend directory:
     ```bash
     cd backend
     ```
   - Create a virtual environment and activate it:
     ```bash
     python3 -m venv env
     source env/bin/activate  # On Windows: .\env\Scripts\activate
     ```
   - Install dependencies:
     ```bash
     pip install -r requirements.txt
     ```
   - Apply migrations and start the server:
     ```bash
     python manage.py migrate
     python manage.py runserver
     ```

3. **Frontend Setup**:
   - Navigate to the frontend directory:
     ```bash
     cd frontend
     ```
   - Install dependencies:
     ```bash
     npm install
     ```
   - Start the development server:
     ```bash
     npm start
     ```

4. **Mobile Application Setup**:
   - Navigate to the mobile app directory:
     ```bash
     cd mobile
     ```
   - Install dependencies:
     ```bash
     npm install
     ```
   - Run the app:
     ```bash
     react-native run-android  # For Android
     react-native run-ios      # For iOS
     ```

5. **Docker Setup** (Optional):
   - Build and run Docker containers:
     ```bash
     docker-compose up --build
     ```

## Contributing

We welcome contributions! Please read our [CONTRIBUTING.md](CONTRIBUTING.md) for details on the code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or issues, please contact us at support@gruzdogruz.com.
