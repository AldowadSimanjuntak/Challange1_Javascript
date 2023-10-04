# Challange1_Javascript
Bank Account Web Application
Overview
This is a simple web application that allows users to manage their bank account balance. Users can add or subtract funds from their account, and the current balance is displayed on the screen. The application uses HTML, CSS, and JavaScript to provide this functionality.

How to Use
Open the index.html file in your web browser.

You will see a webpage titled "Bank Account" with the current balance displayed as "Saldo saat ini: Rp.<span id="saldoDisplay">0</span>."
To add funds to your account, click the "Tambah Saldo" button. A prompt will appear asking you to enter the amount you want to add. Enter a valid numerical value and click "OK." The balance will be updated, and the new balance will be displayed on the screen. Your balance will also be stored locally, so it will persist even if you close the browser.
To subtract funds from your account, click the "Kurangi Saldo" button. A similar prompt will appear, asking you to enter the amount you want to subtract. Enter a valid numerical value and click "OK." The balance will be updated, and the new balance will be displayed on the screen. Just like adding funds, your balance will be stored locally.

Code Explanation
The JavaScript code for this application is located in bank_account.js. It handles the logic for adding and subtracting funds and storing the balance in local storage.
The current balance is displayed using the <span> element with the id "saldoDisplay."
The application also uses an external CSS file (styles.css) for styling.

Local Storage
The application uses local storage to persist the user's balance. This means that even if you close the browser or refresh the page, your balance will be saved and loaded the next time you open the application.

Note
This is a simple demonstration of how a basic banking application might work and is not intended for actual financial transactions. The application does not have any security measures or user authentication.

Please make sure to enter valid numerical values when adding or subtracting funds. Non-numerical inputs will not affect the balance.
