<div style="text-align: left; max-width: 800px; margin: 0 auto; padding: 20px;">
  <!-- Name centered above Profile Picture -->
  <div style="display: flex; flex-direction: column; align-items: flex-start;">
    <p class="title">Rodrigo</p>
    <p class="title">Nicolau</p>
    <p class="title">Blanchet</p>
    <img src="https://github.com/rodrigonicolau/rodrigonicolau.github.io/blob/main/profile.jpg?raw=true" alt="Profile Picture" width="150" style="border-radius: 50%; aspect-ratio: 1 / 1; object-fit: cover; margin-bottom: 20px;">
  </div>
</div>

<style>
  /* Title Font and Color */
  .title {
    font-weight: bold;
    font-size: 1.8em;
    margin-bottom: 8px;
    color: navy;
    font-family: 'Arial', sans-serif; /* Replace with desired font */
  }

  /* Dark Mode Title Color */
  body.dark-mode .title {
    color: #ffffff;
  }

  /* Light and Dark Mode Backgrounds */
  body.light-mode {
    background-color: #ffffff;
    color: #000000;
  }

  body.dark-mode {
    background-color: #121212;
    color: #ffffff;
  }
</style>


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


<!-- Dark Mode Toggle Button -->
<button onclick="toggleDarkMode()" id="darkModeButton" style="position: fixed; top: 10px; right: 10px; padding: 10px; border: none; background: transparent; cursor: pointer; font-size: 20px;">
  <span id="icon">🌒</span>
</button>

<style>
  /* Light Mode (default) */
  body.light-mode {
    background-color: #ffffff;
    color: #000000;
  }

  /* Dark Mode Styling */
  body.dark-mode {
    background-color: #121212;
    color: #ffffff;
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
