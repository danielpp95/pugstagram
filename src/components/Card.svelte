<script>
    import Comments from './Comments.svelte'
</script>

<div class="Card">
    <div class="Card-container">
        <div class="Card-header">
            <div class="Card-user">
                <img src="https://i.imgur.com/tsZnYwy.jpg" alt="Profile picture">
                <h2>
                    danielpp95
                    <span>Zulia, Venezuela</span>
                </h2>
            </div>
            <div class="Card-settings">
                <i class="fas fa-ellipsis-h"/>
            </div>
        </div>
        <div class="Card-photo">
            <figure>
                <img src="https://i.imgur.com/tsZnYwy.jpg" alt="Post image">
            </figure>
        </div>
        <div class="Card-icons">
            <div class="Card-icons-first">
                <i class="fas fa-heart"/>
                <i class="fas fa-paper-plane"/>
            </div>
            <div class="Card-icons-second">
                <i class="fas fa-bookmark"/>
            </div>
        </div>
        <div class="Card-description">
            <h3>danielpp95</h3>
            <span>Mensage</span>
        </div>
        <Comments />
    </div>
</div>