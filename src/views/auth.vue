<template>
    <section class="autn-sec">
        <div class="contaner">
            <h2>AUTH</h2>
            <form action="">
                <input type="text">
                <button>Go</button>
            </form>
        </div>
    </section>
</template>
<script></script>
<style lang="scss"> 
.autn-sec{
    display: flex;
    align-items: center;
    justify-content: center;
    height: 80vh;
    

    .contaner{
        max-width: 768px;
        padding: 8px 10px;
        border-radius: 8px;
        backdrop-filter: blur(2222px);

        h2{
          color: rgb(255, 255, 255);
          font-size: 26px;
        }
    }
}
</style>