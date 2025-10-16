# CSS
Code for CSS
/* GLOBAL RESET & FONT */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Arial', sans-serif;
}

/* BODY/BACKGROUND STYLING */
body {
    background: linear-gradient(120deg, #f0f2f5, #d9e2ec);
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
}

/* MAIN CONTAINER (THE CARD) */
.container {
    background: #fff;
    padding: 50px;
    border-radius: 15px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.15);
    width: 450px; /* Optimal desktop card width */
}

/* HEADER STYLING */
header h1 {
    text-align: center;
    color: #333;
    margin-bottom: 10px;
}

header p {
    text-align: center;
    margin-bottom: 30px;
    font-size: 14px;
}

/* SECTION AND FORM STYLING */
h2 {
    text-align: center;
    color: #555;
    margin-bottom: 20px;
}

form {
    display: flex;
    flex-direction: column;
}

/* Form toggle visibility */
.hidden {
    display: none !important; /* Important ensures JS toggling works */
}

/* INPUT GROUPS */
.input-group {
    margin-bottom: 15px;
    display: flex;
    flex-direction: column;
}

label {
    font-size: 13px;
    color: #555;
    margin-bottom: 5px;
}

input[type="text"], 
input[type="password"], 
input[type="email"], 
input[type="tel"] {
    padding: 12px 15px;
    border: 1px solid #ccc;
    border-radius: 8px;
    font-size: 14px;
    transition: border-color 0.3s ease;
}

/* Focus state for inputs */
input:focus {
    border-color: #0072c6;
    outline: none;
}

/* CHECKBOX STYLING */
.checkbox-label {
    display: flex;
    align-items: center;
    font-size: 14px;
    color: #555;
    cursor: pointer;
}

.checkbox-label input[type="checkbox"] {
    margin-right: 8px;
    /* Reset input padding for checkboxes */
    padding: 0; 
    width: auto
