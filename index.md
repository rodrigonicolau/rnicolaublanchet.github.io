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

<!-- Fancy Dark Mode Toggle Button -->
<button onclick="toggleDarkMode()" id="darkModeToggle" style="position: fixed; top: 10px; right: 10px; padding: 10px 20px; border: none; border-radius: 20px; background-color: #333; color: #fff; font-weight: bold; cursor: pointer; transition: all 0.3s;">
  🌙 Dark Mode
</button>

<style>
  /* Button style for light and dark modes */
  .dark-mode #darkModeToggle {
    background-color: #eee;
    color: #333;
  }
</style>

<script>
  function toggleDarkMode() {
    document.body.classList.toggle("dark-mode");
    const button = document.getElementById("darkModeToggle");
    if (document.body.classList.contains("dark-mode")) {
      button.innerHTML = "☀️ Light Mode";
    } else {
      button.innerHTML = "🌙 Dark Mode";
    }
  }
</script>
