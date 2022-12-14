<template>
    <div class="side col-lg-3 me-auto position-absolute h-100">
        <div class="logo d-flex justify-content-center align-items-center">
            <img src="../assets/Frame.png" alt="" />
        </div>
        <div class="sibbar">
            <ul>
                <router-link to="/vcrd" tag="li" class="Vcards"
                    >Vcards</router-link
                >
                <router-link to="/product" tag="li" class="Product"
                    >Product</router-link
                >
                <router-link to="/" tag="li" class="Register"
                    >Register Users
                </router-link>
                <router-link to="/" tag="li" class="Plan">Plan </router-link>
                <router-link to="/" tag="li" class="Partner-Membership"
                    >Partner Membership
                </router-link>
            </ul>
            <hr />
            <ul>
                <router-link to="/Vcards" tag="li" class="Vcards"
                    >Payment Log
                </router-link>
                <router-link to="/Product" tag="li" class="Product"
                    >Payment Log
                </router-link>
                <router-link to="/" tag="li" class="Register"
                    >Product Orders
                </router-link>
                <router-link to="/" tag="li" class="Plan">Stripe </router-link>
                <router-link to="/" tag="li" class="Partner-Membership ms-3"
                    >Languages
                </router-link>
            </ul>
        </div>
    </div>
</template>
<script>
export default {
    data: function () {
        return {};
    },
    name: "SideBar",
};
</script>
<style lang="scss" scoped>
.side {
    top: 0px;
    left: 0;
    background-color: #f4f4f4;
}
.logo {
    height: 100px;
}
.sibbar {
    text-align: left;
    margin: 30px 0;
}
ul {
    padding: 0;
    li {
        list-style: none;
        padding: 10px 10px 10px 30px;
        &:hover {
            background-color: #d2e8e3;
        }
    }
}
</style>
