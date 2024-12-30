# SpendSense - Expense Tracker Application

SpendSense is a feature-rich expense tracker application built using Flutter for the frontend and FastAPI for the backend. This repository contains the source code and assets needed to develop, build, and deploy the application.

## Features

- **Track Expenses:** Easily log daily expenses and categorize them for better financial management.
- **Budget Management:** Set budgets and monitor spending to stay on track.
- **Visual Insights:** View spending patterns with intuitive charts and graphs.
- **Cross-Platform:** Available for both Android and iOS with a consistent user experience.
- **Backend API:** A robust FastAPI backend ensures secure and efficient data management.

## Screenshots

Below are some screenshots of the application showcasing its functionality:

<img src="https://via.placeholder.com/400" alt="Screenshot 1" width="400">
<img src="https://via.placeholder.com/400" alt="Screenshot 2" width="400">
<img src="https://via.placeholder.com/400" alt="Screenshot 3" width="400">
<img src="https://via.placeholder.com/400" alt="Screenshot 4" width="400">

## Requirements

### Frontend
- Flutter 3.0 or later
- Dart 2.15 or later

### Backend
- Python 3.8 or later
- FastAPI 0.78 or later

## Installation

### Frontend

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/spendsense.git
   ```
2. Navigate to the frontend directory:
   ```bash
   cd spendsense/frontend
   ```
3. Install dependencies:
   ```bash
   flutter pub get
   ```
4. Run the application:
   ```bash
   flutter run
   ```

### Backend

1. Navigate to the backend directory:
   ```bash
   cd spendsense/backend
   ```
2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the FastAPI server:
   ```bash
   uvicorn main:app --reload
   ```
5. The API documentation is available at `http://127.0.0.1:8000/docs`.

## Configuration

- **Frontend Configuration:** Update API endpoints in the `lib/constants/api.dart` file.
- **Backend Configuration:** Set environment variables for database and API keys in a `.env` file.

## Contributing

We welcome contributions from the community! To contribute:

1. Fork this repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request detailing your changes.

Please adhere to the [code of conduct](CODE_OF_CONDUCT.md).

## License

SpendSense is released under the [MIT License](LICENSE).

## Acknowledgments

- Thanks to the Flutter and FastAPI communities for their invaluable tools and resources.
- Special thanks to all contributors who have helped improve this project.

---

Happy coding! For any issues or suggestions, feel free to open an issue in this repository. Your feedback is greatly appreciated.
