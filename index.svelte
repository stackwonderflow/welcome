<!-- Welcome.svelte -->

<script>
    import './styles.css';
</script>

<div class="wrapper">
    <div class="header">
        <h1 class="postTitle">Emanuel Antablin</h1>
        <ul>
            <li>
                <a href="about" class="jelly-button">
                    <span class="jelly-text">about</span>
                </a>
            </li>
            <li>
                <a href="consult" class="jelly-button">
                    <span class="jelly-text">consult</span>
                </a>
            </li>
            <li>
                <a href="https://github.com/eantablin" class="jelly-button">
                    <span class="jelly-text">code</span>
                </a>
            </li>
            <li>
                <a href="mailto:eantablin@protonmail.com" class="jelly-button">
                    <span class="jelly-text">email</span>
                </a>
            </li>
        </ul>
    </div>
    <!-- Passionately searching for security flaws and understanding human-computer interactions. -->
    <p class="introduction">Chaotically falling onward</p>

    <div class="blog">
        <ul class="postList">
            <li class="postItem">
                <ol>
                    <li><span class="date">2021 Dec 31</span> - <a href="uxtips">Designing an intuitive UX</a></li>
                    <li><span class="date">2023 Jun 3</span> - <a href="mentoringTips">Efficient Mentorship</a></li>
                </ol>
            </li>
        </ul>
    </div>

    <div class="footer">
        <div class="copyright">
            © {new Date().getFullYear()} Emanuel Antablin
        </div>
    </div>
</div>
