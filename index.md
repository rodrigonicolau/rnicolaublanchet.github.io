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
  

<!-- Dark Mode Button -->
<button onclick="toggleDarkMode()" id="darkModeButton" style="position: fixed; top: 10px; right: 10px; padding: 10px; border: none; background: transparent; cursor: pointer;">
  <span id="icon" class="sun-icon"></span>
</button>

<style>
  /* Sun and Moon Icon Styling */
  #icon {
    display: inline-block;
    width: 20px;
    height: 20px;
    transition: all 0.3s;
  }

  /* Sun Shape (Light Mode) */
  .sun-icon {
    background-color: #FFD700;
    clip-path: polygon(50% 0%, 61% 35%, 98% 35%, 68% 57%, 79% 91%, 50% 70%, 21% 91%, 32% 57%, 2% 35%, 39% 35%);
  }

  /* Moon Shape (Dark Mode) */
  .moon-icon {
    background-color: #4B0082;
    clip-path: circle(50% at 70% 30%);
  }

  /* Hover Effect */
  #darkModeButton:hover #icon {
    background-color: #FFA500;
  }

  /* Dark Mode Styling */
  .dark-mode {
    background-color: #121212;
    color: #ffffff;
  }
</style>

<script>
  function toggleDarkMode() {
    document.body.classList.toggle("dark-mode");
    const icon = document.getElementById("icon");
    icon.classList.toggle("sun-icon");
    icon.classList.toggle("moon-icon");
  }

  // Set initial icon based on system preference
  document.getElementById("icon").classList.add("sun-icon");
</script>
