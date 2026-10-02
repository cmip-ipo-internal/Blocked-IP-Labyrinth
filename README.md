# Blocked-IP-Labyrinth

<p>Your IP address is: <span id="ip">Loading...</span></p>

<script>
  // Fetches IP data and displays it in the HTML span above
  fetch('https://ipify.org')
    .then(response => response.json())
    .then(data => document.getElementById('ip').textContent = data.ip);
</script>
