<script>
	import '../app.pcss';
  import { AppShell } from '@skeletonlabs/skeleton';
</script>

<AppShell>
  <svelte:fragment slot="header">
  </svelte:fragment>
  <svelte:fragment slot="sidebarLeft">
  </svelte:fragment>
  <svelte:fragment slot="sidebarRight">
  </svelte:fragment>
  <slot />
</AppShell>
