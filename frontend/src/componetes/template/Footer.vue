<template>
	<footer class="Footer">
        <span>Copyright <strong>Vks</strong>2023-</span>
    </footer>
</template>

<script>
export default {
	name: "Footer",
}
</script>

<style>
    .Footer{
        grid-area: footer;
        background-color: #ddd;
        color: #333;

        display: flex;
        align-items: center;
        justify-content: flex-end;
        padding-right: 10px;
    }
</style>