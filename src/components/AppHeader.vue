<script>
    export default {
        name: 'AppHeader'
    }
</script>
<template>
    <div class="header_nav_bar">
        <div>
            <img src="/public/images/HelloIMG1669149314369.png" alt="">
        </div>
        <ul>
            <li>
                HOME
            </li>
            <li>
                MISSION
            </li>
            <li>
                CAUSES
            </li>
            <li>
                JOURNAL
            </li>
            <li>
                <button>DONATE</button>
            </li>
        </ul>
    </div>
    
</template>
<style>
ul{
    list-style: none;
    display: flex;
}
li{
    padding: 1rem;
}
.header_nav_bar{
    display: flex;
    justify-content: space-between;
}
</style>