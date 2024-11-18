<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Flight Search</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Flight Search</h1>
  </header>
  <main>
    <form id="flight-search-form">
      <label for="origin">Origin:</label>
      <input type="text" id="origin" placeholder="Enter origin city" required>

      <label for="destination">Destination:</label>
      <input type="text" id="destination" placeholder="Enter destination city" required>

      <label for="departure-date">Departure Date:</label>
      <input type="date" id="departure-date" required>

      <button type="submit">Search Flights</button>
    </form>

    <section id="results">
      <h2>Flight Results</h2>
      <ul id="flight-list"></ul>
    </section>
  </main>
  <script src="script.js"></script>
</body>
</html>
