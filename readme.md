# Sticky Notes

## Introduction
Welcome to Sticky Notes, a user-centric bulletin board application built with Python and Django, styled in an 80s cyberpunk theme. This project is my final milestone in the software engineering boot camp with HyperionDev. Before starting this course, I had no programming or software engineering experience. It's been a tough but rewarding journey, and I'm excited to share my first major project with you. I see this as the first step in a new path of building and experimenting with software.

## Features
- **Create Note**: Users can post a note from the index view. A note includes a title, main content, an author field, and an auto-generated timestamp.
- **View Notes**: The index view displays all notes with their titles. Clicking on a title takes you to the detailed view of the note.
- **Edit Note**: In the detailed view, users can edit the note. The original content is displayed in a form for easy updating.
- **Delete Note**: Notes can be deleted from the detailed view after confirming the action.
- **Validation**: Notes require a title to ensure proper hyperlink functionality.

## Installation
To run Sticky Notes locally, follow these steps for either Windows or Mac:

### Windows
1. **Clone the repository**:
    ```bash
    git clone https://github.com/tentomoosh/sticky-notes.git
    cd sticky-notes
    ```

2. **Set up a virtual environment**:
    ```bash
    python -m venv venv
    venv\Scripts\activate
    ```

3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Apply migrations**:
    ```bash
    python manage.py migrate
    ```

5. **Run the development server**:
    ```bash
    python manage.py runserver
    ```

6. **Access the application**:
    Open your web browser and go to `http://127.0.0.1:8000/`.

### Mac
1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/sticky-notes.git
    cd sticky-notes
    ```

2. **Set up a virtual environment**:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Apply migrations**:
    ```bash
    python3 manage.py migrate
    ```

5. **Run the development server**:
    ```bash
    python3 manage.py runserver
    ```

6. **Access the application**:
    Open your web browser and go to `http://127.0.0.1:8000/`.

## Usage
- **Posting a Note**: From the index view, click on the "Add Note" button. Fill in the title, main content and Author then submit the form.
- **Viewing a Note**: Click on the note's title in the index view to see the detailed view.
- **Editing a Note**: In the detailed view, click on the "Edit" button, modify the note's content, and save changes.
- **Deleting a Note**: In the detailed view, click on the "Delete" button and confirm the action.

## Additional Information
- **Defensive Programming**: The application ensures that every note has a title, which is crucial for navigation.
- **User Experience**: The 80s cyberpunk theme provides a unique and visually appealing interface that enhances user engagement.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements
- HyperionDev for the boot camp training.
- All the open-source libraries and tools that made this project possible.

