Works for node 12.22.12 only. Install appropriate version for correct dependency installation


1. clone the repo
    ```
    git clone https://github.com/rehmanis/CSCI571-Stocks-Angular.git
    ```
2. cd to the cloned repo
    
3. Open the .env file and remove the contents in it. Paste the following credentials.
    ```
    TINGO_API_KEY=e3663e8b11344eddc7fb8b0066acd3a06a33871a
    NEWS_API_KEY=a39078652270495d9a0c180fc28302db
    ```


2. Install all dependencies (note make sure you are using node version 12 as stated earlier)
    ```
    npm install
    ```
3.  Build the angular frontend
    ```
    npm run-script ng build
    ```
4. Start server (runs both backend and frontend)
    ```
    npm run devstart
    ```
5. open ```Chrome``` or ```Firefox```. The App can then be started on ```http://localhost:3000/```

