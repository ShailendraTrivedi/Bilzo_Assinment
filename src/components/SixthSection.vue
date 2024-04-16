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
</style>