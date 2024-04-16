<script>
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


<style scoped>
.footer {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 64px 120px 100px;
    gap: 10px;
    width: 1366px;
    height: 408px;
    flex: none;
    order: 6;
    align-self: stretch;
    flex-grow: 0;
    margin: 0 auto;
}

.footer>ul {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px;
    gap: 48px;
    width: 1126px;
    height: 244px;
    flex: none;
    order: 0;
    align-self: stretch;
    flex-grow: 0;
    list-style-type: none;
}

.footer>ul>li:nth-child(1) {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: flex-start;
    padding: 0px;
    width: 1126px;
    height: 128px;
    flex: none;
    order: 0;
    align-self: stretch;
    flex-grow: 0;
}


.left_side_footer {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 10px 8px 10px 0px;
    gap: 10px;
    margin: 0 auto;
    width: 563px;
    height: 44px;
    flex: none;
    order: 0;
    flex-grow: 1;
}

.right_side_footer {
    margin: 0 auto;
    width: 563px;
    height: 128px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    order: 1;
    flex-grow: 1;
}

.up_side_footer {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px;
    gap: 16px;
    width: 147px;
    height: 64px;
    flex: none;
    order: 0;
    flex-grow: 0;
}

.up_side_footer>div:nth-child(1) {
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 0px;
    gap: 8px;
    width: 87px;
    height: 24px;
    flex: none;
    order: 0;
    flex-grow: 0;
    cursor: pointer;
}

.up_side_footer>div:nth-child(1)>span {
    width: 55px;
    height: 17px;
    font-family: "Inter";
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 17px;
    color: #64748b;
    flex: none;
    order: 1;
    flex-grow: 0;
}

.up_side_footer>div:nth-child(2) {
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 0px;
    gap: 8px;
    width: 147px;
    height: 24px;
    flex: none;
    order: 1;
    flex-grow: 0;
    cursor: pointer;
}

.up_side_footer>div:nth-child(2)>span {
    width: 115px;
    height: 17px;
    font-family: "Inter";
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 17px;
    color: #64748b;
    flex: none;
    order: 1;
    flex-grow: 0;
}

.down_side_footer {
    width: 218px;
    height: 24px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    order: 1;
    flex-grow: 0;
    position: relative;
}

.down_side_footer>span {
    top: 0;
    font-family: "Inter";
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 17px;
    color: #94a3b8;
}

.down_side_footer>ul {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    padding: 0px;
    gap: 24px;
    width: 120px;
    height: 24px;
    list-style-type: none;
}

.down_side_footer>ul>li {
    cursor: pointer;
}

.footer>ul>li:nth-child(2) {
    width: 1126px;
    height: 2px;
    background: #e0e5e9;
    flex: none;
    order: 1;
    align-self: stretch;
    flex-grow: 0;
}

.footer>ul>li:nth-child(3) {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    padding: 0px;
    width: 1126px;
    height: 18px;
    flex: none;
    order: 2;
    align-self: stretch;
    flex-grow: 0;
}

.footer>ul>li:nth-child(3)>ul {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    padding: 0px;
    gap: 56px;
    margin: 0 auto;
    width: 563px;
    height: 17px;
    flex: none;
    order: 0;
    flex-grow: 1;
    list-style-type: none;
}

.footer>ul>li:nth-child(3)>ul>li {
    width: 37px;
    height: 17px;
    font-family: "Inter";
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 17px;
    text-transform: capitalize;
    color: #64748b;
    flex: none;
    flex-grow: 0;
    cursor: pointer;
}

.footer>ul>li:nth-child(3)>div {
    margin: 0 auto;
    width: 563px;
    height: 18px;
    font-family: "Assistant";
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 18px;
    text-align: right;
    color: #0a142f;
    mix-blend-mode: normal;
    opacity: 0.5;
    flex: none;
    order: 1;
    flex-grow: 1;
}


@media screen and (max-width: 360px) {
    .footer {
        padding: 48px 24px;
        width: 360px;
        height: fit-content;
    }

    .footer>ul {
        width: 312px;
        height: fit-content;
    }

    .footer>ul>li:nth-child(1) {
        flex-direction: column;
        gap: 32px;
        width: 312px;
        height: fit-content;
    }

    .left_side_footer {
        align-items: center;
        width: 168px;
        height: 44px;
    }

    .right_side_footer {
        width: 312px;
        height: 104px;
        gap: 20px;
    }

    .footer>ul>li:nth-child(2) {
        width: 312px;
        height: 2px;
    }

    .footer>ul>li:nth-child(3) {
        flex-wrap: wrap;
        align-items: center;
        align-content: flex-start;
        gap: 28px;
        width: 292px;
        height: 63px;
    }

    .footer>ul>li:nth-child(3)>ul {
        flex-wrap: wrap;
        align-content: flex-start;
        gap: 12px 24px;
        width: 292px;
        height: 17px;
    }

    .footer>ul>li:nth-child(3)>div {
        width: 189px;
        height: 18px;
        text-align: center;
    }
}
</style>