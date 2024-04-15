<script>
import '../assets/css/second_section.css'
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
        <div>USED BY OVER 50 ENTERPRISES</div>
        <ul>
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
    </section>
</template>
