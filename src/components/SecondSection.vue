<script>
import HotJar from "../assets/icons/HotJar.vue"
export default {
    name: 'SecondSection',
    components: {
        HotJar: HotJar
    }
}
</script>
<template>
    <section class="second_section">
        <h3>USED BY OVER 50 ENTERPRISES</h3>
        <div>
            <ul class="carousel">
                <li>
                    <HotJar />
                </li>
                <li>
                    <HotJar />
                </li>
                <li>
                    <HotJar />
                </li>
                <li>
                    <HotJar />
                </li>
                <li>
                    <HotJar />
                </li>
            </ul>
        </div>
    </section>
</template>

<style scoped>
.second_section {
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 32px 64px 40px;
    gap: 36px;
    isolation: isolate;
    width: 1126px;
    height: 176px;
    background: #ffffff;
    border-width: 1px 1px 1px 1px;
    border-style: solid;
    border-color: #cbd5e1;
    border-radius: 14px;
    flex: none;
    order: 1;
    flex-grow: 0;
    margin: 0 auto;
}

.second_section>h3 {
    width: 351px;
    height: 20px;
    font-family: "Inter";
    font-style: normal;
    font-weight: 400;
    font-size: 15px;
    line-height: 128%;
    /* or 20px */
    letter-spacing: 0.24em;
    color: #94a3b8;
    flex: none;
    order: 0;
    flex-grow: 0;
    z-index: 0;
}

.second_section>div {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    padding: 0px;
    gap: 103px;
    width: 998px;
    height: 48px;
    flex: none;
    order: 1;
    align-self: stretch;
    flex-grow: 0;
    z-index: 1;
    list-style-type: none;
    position: relative;
    overflow: hidden;
}

.carousel {
    position: absolute;
    left: 20px;
    top: 10px;
    display: flex;
    gap: 100px;
    list-style-type: none;
}


@media screen and (max-width:360px) {
    .second_section {
        padding: 0px;
        gap: 16px;
        width: 356px;
        height: 79px;
        overflow: hidden;
        background: none;
        border: none;
    }

    .second_section>h3 {
        width: 266px;
        height: 15px;
        font-size: 12px;
    }

    .second_section>div {
        justify-content: center;
        align-items: flex-start;
        gap: 40px;
        width: 404px;
        height: 48px;
    }

    .carousel {
        gap: 50px;
        animation: slideLeft 5s linear infinite forwards;
    }

    @keyframes slideLeft {
        0% {
            left: 0;
        }

        100% {
            left: -100%;
        }
    }


}
</style>
