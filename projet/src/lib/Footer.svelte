<script>
    import { link } from "svelte-spa-router";

</script>

<main>

    <div class="footer">
        <div class="footer-bloc">
            <a href="/" use:link><img src="white-logo.png" alt="home" /></a>
        </div>

        <div class="footer-bloc">
            <div class="title">
                <h2>instagram</h2>
            </div>
            <div class="info">
                <a href="https://www.instagram.com/cocoprendlethe/"><p>@cocoprendlethe</p></a>
            </div>
        </div>
        <div class="footer-bloc">
            <div class="info">
                <a href="/contact" use:link><p>contact</p></a>
            </div>
        </div>
        <div class="footer-bloc">   
            <div class="title">
                <h2>communication</h2>
            </div>
            <div class="info">
                <a href="mailto:elodie.cornec@hotmail.fr"><p>elodie.cornec@hotmail.fr</p></a>
            </div>
        </div>
        <div class="footer-bloc">
            <div class="info">
                <a href="/" use:link><p>accueil</p></a>
            </div>
        </div>
        <div class="footer-bloc">
            <div class="title">
                <h2>credits</h2>
            </div>
            <div class="info">
                <p>Website designed and developped by Julien Farrouault</p>
            </div>
        </div>
    </div>

</main>

<style>

    .footer {
        display: flex;
        height: 500px;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        border-top: 1px solid white;
        margin-left: 20%;
        margin-right: 20%;
    }

    .footer-bloc {
        padding-bottom: 5%;
    }

    img {
        width: 100px;
    }

    h2 {
        text-align: center;
        margin-bottom: 10px;
    }

    a {
        text-decoration: none;
        color: rgb(255, 255, 254);
    }

    p {text-align: center;}
</style>