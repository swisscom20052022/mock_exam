# How to Run MkDocs Server

To run the MkDocs development server, follow these steps:

1. **Install Dependencies**:
   Ensure you have Python installed. Then, install the required dependencies using:
   ```
   pip install -r requirements.txt
   ```

2. **Run the MkDocs Server**:
   Use the following command to start the MkDocs development server:
   ```
   python -m mkdocs serve
   ```

3. **Access the Server**:
   Open your web browser and navigate to:
   ```
   http://127.0.0.1:8000
   ```

This will display your MkDocs site locally.

4. **Deploy to GitHub Pages**:
    ```bash
    mkdocs gh-deploy --clean
    ```