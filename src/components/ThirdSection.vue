<script>
import '../assets/css/third_section.css'
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
