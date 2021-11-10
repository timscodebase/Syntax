<script>
  export let show
  const { number, title } = show
</script>

<li>
  <a href={`/shows/${number}`}>
      #{show.number} - {title}
  </a>
</li>