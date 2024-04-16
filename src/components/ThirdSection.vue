<script>
import Setup_Employee_Groups from "../assets/icons/Setup_Employee_Groups.vue"
import The_Definitive_Rule_Engine from "../assets/icons/The_Definitive_Rule_Engine.vue"
import Customized_Reports from "../assets/icons/Customized_Reports.vue"
import Superior_Employee_Experience from "../assets/icons/Superior_Employee_Experience.vue"
import Easy_Integrations from "../assets/icons/Easy_Integrations.vue"
import Configurable_Workflows from "../assets/icons/Configurable_Workflows.vue"
import Scan_any_Bill from "../assets/icons/Scan_any_Bill.vue"
import AI_Based_Concierge from "../assets/icons/AI_Based_Concierge.vue"
import AI_Assisted_Trip_Planning from "../assets/icons/AI_Assisted_Trip_Planning.vue"
export default {
    name: 'ThirdSection',
    components: {
        Setup_Employee_Groups: Setup_Employee_Groups,
        The_Definitive_Rule_Engine: The_Definitive_Rule_Engine,
        Customized_Reports: Customized_Reports,
        Superior_Employee_Experience: Superior_Employee_Experience,
        Easy_Integrations: Easy_Integrations,
        Configurable_Workflows: Configurable_Workflows,
        Scan_any_Bill: Scan_any_Bill,
        AI_Based_Concierge: AI_Based_Concierge,
        AI_Assisted_Trip_Planning: AI_Assisted_Trip_Planning
    }
}
</script>
<template>
    <section class="third_section">
        <div>
            <h1>Features that suit your needs</h1>
            <div>
                <ul>
                    <li>
                        <div>
                            <div>
                                <span></span>
                                <div>
                                    <Setup_Employee_Groups />
                                </div>
                                <h5>Setup Employee Groups</h5>
                            </div>
                        </div>
                        <p>Use any parameter to setup distinct
                            employee groups to implement policies</p>
                    </li>
                    <li>
                        <div>
                            <div>
                                <span></span>
                                <div>
                                    <The_Definitive_Rule_Engine />
                                </div>
                                <h5>The Definitive Rule Engine</h5>
                            </div>
                        </div>
                        <p>Configure ANY policy - and if you can’t configure it, we promise to work on it for free</p>
                    </li>
                    <li>
                        <div>
                            <div>
                                <span></span>
                                <div>
                                    <Customized_Reports />
                                </div>
                                <h5>Customized Reports</h5>
                            </div>
                        </div>
                        <p>Setup the reports that you want using our seamless reporting engine.</p>
                    </li>
                </ul>
                <ul>
                    <li>
                        <div>
                            <div>
                                <span></span>
                                <div>
                                    <Superior_Employee_Experience />
                                </div>
                                <h5>Superior Employee Experience</h5>
                            </div>
                        </div>
                        <p>Manage all expenses and travel requests easily. Empower your employees with personalized
                            reports.</p>
                    </li>
                    <li>
                        <div>
                            <div>
                                <span></span>
                                <div>
                                    <Easy_Integrations />
                                </div>
                                <h5>Easy Integrations</h5>
                            </div>
                        </div>
                        <p>Integrate with your upstream, HRMS or your downstream finance system to seamlessly deliver
                            value through our Open APIs.</p>
                    </li>
                    <li>
                        <div>
                            <div><span></span>
                                <div>
                                    <Configurable_Workflows />
                                </div>
                                <h5>Configurable Workflows</h5>
                            </div>
                        </div>
                        <p>Configure approvals or rejections. Escalations and reports. At will. Setup new groups.</p>
                    </li>
                </ul>
                <ul>
                    <li>
                        <div>
                            <div>
                                <span></span>
                                <div>
                                    <Scan_any_Bill />
                                </div>
                                <h5>Scan any Bill</h5>
                            </div>
                        </div>
                        <p>The world’s best OCR system backs up this product. All data goes in. 99% success.</p>
                    </li>
                    <li>
                        <div>
                            <div>
                                <span></span>
                                <div>
                                    <AI_Based_Concierge />
                                </div>
                                <h5>AI-Based Concierge</h5>
                            </div>
                            <div>Coming soon</div>
                        </div>
                        <p>Ask the concierge to change things during your travel - and it will trigger relevant
                            actions 24x7.</p>
                    </li>
                    <li>
                        <div>
                            <div>
                                <span></span>
                                <div>
                                    <AI_Assisted_Trip_Planning />
                                </div>
                                <h5>AI-Assisted Trip Planning</h5>
                            </div>
                            <div>Coming soon</div>
                        </div>
                        <p>Just tell us what you want to do in normal language and we will try and put together the best
                            itinerary for you.</p>
                    </li>
                </ul>
            </div>
        </div>
    </section>
</template>

<style scoped>
.third_section {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 80px 0px 0px;
    gap: 80px;
    width: 1366px;
    height: 683px;
    flex: none;
    order: 2;
    align-self: stretch;
    flex-grow: 0;
    margin: 0 auto;
}

.third_section>div {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 0px;
    gap: 48px;
    width: 1366px;
    height: 521px;
    flex: none;
    order: 0;
    align-self: stretch;
    flex-grow: 0;
}

.third_section>div>h1 {
    width: 413px;
    height: 41px;
    font-family: 'Extatica';
    font-style: normal;
    font-weight: 600;
    font-size: 32px;
    line-height: 128%;
    text-align: center;
    background: linear-gradient(90.37deg, #2d56ec 0.3%, #1aacea 112.39%),
        linear-gradient(90.16deg, #355ded 0.21%, #6f33f0 100.08%), #475569;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    text-fill-color: transparent;
    flex: none;
    order: 0;
    flex-grow: 0;
}

.third_section>div>div {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: space-between;
    padding: 0px 120px;
    gap: 48px;
    width: 1366px;
    height: 432px;
    flex: none;
    order: 1;
    align-self: stretch;
    flex-grow: 0;
}

.third_section>div>div>ul {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    padding: 0px;
    width: 1126px;
    height: 96px;
    flex: none;
    order: 0;
    align-self: stretch;
    flex-grow: 0;
}

.third_section>div>div>ul>li {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px;
    gap: 16px;
    width: 351.33px;
    height: 96px;
    flex: none;
    order: 0;
    align-self: stretch;
    flex-grow: 0;
}

@media screen and (max-width: 400px) {
    .third_section {
        width: 360px;
        padding: 0;
    }

    .third_section>div {
        padding: 48px 24px;
        gap: 36px;
        width: 360px;
        height: 1572px;
    }

    .third_section>div>h1 {
        width: 312px;
        height: 72px;
        font-size: 28px;
    }

    .third_section>div>div {
        flex-direction: column;
        align-items: center;
        gap: 36px;
        width: 312px;
        padding: 0;
    }

    .third_section>div>div>ul {
        display: flex;
        flex-direction: column;
        height: fit-content;
        width: fit-content;
        gap: 40px;
    }

    .third_section>div>div>ul>li {
        width: 312px;
    }
}

.third_section>div>div>ul>li>p {
    width: 351.33px;
    height: 48px;
    font-family: "Inter";
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 148%;
    color: #64748b;
    flex: none;
    order: 1;
    align-self: stretch;
    flex-grow: 0;
}

.third_section>div>div>ul>li>div {
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 0px;
    gap: 8px;
    width: 363.33px;
    height: 32px;
    flex: none;
    order: 1;
    align-self: stretch;
    flex-grow: 0;
    z-index: 1;
}

.third_section>div>div>ul>li>div>div:nth-child(1) {
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 0px;
    gap: 12px;
    isolation: isolate;
    width: 253px;
    height: 32px;
    flex: none;
    order: 0;
    flex-grow: 0;
    position: relative;
    z-index: 0;
}

.third_section>div>div>ul>li>div>div:nth-child(1)>div {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 10px;
    width: 32px;
    height: 32px;
    background: #365eee;
    border-radius: 2px;
    flex: none;
    order: 1;
    flex-grow: 0;
    z-index: 1;
}

.third_section>div>div>ul>li>div>div:nth-child(1)>span {
    position: absolute;
    width: 32px;
    height: 32px;
    left: 0px;
    top: 0px;
    background: rgba(54, 94, 238, 0.2);
    border-radius: 2px;
    transform: rotate(-45deg);
    flex: none;
    order: 0;
    flex-grow: 0;
    z-index: 0;
}

.third_section>div>div>ul>li>div>div:nth-child(1)>h5 {
    width: 100%;
    height: 25px;
    font-family: "Inter";
    font-style: normal;
    font-weight: 600;
    font-size: 16px;
    line-height: 140%;
    color: #475569;
    flex: none;
    order: 2;
    flex-grow: 0;
    z-index: 2;
}

.third_section>div>div>ul>li>div>div:nth-child(2) {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    padding: 2px 6px;
    gap: 10px;
    width: 88px;
    height: 21px;
    background: rgba(235, 163, 28, 0.2);
    border-radius: 2px;
    flex: none;
    order: 2;
    flex-grow: 0;
    z-index: 2;
    font-family: "Inter";
    font-style: normal;
    font-weight: 500;
    font-size: 12px;
    line-height: 142%;
    color: #eba31c;
    flex: none;
    order: 0;
    flex-grow: 0;
}
</style>