# Stats Widget
A compact widget designed to display real-time statistics fetched from a backend service.

## Features
- **Clean UI**: Simple and intuitive interface for easy data visualization.
- **Customizable**: Configurable API URL to connect with different backend services.

## Configuration
The Stats Widget requires some basic setup to function properly. The configuration is handled through environment variables, which should be placed in a `.env` file located in the project's root directory.

### Environment Variables
```env
API_URL=http://localhost:5053/api/Event/GetAllEventCounts  # URL of your Stats Backend API endpoint.
```

## Usage

1. **Clone the Repository**
   ```bash
   git clone https://github.com/BBB-XYZ/DefaultWidgetStore.git
   cd Stats-Widget
   ```

3. **Run the Widget**
   ```bash
   docker compose up
   ```

## Notes

- **Prerequisites**: Ensure your Stats Backend is running and accessible at the specified API URL.
- **Setup**: After setting up the configuration, restart the widget to apply changes.
- **Troubleshooting**: If data isn't loading, check network permissions or verify the backend is responding correctly.
