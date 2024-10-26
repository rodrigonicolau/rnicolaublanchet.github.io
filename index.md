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

<!-- Dark Mode Toggle Button -->
<button onclick="toggleDarkMode()" id="darkModeButton" style="position: fixed; top: 10px; right: 10px; padding: 10px; border: none; background: transparent; cursor: pointer;">
  <span id="icon" class="sun"></span>
</button>

<style>
  /* Sun and Moon Icon Styling */
  #icon {
    display: inline-block;
    width: 24px;
    height: 24px;
    border-radius: 50%;
    transition: background-color 0.3s, box-shadow 0.3s;
  }

  /* Sun Style (Light Mode) */
  .sun {
    background-color: #FFD700;
    box-shadow: 0 0 8px #FFD700;
  }

  /* Moon Style (Dark Mode) */
  .moon {
    background-color: #4B0082;
    box-shadow: 0 0 8px #4B0082;
  }

  /* Hover Effect */
  #darkModeButton:hover #icon {
    background-color: #FFA500; /* Orange on hover */
    box-shadow: 0 0 8px #FFA500;
  }

  /* Dark Mode Background */
  .dark-mode {
    background-color: #121212;
    color: #ffffff;
  }
</style>

<script>
  function toggleDarkMode() {
    document.body.classList.toggle("dark-mode");
    const icon = document.getElementById("icon");
    icon.classList.toggle("sun");
    icon.classList.toggle("moon");
  }

  // Set initial icon to sun or moon based on system preference
  document.getElementById("icon").classList.add("sun");
</script>
