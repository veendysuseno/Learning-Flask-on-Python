# Flask Hello World

This is a basic Flask application that demonstrates how to create a simple web server using Flask. When accessed, the server responds with a greeting message.

## Requirements

- Python 3.x
- pip
- Flask

## Installation

1. **Clone the repository** (if applicable) or create a new directory for your project.

2. **Install Flask** using pip:

   ```bash
   pip install Flask

   ```

3. Create a file named app.py and paste the following code into it:

```python
from flask import Flask

app = Flask(__name__)

@app.route('/')
def index():
    return "Hello, Flask!"

if __name__ == '__main__':
    app.run()

```

## Running the Application

1. Navigate to the directory containing app.py.
2. Run the application using the Python interpreter:
   ```bash
   python app.py
   ```
3. Open a web browser and go to http://localhost:5000. You should see the message Hello, Flask!.

## Description

- Flask: A lightweight WSGI web application framework in Python.
- app = Flask(name): Creates an instance of the Flask class.
- @app.route('/'): Defines the route for the root URL (/).
- def index(): Function that returns the string "Hello, Flask!" to be displayed on the webpage.
- app.run(): Runs the Flask development server.

## License

- This project is licensed under the MIT License - see the LICENSE file for details.

<hr/>

### Penjelasan dalam Bahasa Indonesia:

- **Requirements**: Daftar pustaka atau alat yang diperlukan untuk menjalankan aplikasi.
- **Installation**: Langkah-langkah untuk menginstal Flask dan menyiapkan aplikasi.
- **Running the Application**: Cara menjalankan aplikasi dan mengaksesnya melalui browser.
- **Description**: Penjelasan singkat mengenai kode dan bagaimana aplikasinya bekerja.
- **License**: Bagian yang menunjukkan lisensi proyek. Anda dapat mengubah atau menghapus bagian ini jika tidak relevan.

Silakan sesuaikan file `README.md` ini sesuai dengan kebutuhan proyek atau preferensi Anda!

<hr/>

#### @Copyright 2018 | About-Flask-on-Python
