<script>
export default {
    name: 'SixthSection',
    components: {
    }
}
</script>
<template>
    <div class="full_sixth_section">
        <section class="sixth_section">
            <div>
                <h1>Manage your travel and expenses the smart way!</h1>
                <div class="input_values">
                    <div>
                        <input type="text" class="" placeholder="Name" />
                        <input type="text" class="" placeholder="Official email ID" />
                        <button>Start trial</button>
                    </div>
                    <div>
                        <p>30 Days free trial</p>
                        <span></span>
                        <p>Upto 10 users</p>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<style scoped>
.full_sixth_section {
    width: 100%;
    background: #e3f0f9;
}

.sixth_section {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 48px 0px;
    gap: 10px;
    width: 1366px;
    height: 263px;
    flex: none;
    order: 5;
    align-self: stretch;
    flex-grow: 0;
    margin: 0 auto;
}

.sixth_section>div {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 0px;
    gap: 36px;
    width: 1366px;
    height: 167px;
    flex: none;
    order: 0;
    flex-grow: 0;
}

.sixth_section>div>h1 {
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

.input_values {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 0px;
    gap: 16px;
    width: 689px;
    height: 80px;
    flex: none;
    order: 1;
    flex-grow: 0;
}

.input_values div:nth-child(1) {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    padding: 0px;
    gap: 16px;
    width: 689px;
    height: 44px;
    flex: none;
    order: 0;
    flex-grow: 0;
    margin: 0 auto;
}

.input_values div:nth-child(2) {
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 0px;
    gap: 12px;
    width: 265px;
    height: 20px;
    flex: none;
    order: 1;
    flex-grow: 0;
    margin: 0 auto;
}

.input_values div:nth-child(2)>p {
    width: 130px;
    height: 20px;
    font-family: "Inter";
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 128%;
    color: #64748b;
    flex: none;
    flex-grow: 0;
}

.input_values div:nth-child(2)>span {
    width: 6px;
    height: 6px;
    background: #94a3b8;
    border-radius: 100%;
    flex: none;
    flex-grow: 0;
}

.input_values div:nth-child(1)>input:focus {
    outline: none;
}

.input_values div:nth-child(1)>input {
    box-sizing: border-box;
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 12px 16px;
    gap: 10px;
    background: #f1f5f9;
    border: 1px solid #cbd5e1;
    border-radius: 4px;
    flex: none;
    order: 0;
    flex-grow: 0;
    font-family: "Inter";
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 128%;
    color: #94a3b8;
}

.input_values div:nth-child(1) input:nth-child(1) {
    width: 200px;
    height: 44px;
}

.input_values div:nth-child(1) input:nth-child(2) {
    width: 352px;
    height: 44px;
}
</style>