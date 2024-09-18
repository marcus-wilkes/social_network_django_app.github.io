
## Social Network Developer App


## Project Overview

The **Social Network Developer App** is a modern social networking platform designed specifically for developers. It connects developers by providing a robust environment for sharing ideas, building connections, and exploring new opportunities. This application combines the power of Django and Django-Rest-Framework for the backend with a dynamic React frontend, offering a seamless and interactive user experience.

## Technologies

**Frontend:**
- **React**: A JavaScript library for building user interfaces.
- **Redux**: A state management library for React applications.
- **React-Router-Dom**: For routing and navigation.
- **Axios**: For making HTTP requests.
- **Moment**: For date and time manipulation.
- **React-Moment**: Integration with Moment.js for React.

**Backend:**
- **Django**: A high-level Python web framework for building the backend.
- **Django-Rest-Framework**: A powerful and flexible toolkit for building Web APIs.

**Development Tools:**
- **Node.js** and **npm**: For managing JavaScript dependencies and running development scripts.
- **Python** and **pip**: For managing Python dependencies and running Django commands.

## Installation

### Frontend (React)

1. Install dependencies:

    ```bash
    npm install
    ```

2. Start the development server:

    ```bash
    npm start
    ```

3. Build for production:

    ```bash
    npm run build
    ```

   - The `proxy` is set to `http://localhost:8000` in `package.json`. You can configure `axios.defaults.baseURL` to `https://api.example.com` if needed.

### Backend (Django)

1. Clone the repository:

    ```bash
    git clone https://github.com/devmahmud/DevConnector-Django.git
    ```

2. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

3. Configure GitHub API credentials:

    Edit `settings.py` and add your GitHub credentials:

    ```python
    GIT_CLIENT_ID = 'your github client id'
    GIT_CLIENT_SECRET = 'your github client secret'
    ```

4. Run database migrations:

    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

5. Start the development server:

    ```bash
    python manage.py runserver
    ```

   The server will be accessible at `http://127.0.0.1:8000`.

   - Ensure to whitelist your host origin using `django-cors-headers` for production. [See Documentation](https://pypi.org/project/django-cors-headers/)

### Testing

To run the tests:

```bash
python manage.py test
```
### License
This project is licensed under the MIT License.

### Author
Developed by Marcus Wilkes
