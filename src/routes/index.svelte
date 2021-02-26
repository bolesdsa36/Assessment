<!-- header of website layout -->
<header>
    <h1>YouTube’s Biggest Channels</h1>
</header>

<!-- nevigation menu of website layout -->
<nav>
    <a href=".">Home</a>
    <a href="education">Education</a>
    <a href="entertainment">Entertainment</a>
    <a href="music">Music</a>
</nav>

<!-- Content section of website layout -->
<div class="row">
    <div class="columnA" />

    <div class="columnB">
        <h2>What is YouTube?</h2>
        <p>
            YouTube is a free video sharing website on the internet. The website
            lets people upload, view, and share videos. YouTube was started on
            February 14, 2005 by three former workers of PayPal. Google (a
            search engine company) has owned and operated YouTube since 2006.
            YouTube now carries paid advertisements on all pages. Videos can be
            rated with likes or dislikes, and viewers can subscribe to channels
            they like. Videos can be commented on if viewers log into their own
            accounts. The number of times a video has been watched, known as
            "views", are shown. Many different types of videos can be put onto
            the website, such as educational content, animations, and events.
        </p>
    </div>

    <div class="columnC" />
</div>
<footer>
    <p>&copy; Sarah2021</p>
</footer>

<style>
    * {
        box-sizing: border-box;
    }

    /* CSS property for header section */
    header {
        font-family: "Lobster Two", cursive;
        background-color: #fcb1a67c;
        padding: 15px;
        text-align: center;
    }

    header h1 {
        color: white;
        font-size: 400%;
    }

    /* CSS property for navigation menu */
    nav {
        overflow: hidden;
        background-color: #5d2a42;
    }
    nav a {
        float: left;
        display: block;
        color: white;
        text-align: center;
        padding: 14px 16px;
        text-decoration: none;
        font-family: "Big Shoulders Inline Display", cursive;
        font-size: 125%;
    }
    nav a:hover {
        background-color: white;
        color: #fb6376;
    }

    /* CSS property for content section */
    .columnA,
    .columnB,
    .columnC {
        float: left;
        width: 33%;
        padding: 15px;
        text-align: justify;
    }

    h2 {
        color: #fb6376;
        text-align: center;
        font-family: "Big Shoulders Inline Display";
        font-family: "Lobster Two", cursive;
    }
    p {
        font-family: "Manrope", sans-serif;
    }
    footer {
        position: fixed;
        left: 0;
        bottom: 0;
        width: 100%;
        background-color: #5d2a42;
        color: white;
        text-align: center;
    }
</style>
