<script lang="ts">
    import HeroTitle from '$lib/HeroTitle.svelte';
    import BackBreadcrum from '$lib/BackBreadcrum.svelte';
</script>    

<svelte:head>
    <title>Hotten Technology Group</title>
</svelte:head>

<HeroTitle title="Hotten Technology Group"/>
<section class="content">
    <div class="gweb-text-layout">
        <p>
            Hotten Technology is an organisation providing computer and IT services in the UK. We currently operate two parent services:
        </p>

        <h2>Hotten UK</h2>
        <p class="gweb-link-black">
            <a href="https://hotten.uk">Hotten UK</a> provides personal website hosting and design. Examples include <a href="https://george.hotten.uk">George's personal website</a> and his education related publishings.
        </p>    

        <h2>Hotten Cloud</h2>
        <p class="gweb-link-black">
            <a href="https://hotten.cloud">Hotten Cloud</a> provides the infrastructure used to host Hotten UK, alongside many services used by family and friends.
        </p>    
    </div>
</section>
