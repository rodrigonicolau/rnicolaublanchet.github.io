<div style="text-align: center; max-width: 800px; margin: 0 auto; padding: 20px;">
  <!-- Name centered above Profile Picture -->
  <div style="display: flex; flex-direction: column; align-items: center;">
    <p style="font-weight: bold; font-size: 1.8em; margin-bottom: 10px; text-align: center;">Rodrigo Nicolau Blanchet </p>
    <img src="https://github.com/rodrigonicolau/rodrigonicolau.github.io/blob/main/profile.jpg?raw=true" alt="Profile Picture" width="150" style="border-radius: 50%; aspect-ratio: 1 / 1; object-fit: cover; margin-bottom: 20px;">
  </div>
</div>

<style>
  header {
    display: none;
  }
</style>

<style>
  footer {
    display: none;
  }
</style>

<style>
  
/* Default light mode styles */
  body {
    background-color: #ffffff;
    color: #000000;
  }

/* Dark mode styles, if system preference is dark */
  @media (prefers-color-scheme: dark) {
    body {
      background-color: #121212;
      color: #ffffff;
    }
  }

/* Additional dark mode styling */
  .dark-mode {
    background-color: #121212;
    color: #ffffff;
  }
  .dark-mode a {
    color: #bb86fc;
  }
</style>

<!-- Dark Mode Button -->
<button onclick="toggleDarkMode()" id="darkModeButton" style="position: fixed; top: 10px; right: 10px; padding: 10px; border: none; background-color: transparent; cursor: pointer; font-size: 20px;">
  🌙
</button>

<style>
  .dark-mode {
    background-color: #121212;
    color: #ffffff;
  }
</style>

<script>
  function toggleDarkMode() {
    document.body.classList.toggle("dark-mode");
    const button = document.getElementById("darkModeButton");
    if (document.body.classList.contains("dark-mode")) {
      button.innerHTML = "☀️"; // Sun icon for light mode
    } else {
      button.innerHTML = "🌙"; // Moon icon for dark mode
    }
  }
</script>


