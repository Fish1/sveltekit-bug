<script lang="ts">
    import { page } from '$app/stores';
    // using this $page will cause a bug?
    $page;
</script>

<slot />