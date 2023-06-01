<script lang="ts">
    import headerImg from "../../img/plug.jpg"
</script>

<header class="header">
    <img src={headerImg} alt="Картинка будет чуть позже" width="1440" height="400">
</header>

<style>
    .header {
        display: flex;
        justify-content: center;
        align-content: center;
    }


    @media (max-width: 1440px) {
        .header img {
            width: 100%;
        }
    }

</style>