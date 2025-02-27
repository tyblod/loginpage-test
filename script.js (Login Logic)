document.getElementById("login-form").addEventListener("submit", function(event) {
    event.preventDefault(); // Prevent form submission

    const username = document.getElementById("username").value;
    const password = document.getElementById("password").value;

    if (username === "admin" && password === "password") {
        alert("Login successful!");
        window.location.href = "dashboard.html"; // Redirect after login
    } else {
        document.getElementById("error-message").innerText = "Invalid credentials!";
    }
});
