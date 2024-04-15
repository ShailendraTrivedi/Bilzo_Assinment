<script>
import '../assets/css/fourth_section.css'
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
            <div>Integrations</div>
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
