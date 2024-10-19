<script type="module">
  document.querySelectorAll('a[href="#_search-input"]').forEach(el => {
    if (!el.dataset.done) {
      el.addEventListener('click', () => document.getElementById('_search-input').focus());
      el.dataset.done = '';
    }
  });
</script>
