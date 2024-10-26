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
<label class="dark-mode-switch">
  <input type="checkbox" onclick="toggleDarkMode()" id="darkModeToggle">
  <span class="slider"></span>
</label>

<style>
  
  /* Switch container */
  .dark-mode-switch {
    position: fixed;
    top: 10px;
    right: 10px;
    width: 50px;
    height: 25px;
    display: inline-block;
  }

  /* Hide default checkbox */
  .dark-mode-switch input {
    opacity: 0;
    width: 0;
    height: 0;
  }

  /* Slider styling */
  .slider {
    position: absolute;
    cursor: pointer;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-color: #ccc;
    border-radius: 34px;
    transition: .4s;
  }

  /* Dark mode color */
  .slider:before {
    position: absolute;
    content: "";
    height: 18px;
    width: 18px;
    left: 4px;
    bottom: 3.5px;
    background-color: white;
    border-radius: 50%;
    transition: .4s;
  }

  /* Slider color when checked */
  input:checked + .slider {
    background-color: #333;
  }

  /* Slider position when checked */
  input:checked + .slider:before {
    transform: translateX(26px);
  }

  /* Dark mode styling */
  .dark-mode {
    background-color: #121212;
    color: #ffffff;
  }
</style>

<script>
  function toggleDarkMode() {
    document.body.classList.toggle("dark-mode");
  }
</script>
