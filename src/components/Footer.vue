<script>
import '../assets/css/footer.css'
import LogoIcon from "../assets/icons/Logo.vue"
import LocationIcon from "../assets/icons/LocationIcon.vue"
import ContactLogo from "../assets/icons/ContactLogo.vue"
import LinkedInIcon from "../assets/icons/LinkedInIcon.vue"
import YoutubeIcon from "../assets/icons/YoutubeIcon.vue"
import InstagramIcon from "../assets/icons/InstagramIcon.vue"
export default {
    name: 'Footer_Component',
    components: {
        LogoIcon: LogoIcon,
        LocationIcon: LocationIcon,
        ContactLogo: ContactLogo,
        LinkedInIcon: LinkedInIcon,
        YoutubeIcon: YoutubeIcon,
        InstagramIcon: InstagramIcon
    }
}
</script>
<template>
    <section class="footer">
        <ul>
            <li>
                <div class="left_side_footer">
                    <LogoIcon />
                </div>
                <div class="right_side_footer">
                    <div class="up_side_footer">
                        <div>
                            <LocationIcon />
                            <span>Address</span>
                        </div>
                        <div>
                            <ContactLogo />
                            <span>
                                +91 1234567890
                            </span>
                        </div>
                    </div>
                    <div class="down_side_footer">
                        <span>Social Media</span>
                        <ul>
                            <li>
                                <LinkedInIcon />
                            </li>
                            <li>
                                <YoutubeIcon />
                            </li>
                            <li>
                                <InstagramIcon />
                            </li>
                        </ul>
                    </div>
                </div>
            </li>
            <li></li>
            <li>
                <ul>
                    <li>Blogs</li>
                    <li>Features</li>
                    <li>Pricing</li>
                    <li>Integrations</li>
                </ul>
                <div>Copyright © 2024 • ExpenseBook</div>
            </li>
        </ul>
    </section>
</template>
