<script lang="ts">
    import svelteLogo from '../../assets/svelte.svg';
</script>

<nav>
    <span class="logo">
        <img src={svelteLogo} alt="Svelte logo" height=60 width=60/>
        <p>Svelte</p>
    </span>
    <ul>
        <li><a href="/">Home</a></li>
        <li><a href="/about">About</a></li>
        <li><a href="/contact">Contact</a></li>
    </ul>
</nav>

<style>
    .logo {
        display: flex;
        align-items: center;
    }

    .logo p{
        font-size: 42px;
    }
    nav {
        display: flex;
        justify-content: space-around;
        align-items: center;
        background-color: #333;
        color: white;
        padding: 2rem;
    }

    ul {
        display: flex;
        list-style: none;
        gap: 2rem;

    }

    a {
        color: white;
        text-decoration: none;
        font-size: 24px;
    }
</style>