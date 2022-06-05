<script>
  import Icon from 'svelte-awesome';
  import SidebarIcon from './SidebarIcon.svelte';
</script>


<svelte:head>
	<script src="https://kit.fontawesome.com/3ca07819d7.js" crossorigin="anonymous"></script>
</svelte:head>

<div class="fixed top-0 left-0 h-screen w-16 m-0 flex flex-col bg-gray-900 text-white shadow-lg">
  <SidebarIcon icon="fa-solid fa-house" title="Home"/>
  <SidebarIcon icon="fa-solid fa-briefcase" title="Portfolio"/>
  <SidebarIcon icon="fa-solid fa-user" title="About Me"/>
</div>