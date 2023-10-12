<script>

</script>

<section class="hero">
    <div class="content">
        <div class="hero-box">
            <span class="yellow">0 &gt; 10k</span>
            <hr class="vertical" />
            <div class="logo-box">
                <span class="logo">THE</span><span class="logo">DUTCHdev</span>
            </div>
        </div>
    </div>
</section>

<!-- Make a full screen hero section with centered content -->
<style>
    :global(body) {
        margin: 0;
        padding: 0;
        font-family: "Poppins";
    }

    .yellow {
        color: #ffdf2b;
        text-shadow: 0.5rem 0.5rem rgba(0, 0, 0, 0.3);
        font-size: 6rem;
    }

    .logo {
        color: white;
        font-weight: 700;
        font-size: 4rem;
        -webkit-text-stroke-width: 4px;
        -webkit-text-stroke-color: black;
    }

    hr.vertical {
        background-color: white;
        border: black;
        width: 0.5rem;
        height: 10rem;
        /* or height in PX */
    }
    section {
        padding-top: 1rem;
    }

    .hero {
        height: 100dvh;
        display: flex;
        justify-content: center;
        line-height: 0.8;
        background-size: cover;
        background-image: url("$lib/background-dutchdev.png");
    }

    .hero-box {
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        gap: 2rem;
    }

    .logo-box {
        display: flex;
        flex-direction: column;
        text-align: left;
    }

    .content {
        text-align: center;
        color: #fff;
    }

    @media screen and (max-width: 900px) {
        .yellow {
            font-size: 2.8rem;
        }
        .logo {
            font-size: 1.8rem;
            -webkit-text-stroke-width: 2px;
        }

        hr.vertical {
            width: 0.2rem;
            height: 6rem;
            /* or height in PX */
        }
    }
</style>
