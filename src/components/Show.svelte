<script>
  export let show
  const { number, title } = show
</script>

  <a href={`/shows/${number}`}>
    #{show.number} - {title}
  </a>