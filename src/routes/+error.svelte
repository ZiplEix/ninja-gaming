<script>
    import { page } from '$app/stores';
</script>

<div class="error">
    <h1>Oops!</h1>
    <p>{$page.status}: {$page.error.message}</p>
    <a href="/guides">View all guides...</a>
</div>

<style>
    .error {
        text-align: center;
        margin-bottom: 60px;
    }
</style>
