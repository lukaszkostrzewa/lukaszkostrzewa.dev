<script>
    const year = new Date().getFullYear();
</script>

<style>
    footer {
        text-align: center;
        padding: 1rem;
        border-top: 1px solid rgba(70, 130, 180, 0.1);
        font-size: 0.8rem;
        color: grey;
        margin-top: 2rem;
    }

    .social-media {
        margin: 1rem;
        height: 1.5rem;
    }

    a,
    img {
        height: 100%;
    }

    a {
        margin: 0.5rem;
        opacity: 0.7;
        transition: opacity 400ms;
    }

    a:hover {
        opacity: 1;
    }
</style>

<footer>
    © {year} Łukasz Kostrzewa
    <div class="social-media">
        <a href="https://stackoverflow.com/users/1131963"><img src="stackoverflow.png" alt="StackOverflow"/></a>
        <a href="https://twitter.com/lukaszwebmaster"><img src="twitter.png" alt="Twitter"/></a>
        <a href="https://www.linkedin.com/in/\%C5\%82ukasz-kostrzewa-06616991/"><img src="linkedin.png" alt="LinkedIn"/></a>
        <a href="https://github.com/lukaszkostrzewa"><img src="github.png" alt="GitHub"/></a>
        <a href="https://www.goodreads.com/user/show/120856329-lukasz-kostrzewa"><img src="goodreads.png" alt="GitHub"/></a>
    </div>
</footer>
