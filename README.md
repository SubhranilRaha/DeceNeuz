# DeceNeuz
Decentralized news application

## Steps to Run the Application
1. Clone this repository to your machine:
   ```bash
   git clone https://github.com/your-username/DeceNeuz.git
   ```

2. Use Docker to run the 'Appwrite' backend server on your machine. Navigate to the root directory and run:
   ```bash
   docker-compose up
   ```

3. Download all the dependencies:
   ```bash
   npm install
   ```

4. Set the environment variables for Appwrite. Obtain the necessary variables by visiting 'localhost:login' after running the Appwrite server.

   Add these variables to your project by creating a `.env` file in the root directory and setting the values:

   Example `.env` file:
   ```
   APPWRITE_ENDPOINT=http://localhost/v1
   APPWRITE_PROJECT_ID=123456789
   APPWRITE_API_KEY=secret_key
   APPWRITE_COLLECTION_ID=987654321
   ```

Now, you should be ready to run the DeceNeuz application locally.
