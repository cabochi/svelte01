<script>
  let count = $state(0); // --> rune $state

  function increment() {
    count++;
  }
</script>

<h1>Counter : {count}</h1>

<button onclick={increment}>Increment</button>


<!-- <script>
  let count = $state(0)
  const increment = () => {
    count += 1
  }
</script>

<button onclick={increment}>
  count is {count}
</button> -->

 