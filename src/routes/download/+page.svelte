<script>
	import Button from "$lib/components/Button.svelte";

    const dl = "https://utovrzivudfhebqdqkia.supabase.co/storage/v1/object/public/downloads/anon4u-release.apk";
</script>
<svelte:head>
    <meta http-equiv="refresh" content="5; url={dl}" />
    <title>Download - anon4u</title>
</svelte:head>

<div class="flex h-full items-center justify-center">
    <div class="flex flex-col space-y-4">
        <h3>Download is now starting in 5 seconds...</h3>
        <p>If not downloading automatically, try clicking Download button below</p>
        <Button color="primary" type="link" href={dl}>Download </Button>
    </div>
</div>
