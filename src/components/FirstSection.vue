<script>
export default {
  name: 'FirstSection'
}
</script>
<template>
  <section class="first_section">
    <div>
      <div>
        <div>The World’s Most Configurable</div>
        <div>Travel & Expense Management Software</div>
      </div>
      <p>
        Configure <span>any</span> rule. Enable a world class mobile experience for your users. Get
        seamless reporting & integrations. Inbuilt OCR expense scanning. Manage travel & non-travel
        expenses. Open APIs to connect with external systems.
      </p>
    </div>
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
  </section>
</template>

<style scoped>
.first_section {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 56px 244px;
  gap: 40px;
  width: 1366px;
  height: 462px;
  flex: none;
  order: 1;
  align-self: stretch;
  flex-grow: 0;
  margin: 0 auto;
}

.first_section>div {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 0px;
  gap: 36px;
  width: 975px;
  height: 230px;
  flex: none;
  order: 0;
  flex-grow: 0;
}

.first_section>div>div {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 0px;
  gap: 8px;
  width: 975px;
  height: 116px;
  flex: none;
  order: 0;
  align-self: stretch;
  flex-grow: 0;
}

.first_section>div>p {
  width: 878px;
  height: 78px;
  font-family: 'Inter';
  font-style: normal;
  font-weight: 400;
  font-size: 20px;
  line-height: 128%;
  text-align: center;
  color: #64748b;
  flex: none;
  order: 1;
  flex-grow: 0;
}

.first_section>div>p>span {
  text-decoration-line: underline;
  text-decoration-color: #1aacea;
  background: linear-gradient(90.16deg, #2d56ec 0.21%, #1aacea 100.08%), #64748b;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  text-fill-color: transparent;
}

.first_section>div>div div:nth-child(1) {
  width: 411px;
  height: 36px;
  font-family: 'Inter';
  font-style: normal;
  font-weight: 500;
  font-size: 28px;
  line-height: 128%;
  text-align: center;
  background: linear-gradient(90.16deg, #2d56ec 0.21%, #1aacea 100.08%), #64748b;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  text-fill-color: transparent;
  flex: none;
  order: 0;
  flex-grow: 0;
}

.first_section>div>div div:nth-child(2) {
  width: 975px;
  height: 72px;
  font-family: 'Extatica';
  font-style: normal;
  font-weight: 600;
  font-size: 54px;
  line-height: 128%;
  text-align: center;
  color: #334155;
  flex: none;
  order: 1;
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
  font-family: 'Inter';
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
  font-family: 'Inter';
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