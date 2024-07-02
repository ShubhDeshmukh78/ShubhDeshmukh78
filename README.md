<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Alarm Clock</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Online Alarm Clock</h1>
        <form id="alarmForm">
            <label for="alarmTime">Set Alarm Time:</label>
            <input type="time" id="alarmTime" required>
            <button type="submit">Set Alarm</button>
        </form>
        <div id="alarmStatus"></div>
    </div>
    <script src="script.js"></script>
</body>
</html>
