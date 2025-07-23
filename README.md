# Exam Analyzer

**Exam Analyzer** is a full-stack software application designed to assist educators and institutions in analyzing and visualizing examination results. It provides a streamlined workflow for uploading, processing, and interpreting student performance data, enabling data-driven insights through statistical analysis and interactive visualizations.

---

## Key Features

* Upload exam result files in Excel format (`.xlsx`)
* Perform descriptive and statistical analysis on student performance
* Generate visualizations to represent data distributions, trends, and summaries
* Web-based interface with responsive design
* RESTful API architecture for backend/frontend integration

---

## Technology Stack

* **Frontend**: HTML, CSS, JavaScript, Node.js (with npm)
* **Backend**: Python, Flask, Pandas, Keras, OpenPyXL
* **Data Format**: Excel

---

## Backend Setup Instructions

To set up and run the backend server locally:

1. **Install Python Dependencies**

   Ensure Python is installed. Then, from the root of the backend directory, run:

   ```bash
   pip install -r requirements.txt
   ```

2. **Start the Server**

   Execute the following command to launch the backend server:

   ```bash
   python server.py
   ```

3. **Port Configuration**

   The backend runs on port `3001` by default. Ensure this port is available. If it's in use, either stop the conflicting service or modify the port in `server.py`.

4. **API Access**

   After launching the server, backend endpoints will be accessible via `http://localhost:3001`. API routes are defined in `server.py`.

---

## Frontend Setup Instructions

To set up and run the frontend interface:

1. **Install Node.js Dependencies**

   Navigate to the frontend directory and run:

   ```bash
   npm install
   ```

2. **Start the Development Server**

   Launch the frontend application with:

   ```bash
   npm run dev
   ```

3. **Access the Web Application**

   Once the development server is running, open a browser and navigate to:

   ```
   http://localhost:3000
   ```

   Ensure the backend is also running to enable full functionality.

---

## Python Dependencies

The following libraries are required by the backend (as listed in `requirements.txt`):

```
blinker==1.6.2
certifi==2023.7.22
cffi==1.15.1
click==8.1.7
colorama==0.4.6
et-xmlfile==1.1.0
Flask==3.0.0
Flask-Cors==4.0.0
itsdangerous==2.1.2
Jinja2==3.1.2
keras==2.14.0
MarkupSafe==2.1.3
numpy==1.26.0
openpyxl==3.1.2
pandas==2.1.1
pycparser==2.21
Pygments==2.16.1
python-dateutil==2.8.2
pytz==2023.3.post1
PyYAML==6.0.1
six==1.16.0
tzdata==2023.3
Werkzeug==3.0.0
```

---

## Example Use Cases

* Perform detailed analysis of results for each academic module
* Determine student progression or resit status based on the University of Nottingham's progression regulations
* Generate comprehensive reports on overall academic performance for the entire cohort year

---

## Contributing

Contributions are welcome. If you would like to contribute, please fork the repository and submit a pull request. For major changes, open an issue first to discuss the proposal.

---

## License

This project is licensed under the **Apache License 2.0**. See the [LICENSE](LICENSE) file for full terms and conditions.

---

Let me know if you'd like a matching `LICENSE` file, CI/CD badges, deployment instructions, or usage screenshots.
