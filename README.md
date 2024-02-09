# KNAi



## Description

KNAi is an innovative AI solution designed to enhance the self-assessment process for students. Its three core features include reading and understanding documents, generating quizzes, and correcting these quizzes. Using advanced natural language processing algorithms, KNAi can comprehend various textual documents and generate quizzes from this content. The AI can formulate a range of question types (multiple-choice, true/false, open-ended, etc.), ensuring a personalized learning experience.

## Installation

Follow these steps to set up and run the project:

1. Clone the project from GitHub:

   ```bash
   git clone https://github.com/AndemusGBJ/knai.git
   ```

2. Create a virtual environment and activate it:

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows, use 'venv\Scripts\activate'
   ```

3. Install the required packages from the `requirements.txt` file:

   ```bash
   pip install -r requirements.txt
   ```
If you are getting an error, open the file in install pakeges one by one using :

    ```bash
   pip install <pakage==version>
   ```
4. Run the project:

   ```bash
   python manage.py runserver
   ```

## Usage

To access the project, navigate to [http://localhost:8000/](http://localhost:8000/) in your web browser.

Use the following credentials to log in:

- Username: admin@admin.com
- Password: password@123

Alternatively, you can register to create a new account. Authentication services are still under development; you can test them using Postman. More details can be found [here](https://github.com/AndemusGBJ/knai.git).

## Database

The project is will be using Azure Database while in production. The this development version, use sqlite
To visualize the data, use the `db.sqlite3` file. You can explore it using an SQLite browser or through Visual Studio Code with the necessary extensions installed.

## Important URLs

- Admin: [http://localhost:8000/admin/](http://localhost:8000/admin/)
- Register: [http://localhost:8000/register/](http://localhost:8000/register/)
- Login: [http://localhost:8000/login/](http://localhost:8000/login/)
- Logout: [http://localhost:8000/logout/](http://localhost:8000/logout/)
- Index: [http://localhost:8000/index/](http://localhost:8000/index/)
- Upload Document: [http://localhost:8000/assessments/upload_document/](http://localhost:8000/assessments/upload_document/)
- Set Assessment: [http://localhost:8000/assessments/set-assessment/](http://localhost:8000/assessments/set-assessment/)
- Questionnaire: [http://localhost:8000/assessments/<slug:slug>/questionnaire/](http://localhost:8000/assessments/<slug:slug>/questionnaire/)

Feel free to explore the different functionalities provided by the URLs.

## Contributing

If you would like to contribute to the project, please follow the guidelines in [CONTRIBUTING.md](CONTRIBUTING.md).

## License

This project is licensed under the [LICENSE NAME] - see the [LICENSE.md](LICENSE.md) file for details.
```


