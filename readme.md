# How to Run the Application

Welcome to our application! Below are the steps to get it up and running on your local machine.

## Steps

1. **Clone the Repository**: Start by creating a local copy of the project on your machine.

    ```bash
    git clone https://github.com/Jeshan04/pancard_tampering_detection.git
    ```

2. **Navigate to Project Directory**: Open your command prompt or terminal and change your current directory to the folder where you can find the `app.py` file.

    ```bash
    cd path/to/project
    ```

3. **Create Environment**: Create a virtual environment using conda. Replace `<env-name>` with your desired environment name.

    ```bash
    conda create -n <env-name> python=3.8
    ```

4. **Activate Environment**: Activate the newly created environment.

    ```bash
    conda activate <env-name>
    ```

5. **Install Dependencies**: Install the required dependencies listed in the `requirements.txt` file.

    ```bash
    python -m pip install -r requirements.txt
    ```

6. **Run the Application**: Start the application by running the following command:

    ```bash
    python app.py
    ```

7. **Access the Application**: Once the application is running, you will receive a URL. Copy this URL and paste it into your web browser.

8. **Test with Sample Data**: Use the provided `sample_data` folder to test the application with images.
