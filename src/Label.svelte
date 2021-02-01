<script lang="ts">
  export let label: any = 'A Label';
  export let id: string | undefined = undefined;
</script>

<!-- svelte-ignore a11y-label-has-associated-control -->
<label id={id ? id : undefined}>{label}!!!!!!</label>
