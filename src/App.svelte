<script>
  import Nested from "./Nested.svelte";

  const bio = {
    name: 'Kevin',
    age: '33'
  }
</script>

<Nested name={bio.name} age={bio.age} />