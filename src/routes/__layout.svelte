<script>

import '../styles/global.css'
</script>



<header>
    <a href="/"><img src="lt.png" alt="Light logo" width = 80px>  </a>
    <h1> </h1>
        <h2>   Licht Web App</h2>


</header>
<main>

    <!-- page content-->
    <slot></slot>

</main>

<footer>
<br><br>

<a href="/"> Main Page  </a>
<br>
<a href="/faq"> FAQs  </a>
<br>
<a href="/userguide"> User Guide  </a>


    <p>Copyright 2022 Licht Web App</p>
</footer>

<style>
    header{
        display:flex;
        justify-content: center;
        background: rgba(100, 100, 100, 0.1)
    }

    main {
        max-width: 960px;
        margin: 20px auto;
    }


    footer {
        text-align: center;
    }

</style>
