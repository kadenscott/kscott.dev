<div class="icon-link">
    <div class="icon-link--icon">
        <Icon data="{icon}" scale="10"/>
    </div>
    <div class="icon-link--title">
        <h1>{title}</h1>
    </div>
</div>

<script>
    import Icon from 'svelte-awesome'

    export let icon;
    export let title;
    export let link;
</script>

<style>
    .icon-link {
        display: flex;
        flex-direction: column;
        background-color: var(--fg);
        border-radius: 0.5em;
        box-shadow: 5px 5px 5px #222;
        padding: 3em 5em;
        align-items: center;
        transition: transform 0.3s ease-in-out;
    }

    .icon-link--icon {
        color: var(--fg-light);
    }

    .icon-link--icon:visited {
    }

    .icon-link--title {
        color: var(--fg-light);
    }

    .icon-link:hover {
        transform: translateY(-1em);
    }
</style>