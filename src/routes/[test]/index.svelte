<script lang="ts">
    import { page } from "$app/stores";
      $: test = $page.params.test;
</script>

Your {test} value.