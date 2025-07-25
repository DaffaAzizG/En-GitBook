# Redirecting to Language Selection

<div id="loading" style="font-size: 1.2em; margin-bottom: 1em;">
  Redirecting to language selection page...
</div>

<div id="fallback" style="display:none;">
  If you are not redirected automatically, click [here](../README.md).
</div>

<script>
  // Show fallback link after 3 seconds if redirect fails
  setTimeout(function () {
    document.getElementById('fallback').style.display = 'block';
  }, 3000);

  // Redirect to root (language selection)
  setTimeout(function () {
    window.location.href = "/";
  }, 1000);
</script>
