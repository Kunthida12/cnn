body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.container {
    text-align: center;
    background-color: #ffffff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.welcome-box {
    background-color: #d0f0c0;
    border-radius: 15px;
    padding: 10px 20px;
    margin-bottom: 20px;
}

.checkboxes {
    margin-bottom: 20px;
}

.checkboxes label {
    display: block;
    margin: 10px 0;
    font-size: 18px;
}

.checkboxes input[type="checkbox"] {
    margin-right: 10px;
}

.note {
    color: red;
    font-size: 16px;
    margin-bottom: 20px;
}

button {
    padding: 10px 20px;
    font-size: 16px;
    border: none;
    border-radius: 5px;
    background-color: #4CAF50;
    color: white;
    cursor: pointer;
}

button:disabled {
    background-color: #cccccc;
    cursor: not-allowed;
}
