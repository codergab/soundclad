<template>
    <div class="playlist-layout">
        <div class="sidebar">
            <div class="side-header">
                <nuxt-link to="/" style="color: #fff; font-size: 1.5em; padding: 0.5em">SOUNDCLAD</nuxt-link>
            </div>
            <div class="side-links">
            </div>
        </div>
        <!-- <nuxt-link to="/" class="bottom-link">
            Back Home
        </nuxt-link> -->

        
    </div>
</template>

<style scoped>
    .playlist-layout {
        width: 95vw;
        height: 90vh;
        background: rgba(255, 255, 255, 0.1);
        margin: 2.2em auto;
        display: flex;
        /* align-items: center; */
    }

    .sidebar {
        display: flex;
        border: 1px solid #000;
        width: 220px;
    }

    .side-header {
        text-align: center !important;
    }

    .side-header a {
        text-decoration: none;
        color: #dd6b4d;
    }

    .side-header a:hover {
        color: #dd6b4d;
    }



    .bottom-link {
  
        background: #dd6b4d;
 
        color: #fff;
        padding: 1em;
        text-decoration: none;

    }
</style>

