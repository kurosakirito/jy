<script>
    let books = ["seDiuYingHungChyun", "sanDiuHapLeui", "yiTinTouLungGei"];
</script>

<style>
    .center {
        text-align:center;
    }
    .tableCenter {
        margin: auto;
    }
</style>


<h2 class="center">Books</h2>

<table class="tableCenter">
    {#each books as book}
        <tr>
            <td>{book}</td>
        </tr>
    {/each}
</table>

