<a href="{link}">
    <div class="icon-link">
        <div class="icon-link--icon">
            <Icon data="{icon}"/>
        </div>
        <div class="icon-link--title">
            <h3>{title}</h3>
        </div>
    </div>
</a>

<script>
    import Icon from 'svelte-awesome'

    export let icon;
    export let title;
    export let link;
</script>

<style>
    .icon-link {
        display: flex;
    }

    .icon-link--icon {

    }
</style>