<script lang="ts">
    import "../css/global.scss";
</script>

<div class="wrapper">
    <slot />
</div>

<style>
    .wrapper {
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        min-height: 100vh;
    }
</style>
