<script>
export default  {
    components: {
    },
    data() {
            return {
                home: [
                    { name: "Main Home"},
                    { name: "Floating Portfolio"},
                    { name: "Animated Slider"},
                    { name: "Portfolio Metro"},
                    { name: "Portfolio Gallery"},
                    { name: "Interactive Links"},
                    { name: "Split Slider Showcase"},
                    { name: "Portfolio Carousel"},
                    { name: "Landing"},
                    ],
                pages: [
                    { name: "About Us"},
                    { name: "About Me" },
                    { name: "What we Offer"},
                    { name: "Working process"},
                    { name: "Our Team"},
                    { name: "Pricing Plans"},
                    { name: "Contact Us"},
                    { name: "Coming Soon"},
                    { name: "404 Error Page"},
                    ],    
                blog: [
                    { name: "Right Sidebar"},
                    { name: "Left Sidebar"},
                    { name: "Centered"},
                    { name: "Post Types"},
                    ], 
                shop: [
                    { name: "Product List"},
                    { name: "Product Single"},
                    { name: "Shop Layouts"},
                    { name: "Shop Pages"},
                    ],     
            }
        }
} 
</script>

<template>  
    <div class="container-fluid d-flex justify-content-between align-items-center">
        <img src="../assets/img/logo-sidearea-1.png" alt="Marée Logo" class="my-3 mx-3">

        <div class="menu d-flex">
            <div class="menu-item">
                <a href="#" class="nav-link me-5"><strong>HOME</strong></a>
                <div class="sub-menu">
                    <ul>
                        <li v-for="link in home">
                            {{ link.name }}
                        </li>
                    </ul>
                </div>
            </div>
            <div class="menu-item">
                <a href="#" class="nav-link me-5"><strong>PAGES</strong></a>
                <div class="sub-menu">
                    <ul>
                        <li v-for="link in pages">
                            {{ link.name }}
                        </li>
                    </ul>
                </div>
            </div>
            <div class="menu-item">
                <a href="#" class="nav-link me-5"><strong>PORTFOLIO</strong></a>
                <div class="sub-menu">
                    <ul>
                        <li v-for="link in home">
                            {{ link.name }}
                        </li>
                    </ul>
                </div>
            </div>
            <div class="menu-item">
                <a href="#" class="nav-link me-5"><strong>BLOG</strong></a>
                <div class="sub-menu">
                    <ul>
                        <li v-for="link in blog">
                            {{ link.name }}
                        </li>
                    </ul>
                </div>
            </div>
            <div class="menu-item">
                <a href="#" class="nav-link me-5"><strong>SHOP</strong></a>
                <div class="sub-menu">
                    <ul>
                        <li v-for="link in shop">
                            {{ link.name }}
                        </li>
                    </ul>
                </div>
            </div>
            <div class="menu-item">
                <a href="#" class="nav-link me-5"><strong>ELEMENTS</strong></a>
                <div class="sub-menu">
                    <ul>
                        <li v-for="link in home">
                            {{ link.name }}
                        </li>
                    </ul>
                </div>
            </div>
            <img src="../assets/svg/svg-1.svg" alt="">
        </div>
    </div>

    <img src="../assets/svg/svg-7.svg" alt="" id="myFixedElement2">
    <img src="../assets/svg/svg-6.svg" alt="" id="myFixedElement">

</template>

<style lang="scss" scoped>
.container-fluid {
    font-family: Arial, Helvetica, sans-serif;
}
.menu-item {
    position: relative;
    margin-right: 20px;
}

.sub-menu {
    display: none;
    position: absolute;
    top: 200%;
    left: 0;
    background-color: #faf7f1;
    box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.2);
    z-index: 1;
    width: 200px;
}

.menu-item:hover .sub-menu {
    display: block;
}

a {
    text-decoration: none;
    color: #333;
    list-style: none;
}

.sub-menu ul li {
    display: block;
    padding: 10px;
}
#myFixedElement {
    position: fixed;
    top: 200px; 
    right: 10px; 
    background-color: #fff;
    padding: 10px;
    z-index: 1;
    width: 50px;
}
#myFixedElement2 {
    position: fixed;
    top: 150px; 
    right: 10px; 
    background-color: white;
    padding: 10px;
    z-index: 1;
    width: 50px;
}
</style>
