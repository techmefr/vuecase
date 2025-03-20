<script setup></script>

<template>
    <div id="top-line">
        <img id="profile-img" src="../assets/me.jpg" alt="me" width="300px" height="300px" />
        <div id="line">
            <p>Je suis <span class="text-highlight-1">Gaëtan Compigni</span>,<br /> Concepteur Développeur
                d'Application.
            </p>
            <div id="social"></div>
        </div>
    </div>
</template>

<style scoped>
#top-line {
    margin-top: 50px;
    width: 100%;
    height: 100%;
}

#top-line #profile-img {
    float: left;
    transform: translateY(40%);
    text-align: center;
}

#top-line p {
    font-size: 42px;
    line-height: 60px;
}

#top-line p span {
    font-weight: bold;
}

@media (max-width: 905px) {
    #top-line #profile-img {
        display: none;
    }

    #top-line #line {
        float: none;
        transform: translateY(0%);
    }

    #top-line p {
        font-size: 36px;
    }
}
</style>
