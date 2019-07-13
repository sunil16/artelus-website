<template>
  <footer class="footer_sec">
        <div class="container text-center">

                <h2>A Deep learning healthcare company</h2>
                <hr >

                    <p class="copyrights">© 2019 All Rights Reserved.</p>

            </div>
    </footer>
</template>

<script>
export default {
  name: 'Footer'
}
</script>
<style scoped>
body footer.footer_sec{
    background-color: #f05f40 !important;
    margin: 0;
    padding: 50px 0px;
    margin-top: 30px;
}
body footer.footer_sec h2,body footer.footer_sec p{
   color: #fff;
}
footer.footer_sec h2{
    font-weight: 400;
}
 footer.footer_sec hr{
        max-width: 50px;
        border-width: 3px;
        border-color: #fff;
 }
 footer.footer_sec p{
    font-size: 12px;

 }

</style>
