<script>
	import Button from "$lib/components/Button.svelte";

    const dl = "https://lkaktaupduyplarvdblz.supabase.co/storage/v1/object/sign/good-bucket/anon4u-release.apk?token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJnb29kLWJ1Y2tldC9hbm9uNHUtcmVsZWFzZS5hcGsiLCJpYXQiOjE3MDI3Nzk4NDQsImV4cCI6MTczNDMxNTg0NH0.oGAIqA4K8t39ta_HY5ioBHtml8FuA4bEbzb1hWr8JOQ&t=2023-12-17T02%3A24%3A03.283Z";
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