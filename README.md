/* General Reset and Font Setup */
body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f7f6; /* Light background */
    color: #333; /* Dark text */
    line-height: 1.6;
}

/* Header Styling */
header {
    background-color: #3498db; /* A nice blue header */
    color: white;
    padding: 60px 20px;
    text-align: center;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

header h1 {
    margin-top: 0;
    font-size: 2.5em;
}

header p {
    font-size: 1.1em;
    opacity: 0.9;
}

/* Main Content Layout */
main {
    max-width: 800px;
    margin: 40px auto;
    padding: 0 20px;
}

/* Section Styling */
section {
    background-color: white;
    padding: 30px;
    margin-bottom: 30px;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
}

section h2 {
    color: #2c3e50;
    border-bottom: 2px solid #ecf0f1;
    padding-bottom: 10px;
    margin-top: 0;
}

/* Links/Navigation Styling */
.links nav {
    display: flex;
    flex-direction: column; /* Stack links on mobile */
    gap: 15px;
}

.links a {
    display: block; /* Make links full width */
    padding: 12px 20px;
    background-color: #ecf0f1;
    color: #3498db;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s, color 0.3s;
    text-align: center;
    font-weight: bold;
}

.links a:hover {
    background-color: #3498db;
    color: white;
}

/* Footer Styling */
footer {
    text-align: center;
    padding: 20px;
    color: #777;
    font-size: 0.9em;
    border-top: 1px solid #eee;
}

/* Media Query for Larger Screens (Desktop) */
@media (min-width: 600px) {
    .links nav {
        flex-direction: row; /* Horizontal links on desktop */
        justify-content: space-around;
    }
}
