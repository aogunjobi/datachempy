# DataChemPy

DataChemPy is a comprehensive big data database toolset designed to efficiently manage and share chemical and materials data. This toolset enables users to set up a database, populate it with user-provided data, and perform searches, visualizations, and data sharing via the web.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)

## Installation

### Prerequisites

- Python 3.11 or higher
- pip (Python package installer)
- MongoDB Atlas or another MongoDB instance

### Steps

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/datachempy.git
    cd datachempy
    ```

2. Create and activate a virtual environment:

    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Set up your MongoDB connection by configuring the `config.yaml` file with your MongoDB Atlas connection details.

5. Install JSmol:

    Download JSmol from [JSmol download page](http://wiki.jmol.org/index.php/Jmol_Download).

    Place the downloaded JSmol files in the `static/jsmol` directory of the project.

6. Run the application:

    ```bash
    python app.py
    ```

## Usage

Once the application is running, you can access it by navigating to `http://127.0.0.1:5000` in your web browser. The application allows you to:

- Upload and manage chemical and materials data.
- Perform complex searches on the data.
- Visualize molecular structures using JSmol.
- Share data and visualizations with other users.

## Features

- **Database Management**: Efficiently manage large volumes of chemical and materials data.
- **Data Upload**: Populate the database with user-provided data.
- **Search Functionality**: Perform complex searches to find specific data points.
- **Visualization**: Visualize molecular structures using JSmol.
- **Data Sharing**: Share data and visualizations with other users through the web interface.
