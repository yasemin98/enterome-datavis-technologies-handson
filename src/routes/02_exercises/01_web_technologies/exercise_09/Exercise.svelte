<script>
    function circumference(radius) {
      return 2 * Math.PI * radius;
    }
  
    const radius = 4;
    const circumferenceValue = circumference(radius);
  </script>

  <p> The circumference of a circle with radius {radius}m is {circumferenceValue.toFixed(2)}m. </p>