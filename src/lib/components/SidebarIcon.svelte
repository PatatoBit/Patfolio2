<script>
  export let icon;
  export let title;
</script>

<div class="icon group">
  <i class="fa-xl {icon}"></i>

  <span class="tooltip group-hover:scale-100">
      {title}
  </span>
</div>