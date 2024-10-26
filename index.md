<div style="max-width: 800px; margin: 0 auto; padding: 20px; text-align: left;">
  <!-- Name and Profile Picture -->
  <div style="display: flex; flex-direction: column; align-items: flex-start;">
    <p class="title">Rodrigo Nicolau</p>
    <p class="title">Blanchet</p>
    <img src="https://github.com/rodrigonicolau/rodrigonicolau.github.io/blob/main/profile.jpg?raw=true" alt="Profile Picture" width="150" style="border-radius: 50%; object-fit: cover; margin-bottom: 20px;">
  </div>

  <!-- Introduction Text -->
  <p>Welcome to my page! I am a Predoctoral Fellow in Economics at the University of Zurich.</p>
</div>

<!-- Dark Mode Toggle Button -->
<button onclick="toggleDarkMode()" id="darkModeButton" style="position: fixed; top: 10px; right: 10px; padding: 10px; border: none; background: transparent; cursor: pointer; font-size: 20px;">
  <span id="icon">🌒</span>
</button>

<style>
  /* Title Styling */
  .title {
    font-weight: bold;
    font-size: 1.8em;
    color: navy;
    font-family: 'Arial', sans-serif;
    text-align: left;
  }

  /* Dark Mode Styling */
  .dark-mode {
    background-color: #121212;
    color: #ffffff;
  }
  .dark-mode .title, .dark-mode p {
    color: #ffffff;
  }

  /* Hide Header and Footer */
  header, footer {
    display: none;
  }
</style>

<script>
  // Set initial mode based on system preference
  if (window.matchMedia('(prefers-color-scheme: dark)').matches) {
    document.body.classList.add("dark-mode");
    document.getElementById("icon").textContent = "☀️";
  } else {
    document.body.classList.add("light-mode");
  }

  // Toggle function for light and dark modes
  function toggleDarkMode() {
    document.body.classList.toggle("dark-mode");
    document.body.classList.toggle("light-mode");
    const icon = document.getElementById("icon");
    icon.textContent = document.body.classList.contains("dark-mode") ? "☀️" : "🌒";
  }
</script>

