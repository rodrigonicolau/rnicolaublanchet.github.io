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


<!-- Dark Mode Toggle Button -->
<button onclick="toggleDarkMode()" id="darkModeButton" style="position: fixed; top: 10px; right: 10px; padding: 10px; border: none; background: transparent; cursor: pointer; font-size: 20px;">
  <span id="icon">🌙</span>
</button>

<style>
  /* System preference for dark mode */
  @media (prefers-color-scheme: dark) {
    body {
      background-color: #121212;
      color: #ffffff;
    }
    #icon {
      content: "☀️"; /* Start with sun icon if dark mode */
    }
  }
  /* Light mode as the default */
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
      icon.textContent = "☀️"; // Switch to sun for dark mode
    } else {
      icon.textContent = "🌙"; // Switch to moon for light mode
    }
  }

  // Set initial mode based on system preference
  if (window.matchMedia && window.matchMedia('(prefers-color-scheme: dark)').matches) {
    document.body.classList.add("dark-mode");
    document.getElementById("icon").textContent = "☀️";
  }
</script>


