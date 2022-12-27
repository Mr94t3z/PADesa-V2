# PADesa
PADesa merupakan aplikasi Peminjaman Alat Desa yang dirancang menggunakan Python-Flask dan Bootstrap.

# Here's a step-by-step guide:

1. `Clone` this repository:

```bash
    https://github.com/Mr94t3z/PADesa-V2.git
```

2. Navigate to the `directory` containing the Flask application.
Third, `install` the `required libraries` and `packages` by running the following command:

```bash
pip install -r requirements.txt
```

4. Create a `virtual environment` for the Flask application. This is optional, but it is a good practice to isolate the dependencies of your application from the system's Python packages. To create a `virtual environment`, run the following command:

```bash
python -m venv env
```

5. `Activate` the `virtual environment` by running the following command:

```bash
# On Windows
env\scripts\activate

# On Linux or macOS
source env/bin/activate
```

6. `Run` the Flask application by using the following command:

```bash
flask run
```

This will start the Flask development server, and you should see the following output:

```bash
 * Serving Flask app "app" (lazy loading)
 * Environment: development
 * Debug mode: on
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
 * Restarting with stat
 * Debugger is active!
 * Debugger PIN: 123-456-789
```

7. You can now access the Flask application in your web browser by `visiting` http://127.0.0.1:5000/. 
