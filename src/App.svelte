<script>
  export let test = "Hello Mr";
  let name = "Kornel";

  let handleChange = event => {
    name = event.target.value;
  };
</script>

<style>
  .test-class {
    color: red;
  }
</style>

<p class="test-class">{test} {name}</p>
<input type="text" on:change={handleChange} value={name} />
