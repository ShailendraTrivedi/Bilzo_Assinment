<script>
import Integration_Image from "../assets/icons/Integration_Image.vue"
import HRMS_Systems from "../assets/icons/HRMS_Systems.vue"
import Finance_Systems from "../assets/icons/Finance_Systems.vue"
import Single_Sign_on_Systems from "../assets/icons/Single_Sign_on_Systems.vue"
export default {
    name: 'FourthSection',
    components: {
        Integration_Image: Integration_Image,
        HRMS_Systems: HRMS_Systems,
        Finance_Systems: Finance_Systems,
        Single_Sign_on_Systems: Single_Sign_on_Systems
    }
}
</script>
<template>
    <div class="full_fourth_section">
        <section class="fourth_section">
            <h3>Integrations</h3>
            <div>
                <Integration_Image />
            </div>
            <ul>
                <li>
                    <div>
                        <HRMS_Systems />
                        <h3>HRMS Systems</h3>
                    </div>
                    <p>
                        We can integrate with any HRMS as long as the employee master can be made available to us
                        over SFTP/API.
                        <br><br>

                        We are already deeply integrated with PeopleStrong and others are coming up.
                    </p>
                    <span></span>
                </li>
                <li>
                    <div>
                        <Finance_Systems />
                        <h3>Finance Systems</h3>
                    </div>
                    <p>
                        Connect us with your finance systems to get all cost centers mapped, and all data reconciled on
                        a periodic/regular basis.
                        <br><br>
                        Open APIs available to connect.
                    </p>
                    <span></span>
                </li>
                <li>
                    <div>
                        <Single_Sign_on_Systems />
                        <h3>Single Sign-on Systems</h3>
                    </div>
                    <p>
                        We can integrate to ensure that your users don’t have to log in multiple times into different
                        logins. <br><br>
                        SSO is possible with any system that offers it.
                    </p>
                    <span></span>
                </li>
            </ul>
        </section>
    </div>
</template>

<style scoped>
.full_fourth_section {
    width: 100%;
    background: #e3f0f9;
}

.fourth_section {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
    padding: 48px 0px 100px;
    gap: 108px;
    isolation: isolate;
    width: 1366px;
    height: 543px;
    background: #e3f0f9;
    flex: none;
    order: 3;
    align-self: stretch;
    flex-grow: 0;
    margin: 0 auto;
    position: relative;
}

.fourth_section>h3 {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    padding: 0px 120px;
    gap: 50px;
    width: 1366px;
    height: 51px;
    flex: none;
    order: 0;
    align-self: stretch;
    flex-grow: 0;
    z-index: 0;
    font-family: "Extatica";
    font-style: normal;
    font-weight: 600;
    font-size: 40px;
    line-height: 128%;
    background: linear-gradient(90.37deg,
            #2d56ec 0.3%,
            #2480eb 54.66%,
            #1aacea 112.39%),
        linear-gradient(90.16deg, #355ded 0.21%, #6f33f0 100.08%), #475569;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    text-fill-color: transparent;
    flex: none;
    order: 0;
    flex-grow: 0;
}

.fourth_section>div {
    position: absolute;
    width: 772px;
    height: 161px;
    left: calc(50% - 772px / 2);
    top: 80px;
    border-radius: 12px;
    flex: none;
    order: 1;
    flex-grow: 0;
    z-index: 1;
}

.fourth_section>ul {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    padding: 0px 120px;
    gap: 32px;
    width: 1366px;
    height: 236px;
    flex: none;
    order: 2;
    align-self: stretch;
    flex-grow: 0;
    z-index: 2;
}

.fourth_section>ul>li>div {
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 0px;
    gap: 8px;
    width: 314px;
    height: 32px;
    flex: none;
    order: 0;
    align-self: stretch;
    flex-grow: 0;
    z-index: 1;
}

.fourth_section>ul>li>div>h3 {
    width: 274px;
    height: 27px;
    font-family: "Inter";
    font-style: normal;
    font-weight: 600;
    font-size: 20px;
    line-height: 134%;
    color: #475569;
    flex: none;
    order: 1;
    flex-grow: 1;
}

.fourth_section>ul>li>p {
    width: 314px;
    height: 144px;
    font-family: "Inter";
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 148%;
    color: #64748b;
    flex: none;
    order: 0;
    align-self: stretch;
    flex-grow: 0;
    z-index: 2;
}

.fourth_section>ul>li {
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 20px;
    gap: 20px;
    isolation: isolate;
    width: 354px;
    height: 236px;
    border-radius: 16px;
    flex: none;
    order: 0;
    align-self: stretch;
    flex-grow: 1;
    position: relative;
    overflow: hidden;
}

.fourth_section>ul>li:nth-child(1) {
    background: #f8fafc;
}


.fourth_section>ul>li:nth-child(1)>span {
    position: absolute;
    width: 227px;
    height: 227px;
    left: 165px;
    top: 48px;
    background: #fcb428;
    opacity: 0.3;
    filter: blur(127px);
    flex: none;
    order: 0;
    flex-grow: 0;
    z-index: 0;
}

.fourth_section>ul>li:nth-child(2) {
    background: #f8fafc;
}

.fourth_section>ul>li:nth-child(2)>span {
    position: absolute;
    width: 222px;
    height: 222px;
    left: 170px;
    top: 53px;
    background: #6cb820;
    opacity: 0.16;
    filter: blur(127px);
    flex: none;
    order: 0;
    flex-grow: 0;
    z-index: 0;
}

.fourth_section>ul>li:nth-child(3) {
    background: #f8fafc;
}

.fourth_section>ul>li:nth-child(3)>span {
    position: absolute;
    width: 222px;
    height: 222px;
    left: 170px;
    top: 53px;
    background: #888d9f;
    opacity: 0.3;
    filter: blur(137px);
    flex: none;
    order: 0;
    flex-grow: 0;
    z-index: 0;
}

@media screen and (max-width: 360px) {
    .fourth_section {
        width: 360px;
        height: fit-content;
    }

    .fourth_section>h3 {
        width: 312px;
        height: 36px;
        font-size: 28px;
    }

    .fourth_section>div {
        display: none;
    }

    .fourth_section>ul {
        flex-direction: column;
        justify-content: center;
        align-items: center;
        padding: 0px;
        gap: 20px;
        width: 312px;
        height: 796px;
        margin: 0 auto;
        margin: 0 auto;

    }

    .fourth_section>ul>li {
        width: 312px;
        height: 284px;
    }

    .fourth_section>ul>li>p {
        width: 272px;
        height: 192px;
    }
}
</style>