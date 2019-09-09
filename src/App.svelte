<script>
  let color = "#0000";
</script>

<div id="container">
  <svg
    viewBox="0 0 1000 1000"
    xmlns="http://www.w3.org/2000/svg"
    id="product-svg">
    <path
      style={`fill: ${color};`}
      d="M168.333 342.5l3.334 22.5L175 740.002l6.667 183.334 76.667
      33.333h135l331.667 3.333 65-6.666 13.334-41.667 26.666-535
      5-28.334-85-50-48.333-51.667-43.334-125-36.666-73.334L545
      11.667l-66.667-5L400.001 30l-51.43 74.762L283.81 252.38 272.38
      280l-104.048 62.5z" />
    <path
      d="M373.57 107.766l7.86 86.52 38.572 72.858 25.714 17.143 41.429 10 52.857
      2.857 32.857-8.571 21.429-21.43 35.714-84.285
      7.143-25.715-14.286-52.857-18.571-20-42.857-12.857-60-8.572-57.144
      2.858L407.144 80l-33.573 27.766z"
      id="space" />
  </svg>

  <img id="background-image" src="original.jpg" alt="" />
</div>

<h2>Pick a color</h2>
<input type="color" bind:value={color} id="picker" />
<p>&copy; 2019 Gabriel Lazcano @gnugl</p>
