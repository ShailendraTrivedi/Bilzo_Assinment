<script>
export default {
    name: "FifthSection"
}
</script>

<template>
    <section class="fifth_section">
        <div>Our customers love us</div>
        <ul>
            <li>
                <p>
                    ExpenseBook has truly streamlined our travel setup. No more emails and delays in booking. No mor
                    unknown overruns in expense. Everything is trackable, and the configurability they offer is
                    outstanding.
                </p>
                <div>
                    <img src="../assets/images/Rohit_Mehra.png" alt="">
                    <div>
                        <h5>Rohit Mehra</h5>
                        <p>CFO, XYZ</p>
                    </div>
                </div>
            </li>
            <li>
                <p>
                    ExpenseBook has truly streamlined our travel setup. No more emails and delays in booking. No mor
                    unknown overruns in expense. Everything is trackable, and the configurability they offer is
                    outstanding.
                </p>
                <div>
                    <img src="../assets/images/Alan_Turing.png" alt="">
                    <div>
                        <h5>Alan Turing</h5>
                        <p>CFO, XYZ</p>
                    </div>
                </div>
            </li>
            <li>
                <p>
                    ExpenseBook has truly streamlined our travel setup. No more emails and delays in booking. No mor
                    unknown overruns in expense. Everything is trackable, and the configurability they offer is
                    outstanding.
                </p>
                <div>
                    <img src="../assets/images/Mark_Jacob.png" alt="">
                    <div>
                        <h5>Mark Jacob</h5>
                        <p>CFO, XYZ</p>
                    </div>
                </div>
            </li>
        </ul>
    </section>
</template>

<style scoped>
.fifth_section {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 80px 0px 120px;
    gap: 70px;
    width: 1366px;
    height: 589px;
    flex: none;
    order: 4;
    align-self: stretch;
    flex-grow: 0;
    margin: 0 auto;
}

.fifth_section>div {
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

.fifth_section>ul {
    display: flex;
    flex-direction: row;
    align-items: flex-end;
    padding: 0px 120px;
    gap: 40px;
    width: 1366px;
    height: 268px;
    flex: none;
    order: 1;
    align-self: stretch;
    flex-grow: 0;
}

.fifth_section>ul>li>p {
    width: 300.67px;
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
}

.fifth_section>ul>li>div {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    padding: 0px;
    gap: 15px;
    width: 180px;
    height: 48px;
    flex: none;
    order: 1;
    flex-grow: 0;
}

.fifth_section>ul>li>div>div>h5 {
    width: 117px;
    height: 28px;
    font-family: "Inter";
    font-style: normal;
    font-weight: 600;
    font-size: 20px;
    line-height: 142%;
    color: #475569;
    flex: none;
    order: 0;
    flex-grow: 0;
}

.fifth_section>ul>li>div>div>p {
    width: 64px;
    height: 16px;
    font-family: "Inter";
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 116%;
    color: #64748b;
    flex: none;
    order: 1;
    flex-grow: 0;
}

.fifth_section>ul>li:nth-child(1) {
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 24px;
    gap: 28px;
    width: 348.67px;
    height: 268px;
    background: rgba(54, 94, 238, 0.1);
    border: 1px solid rgba(54, 94, 238, 0.3);
    border-radius: 12px;
    flex: none;
    order: 0;
    flex-grow: 1;
}

.fifth_section>ul>li:nth-child(2) {
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 24px;
    gap: 28px;
    width: 348.67px;
    height: 268px;
    background: rgba(26, 172, 234, 0.1);
    border: 1px solid rgba(26, 172, 234, 0.3);
    border-radius: 12px;
    flex: none;
    order: 1;
    flex-grow: 1;
}

.fifth_section>ul>li:nth-child(3) {
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 24px;
    gap: 28px;
    width: 348.67px;
    height: 268px;
    background: rgba(36, 128, 235, 0.1);
    border: 1px solid rgba(36, 128, 235, 0.3);
    border-radius: 12px;
    flex: none;
    order: 2;
    flex-grow: 1;
}
</style>