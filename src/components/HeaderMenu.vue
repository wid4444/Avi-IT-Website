<template>
    <div>

        <div class="nav-menu">

            <div class="logo">
                <img id="logo" src="../assets/logo.jpg" alt="logo">
            </div>

            <div class="burger">
                <i class="fas fa-bars" @click="showMenu()"></i>
            </div>
        </div>

        <div class="nav-content" :class="this.showMobileMenu ? 'open-menu' : 'closed-menu'">

            <ul class="nav-items">
                <li class="nav-item">
                    <router-link class="nav-link" @click="showMenu()" to="/">Home</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="nav-link" @click="showMenu()" to="/about">About Us</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="nav-link" @click="showMenu()" to="/courses">Courses</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="nav-link" @click="showMenu()" to="/careers">Career Center</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="nav-link" @click="showMenu()" to="/software">Repair &
                        Development</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="nav-link" @click="showMenu()" to="/events">Events</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="nav-link" @click="showMenu()" to="/get-involved">Get Involved</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="nav-link" @click="showMenu()" to="/resources">Resources</router-link>
                </li>
            </ul>

        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            showMobileMenu: false,
        };
    },
    methods: {
        showMenu() {
            this.showMobileMenu = !this.showMobileMenu;
        },
    },
};
</script>




<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;800&display=swap');

* {
    padding: 0;
    margin: 0;
    border: 0;
    outline: 0;
    list-style: none;
    text-decoration: none;
}

.nav-menu {
    justify-content: space-between;
    align-items: center;
    padding: 0 50px;
    height: 150px;
    display: flex;
    background: #bde0fe;
    min-height: 70px;
}

.burger {
    margin-bottom: 30px;
    display: flex;
    flex-direction: row;
    justify-content: flex-end;
    font-style: oblique;
    padding-right: 30px;
}

.nav-link {
    font-family: 'Montserrat', sans-serif;
    font-weight: 1200;
    color: #d100d1;
    font-size: 17px;
    text-decoration: none;
    text-align: center;
    transition: all 0.3s ease 0s;
    padding: 2px 10px;
    border-radius: 20px;
    list-style: none;
    display: block;
}

.nav-link:hover {
    padding: 5px 10px;
    text-align: center;
    text-decoration: none;
    transition: 0.5s;
    background-size: 200% auto;
    color: white;
    border-radius: 30px;
    display: block;
    border: 0px;
    font-weight: 700;
    box-shadow: 0px 0px 14px -7px #b100e8;
    background-image: linear-gradient(45deg, #6a00f4 0%, #b100e8 51%, #6a00f4 100%);
    cursor: pointer;
    user-select: none;
    -webkit-user-select: none;
    touch-action: manipulation;

}

#logo {
    height: 110px;
    margin-top: 20px;
    border-radius: 10px;
}

.nav-content {
    background: #bde0fe;
}

.nav-items {
    display: flex;
    justify-content: center;
    align-items: center;
    list-style: none;
    // margin: 10px;
    padding: 0;
    font-weight: 600;

    li {
        padding: 0 10px;
    }
}

.nav-item {
    margin: 20px 0;
}

i {
    text-align: right;
    display: none;
    color: #d008d6;
    font-size: 50px;

}
// Ipad size
@media screen and (max-width:1024px) {

    
    .nav-menu {
        padding: 0 20px;
    }

    .nav-link {
        display: flex;
        font-family: 'Montserrat', sans-serif;
        font-weight: 600;
        color: #d100d1;
        font-size: 12px;
        text-decoration: none;
        text-align: center;
        transition: all 0.3s ease 0s;
        padding: 2px 5px;
        border-radius: 20px;
        list-style: none;
        text-align: center;
        align-items: center;
        justify-content: center;

    }

    .nav-link:hover {
        padding: 4px 10px;
        text-align: center;
        text-decoration: none;
        transition: 0.5s;
        background-size: 200% auto;
        color: white;
        border-radius: 30px;
        display: block;
        border: 0px;
        font-weight: 700;
        box-shadow: 0px 0px 14px -7px #b100e8;
        background-image: linear-gradient(45deg, #d300f4 0%, #b100e8 51%, #d300f4 100%);
        cursor: pointer;
        user-select: none;
        -webkit-user-select: none;
        touch-action: manipulation;

    }
}

// Mobile version - hidden hamburger menu

@media screen and (max-width: 700px) {          
   

    #logo {
        height: 100px;
        margin-top: 0px;
        margin-left: 20px;

    }

    .nav-menu {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        padding: 0;
        height: 150px;
        background: #bde0fe;
    }

    .burger {
        margin-bottom: 30px;
        display: flex;
        flex-direction: row;
        justify-content: flex-end;
        font-style: oblique;
        padding-right: 30px;
    }

    .open-menu {
        opacity: 1;
        display: flex;
        flex-direction: column;
        position: absolute;
        box-shadow: 0px 0px 14px -7px #b100e8;
        background-image: linear-gradient(45deg, #0707e2 0%, #7c00e8 51%, #d008d6 100%);
        width: 100%;
        top: 0;
        left: 0;
        transform: translateY(25%);
        z-index: 1;
        transition: .4s;
        overflow: hidden;
        text-align: center;
        border-radius: 20px;
    }

    .closed-menu {
        opacity: 0;
        height: 0;
        padding: 0;
        transform: translateY(0%);
        transition: .2s;
        overflow: hidden;
    }

    .nav-link {
        font-family: 'Montserrat', sans-serif;
        font-weight: 700;
        color: white;
        font-size: 15px;
        text-decoration: none;
        text-align: center;
        transition: all 0.3s ease 0s;
        padding: 2px 0px;
        border-radius: 20px;
        list-style: none;

    }

    .nav-link:hover {
        padding: 5px 7px;
        text-align: center;
        text-decoration: none;
        transition: 0.5s;
        background-size: 200% auto;
        color: white;
        border-radius: 30px;
        display: block;
        border: 2px solid white;
        font-weight: 700;
        box-shadow: 0px 0px 14px -7px #c348e9;
        background-image: linear-gradient(45deg, #e0aaff 0%, #f72585 51%, #e0aaff 100%);
        cursor: pointer;
        user-select: none;
        -webkit-user-select: none;
        touch-action: manipulation;

    }

    .nav-content {
        display: flex;
        flex-direction: column;
        z-index: 100;
        transition: all 0.2s ease-out;
    }

    .nav-items {
        display: flex;
        flex-direction: column;
        margin: 20px 0;

    }

    .nav-item {
        margin: 25px;
        text-align: center;

    }

    i {
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        text-align: right;
        margin-top: 20px;
    }


}
</style>