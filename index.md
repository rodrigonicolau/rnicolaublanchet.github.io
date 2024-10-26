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
  <span id="icon" style="display: inline-block; width: 20px; height: 20px; border-radius: 50%; background-color: #FFD700;"></span>
</button>

<style>
  /* Sun (Light Mode) Style */
  #icon.light-mode {
    background-color: #FFD700; /* Gold for sun */
    transition: background-color 0.3s;
  }

  /* Moon (Dark Mode) Style */
  #icon.dark-mode {
    background-color: #4B0082; /* Indigo for moon */
    transition: background-color 0.3s;
  }

  /* Hover Effect */
  #darkModeButton:hover #icon {
    background-color: #FFA500; /* Orange for hover */
  }

  /* Dark Mode Styles */
  .dark-mode {
    background-color: #121212;
    color: #ffffff;
  }
</style>

<script>
  function toggleDarkMode() {
    document.body.classList.toggle("dark-mode");
    const icon = document.getElementById("icon");
    if (document.body.classList.contains("dark-mode")) {
      icon.classList.replace("light-mode", "dark-mode"); // Moon color for dark mode
    } else {
      icon.classList.replace("dark-mode", "light-mode"); // Sun color for light mode
    }
  }
  // Set initial icon style
  document.getElementById("icon").classList.add("light-mode");
</script>

