<script>
export default {

}
</script>

<template>
    <footer>
        <div class="footer_Links">
            <div class="container links_container">
                <div class="row">
                    <div class="col-1">
                        <h5>DC COMICS</h5>

                        <ul class="nav">
                            <li class="nav-item">
                                <a href="#" class="nav-link">Characters</a>
                                <a href="#" class="nav-link">Comics</a>
                                <a href="#" class="nav-link">Movies</a>
                                <a href="#" class="nav-link">TV</a>
                                <a href="#" class="nav-link">Games</a>
                                <a href="#" class="nav-link">Videos</a>
                                <a href="#" class="nav-link">News</a>                           
                            </li>
                        </ul>

                        <h5>SHOP</h5>

                        <ul class="nav">
                            <li class="nav-item">
                                <a href="#" class="nav-link">Shop DC</a>
                                <a href="#" class="nav-link">Shop DC Collectibles</a>                          
                            </li>
                        </ul>
                    </div>

                    <div class="col-1">
                        <h5>DC</h5>

                        <ul class="nav">
                            <li class="nav-item">
                                <a href="#" class="nav-link">Term Of Use</a>
                                <a href="#" class="nav-link">Privacy policy(new)</a>
                                <a href="#" class="nav-link">Ad Choices</a>
                                <a href="#" class="nav-link">Advertising</a>
                                <a href="#" class="nav-link">Jobs</a>   
                                <a href="#" class="nav-link">Subscriptions</a> 
                                <a href="#" class="nav-link">Talent Workshops</a> 
                                <a href="#" class="nav-link">CPSC Certificates</a> 
                                <a href="#" class="nav-link">Rating</a> 
                                <a href="#" class="nav-link">Shop Help</a> 
                                <a href="#" class="nav-link">Contact Us</a>                         
                            </li>
                        </ul>
                    </div>

                    <div class="col-1">
                        <h5>SITES</h5>

                        <ul class="nav">
                            <li class="nav-item">
                                <a href="#" class="nav-link">DC</a>
                                <a href="#" class="nav-link">MAD Magazine</a>
                                <a href="#" class="nav-link">DC Kids</a>
                                <a href="#" class="nav-link">DC Universe</a>
                                <a href="#" class="nav-link">DC Power Visa</a>                           
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>

        <div class="footer_interactables">
            <div class="container d-flex align-items-center justify-content-between">
                <button type="button" class="btn">SIGN-UP NOW!</button>

                <div class="footer_Icons_container d-flex align-items-center">
                    <h4>FOLLOW US</h4>

                    <ul class="icon-list d-flex gap-3">
                        <li><img src="../assets/footer-facebook.png" alt=""></li>
                        <li><img src="../assets/footer-twitter.png" alt=""></li>
                        <li><img src="../assets/footer-youtube.png" alt=""></li>
                        <li><img src="../assets/footer-pinterest.png" alt=""></li>
                        <li><img src="../assets/footer-periscope.png" alt=""></li>
                    </ul>
                </div>
            </div>
               
        </div>
    </footer>
</template>

<style lang="scss" scoped>
    @use "../styles/partials/variables" as *;

    .btn {
        color: white;
        border-color: $color_Primary;
        border-radius: 0;
        font-weight: bold;
        padding: 10px 20px;
    }

    .icon-list {
        list-style: none;
        margin: 0;
    }

    h4 {
        margin: 0;
        color: $color_Primary;
    }

    h5 {
        color: white;
        padding-top: 0.9rem;
        padding-bottom: 0.6rem;
        margin: 0;
    }

    .nav-link {
        padding: 0;
        font-size: 0.85rem;
        color: #959595;
    }

    .footer_interactables {
        background-color: #303030;
        padding-top: 2rem;
        padding-bottom: 2rem;
    }

    .footer_Links {
        background-image: url("../assets/footer-bg.jpg");
    }

    .col-1 {
        width: 12%;
        padding-top: 1.5rem;
        padding-bottom: 3.5rem;
    }
    
    .links_container {
        background-image: url("../assets/dc-logo-bg.png");
        background-repeat: no-repeat;
        background-position-y: center;
        background-position-x: right;
    }
</style>