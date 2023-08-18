<script>
    export let title
    export let content
    export let link
    export let featuredImg
    export let alt

</script>

<div class="card rounded-lg overflow-hidden relative">
    <img class="absolute top-0" src={featuredImg} {alt}>
    <div class="relative z-10">
        <p>{title}</p>
        <p>{content}</p>
        <p>{link}</p>
    </div>


 
</div>

<style>
    .card{
        width: 280px;
        height: 452px;
        background-color: white;
    }
</style>