# Rusty Response Web

Rusty Response Web is the frontend part of a server monitoring application, that provides a user-friendly interface for managing and monitoring, including features for user authentication, server management, and notifier configuration. This repository is part of a larger project, paired with a separate API repository.

📍Live Preview(soon)

## Features

- **User Authentication**: Login page with form validation for secure access.
- **Server Management**:
  - Server table displaying general information.
  - Detailed view for individual servers.
  - Forms for creating, editing, and deleting servers.
- **Notifier Management**:
  - List of notifiers for specific servers.
  - Forms for creating, editing, and deleting notifiers.
- **Pagination**: Implemented for server and notifier pages to handle large datasets efficiently.

## Planned Features
- Overview page for high-level insights.
- Logs for specific servers.
- Documentation page for user guidance.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/rusty-response/rusty-response-web.git
   cd rusty-response-web
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Configure environment variables:
   - Create a `.env` file in the root directory if it does not exist.
   - Add necessary variables (e.g., API endpoint for the backend):
     
     ```env
     VITE_API_URL=http://your-api-endpoint
     ```

4. Start the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. Open your browser and navigate to `http://localhost:5173` (or the port specified by Vite).

## Usage

1. **Login**: Access the application via the login page and authenticate with valid credentials.
2. **View Servers**: Navigate to the server table to view general information or select a server for detailed insights.
3. **Manage Servers**: Use the provided forms to create, edit, or delete servers.
4. **Manage Notifiers**: Configure notifiers for specific servers using the notifier management forms.
5. **Navigation**: Use the sidebar for easy access to different sections and pagination for browsing large datasets.

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit (`git commit -m "feat: add your feature"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

## Tech Stack
- **Frontend**: [React](https://react.dev/) + [TypeScript](https://www.typescriptlang.org/)
- **State Management**: [Redux Toolkit](https://redux-toolkit.js.org/)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For issues, feature requests, or questions, please open an issue on the [GitHub Issues page](https://github.com/rusty-response/rusty-response-web/issues).

