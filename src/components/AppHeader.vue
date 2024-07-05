<script >
export default{
    name: "AppHeader"
}

</script>

<template>
    <header>
        <div class="container">
            <a href="#">
                <img src="../assets/dc-logo.png" alt="Logo DC">
            </a>
            <nav>
                <ul>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                </ul>
            </nav>
        </div>
    </header>

</template>

<style lang="scss" scoped>
header {
    background-color: white;

    .container {
        align-items: center;

        nav{
            flex-grow: 1;
            text-align: right;
            
            ul li {
            display: inline-block;
            }
        }
    }

       
}

</style>
