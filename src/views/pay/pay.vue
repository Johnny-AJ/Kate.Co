<template>
    <div>

        <!-- 关西利木津路线列表 -->
        <div class="p31">
            <div class="p31_img">
                <img src="@/assets/images/图层648.png" alt="/" />
            </div>
            <div class="el-icon-caret-right"></div>
            <div class="p31_title">关西利木津路线列表</div>
        </div>

        <div class="centre_box">
            <div class="reserve_box">
                <h2>- 05. 订单信息 -</h2>

                <div class="payment_box">

                    <div class="payment_left">
                        <div class="payment_content">
                            <!-- 1 -->
                            <div class="p41">
                                <div>
                                    <img src="../../assets/images/图层3.png" alt="/">
                                </div>
                                <div class="p40">
                                    <div class="p43">
                                        <img src="../../assets/images/图层4.png" alt="">
                                    </div>
                                    <div class="payment_price">$ 1,918.00 </div>
                                    <div class="p43">
                                        <img src="../../assets/images/xiala2拷贝.png" alt="">
                                    </div>
                                </div>
                            </div>

                            <div class="payment_title">Hello, little! <div class="payment_you">Is this not you?</div>
                            </div>

                            <div class="paymene_complete">
                                <div class="cont1">
                                    <img src="../../assets/images/suo.png" alt="/">
                                </div>
                                <div class="payment_add">Please add a credit or debit card to complete the purchase.
                                </div>
                            </div>

                            <div class="payment_input">
                                <div>
                                    <el-input placeholder="First Name" style="width: 220px;"></el-input>
                                </div>
                                <div>
                                    <el-input placeholder="Family Name" style="width: 220px;">
                                    </el-input>
                                </div>
                            </div>

                            <div class="payment_multiple">
                                <div>
                                    <img src="../../assets/images/图层12.png" alt="">
                                </div>
                                <div>
                                    <img src="../../assets/images/图层15.png" alt="">
                                </div>
                                <div>
                                    <img src="../../assets/images/图层16.png" alt="">
                                </div>
                                <div>
                                    <img src="../../assets/images/图层15.png" alt="">
                                </div>
                            </div>

                            <div class="payment_Billing">
                                <el-input placeholder="The card number"></el-input>
                            </div>

                            <div class="payment_Valid">
                                <div>
                                    <div class="font_s">Valid term</div>
                                    <div>
                                        <el-input placeholder="MM/YY" style="width: 220px;"></el-input>
                                    </div>
                                </div>
                                <div>
                                    <div class="font_s">CSC</div>
                                    <div>
                                        <el-input placeholder="The last 3 digits" style="width: 220px;"
                                            suffix-icon="el-icon-bank-card">
                                        </el-input>
                                    </div>
                                </div>
                            </div>


                            <div class="payment_Billing">
                                <div class="payment_address">
                                    <div class="font_s">Billing address</div>
                                    <div class="blue">add</div>
                                </div>
                                <div>
                                    <el-select v-model="value" placeholder="Add shipping address" style="width: 100%;">
                                        <el-option v-for="item in options" :key="item.value" :label="item.label"
                                            :value="item.value">
                                        </el-option>
                                    </el-select>
                                </div>
                            </div>


                            <div class="add_btn">
                                <div class="btn_add">Add</div>
                            </div>


                        </div>
                    </div>


                    <div class="payment_right">

                        <div class="payment_right_nav">

                            <div class="PayPal_img">
                                <img src="../../assets/images/scr_vp_fprd_shield_bags.png" alt="">
                            </div>
                            <div class="PayPal_title">
                                <div>PayPal is a safer and more</div>
                                <div>convenient way to pay</div>
                            </div>
                            <div class="security">
                                <div class="financial">
                                    No matter where you shop, we will help you to ensure the security of your financial
                                    information.
                                </div>
                            </div>

                        </div>

                    </div>

                </div>


                <div class="current_nab">

                    <div class="nab_box">

                        <div class="nab_title">Cancel and return to USJ</div>

                        <div class="nab_bot">

                            <div class="nab_clause">
                                <div class="n1">clause</div>
                                <div class="n1">Privacy protection</div>
                                <div class="n1">feedback</div>
                            </div>

                            <div class="nab_time">
                                <div class="time">© 1999 - 2019</div>
                                <div>
                                    <img src="../../assets/images/suo.png" alt="/" />
                                </div>
                            </div>
                        </div>

                    </div>

                    <div class="Consumer">
                        Consumer tip -- PayPal Pte. Ltd. Is the holder of PayPal's value storage tool and does not need
                        to
                        be approved by the monetary authority of Singapore. Users are advised to read
                        <span>the terms and conditions carefully</span>
                    </div>

                </div>

            </div>
        </div>

    </div>
</template>

<script>
    export default {
        name: 'order',
        data() {
            return {
                radio: '',
                options: [
                    {
                        value: '选1',
                        label: 'A'
                    },
                    {
                        value: '选2',
                        label: 'B'
                    },
                    {
                        value: '选3',
                        label: 'C'
                    }
                ]
            }
        }
    }
</script>

<style scoped>
    /* 按钮 */
    /deep/ .el-radio {
        padding: 0;
        margin: 0;
    }
</style>

<style scoped lang="scss">
    /* 关西利木津路线列表  */
    .p31 {
        /* width: 960px; */
        /* height: 45px; */
        /* background: rgba(255, 255, 255, 1); */
        border-bottom: 1px solid #ffe5e5e5;
        display: flex;
        align-items: center;
        line-height: 45px;
        box-sizing: border-box;
        padding-left: 115px;
        margin-bottom: 60px;
    }

    .p31_img {
        margin-right: 10px;
    }

    .p31_img img {
        width: 100%;
    }

    .p31_title {
        font-size: 9px;
        font-family: Taipei Sans TC Beta;
        font-weight: 400;
        color: rgba(0, 0, 0, 1);
        margin-left: 10px;
    }

    /* reserve_box */
    .reserve_box {
        /* width: 330px; */
        width: 100%;
        /* border: 1px solid red; */
        margin-bottom: 117px;
    }

    h2 {
        /* font-size: 18px; */
        /* font-family: Taipei Sans TC Beta; */
        font-weight: 400;
        color: rgba(1, 49, 146, 1);
        margin-bottom: 16.5px;
        text-align: center;
    }

    /* 1 */
    .payment_nav {
        /* border: 1px solid red; */
        background-color: #fff;
        padding-top: 33px;
    }

    .payment_box {
        width: 97%;
        height: 100%;
        /* border: 1px solid red; */
        box-sizing: border-box;
        margin: 0 auto;
        display: flex;
        background: rgba(255, 255, 255, 1);
        border: 1px solid rgba(222, 222, 222, 1);
        border-radius: 4px;
    }

    .payment_left {
        width: 60%;
        /* border: 1px solid blue; */
    }

    .payment_content {
        margin-left: 1.875rem;

        margin-top: 1.9375rem;
        /* border: 1px solid red; */
    }

    .p40 {
        display: flex;
        align-items: center;
    }

    .p41 {
        display: flex;
        justify-content: space-between;
    }

    .p41 img {
        width: 100%;
    }

    .p43 img {
        width: 100%;
    }

    .payment_price {
        font-size: 1.875rem;
        font-family: SF Pro Text;
        font-weight: 400;
        color: rgba(255, 87, 34, 1);
    }

    .payment_title {
        display: flex;
        font-size: 1rem;
        font-family: SF Pro Text;
        font-weight: 400;
        color: rgba(13, 18, 21, 1);
        margin-bottom: 1.5rem;
        border-top: 1px solid #FFAAAAAA;
        padding-top: 1.75rem;
    }

    .paymene_complete {
        display: flex;
        background: rgba(170, 170, 170, 1);
        border-radius: 4px;
        line-height: 50px;
        margin-bottom: 1.5rem;
    }

    .payment_add {
        font-size: 16px;
        font-family: SF Pro Text;
        font-weight: 400;
        color: rgba(238, 238, 238, 1);
        margin-left: .625rem;
        /* padding-left: .625rem; */
    }

    .payment_input {
        display: flex;
        align-items: center;
        justify-content: space-between;
        margin-bottom: 1.5rem;
    }

    .payment_multiple {
        display: flex;
        /* align-items: center; */
        /* line-height: 10px; */
        /* margin: 0 auto; */
        background: rgba(242, 243, 244, 1);
        border: 1px solid rgba(222, 222, 222, 1);
        border-radius: 4px;
        margin-bottom: 1.5rem;
    }

    .payment_multiple img {
        width: 70%;
        margin-left: 15px;
        margin-top: .3125rem;
    }

    .add_btn {
        width: 100%;
        /* border: 1px solid blue; */
        background: rgba(0, 112, 186, 1);
        border-radius: 4px;
        /* line-height: 23px; */
        text-align: center;
        margin-bottom: 5rem;
    }

    .btn_add {
        font-size: 30px;
        font-family: SF Pro Text;
        font-weight: 400;
        color: rgba(254, 255, 254, 1);
        line-height: 2.8125rem;
    }

    .payment_address {
        display: flex;
        align-items: center;
        justify-content: space-between;
    }

    .font_s {
        font-size: 16px;
        font-family: SF Pro Text;
        font-weight: 400;
        color: rgba(51, 51, 51, 1);
    }

    .payment_Valid {
        display: flex;
        justify-content: space-between;
        margin-bottom: 1.5rem;
    }

    .blue {
        font-size: 16px;
        font-family: SF Pro Text;
        font-weight: 400;
        color: rgba(0, 112, 186, 1);
    }

    .payment_you {
        font-size: 16px;
        font-family: SF Pro Text;
        font-weight: 400;
        color: #FF019CDE;
    }

    .cont1 {
        margin-left: .625rem;
    }

    .payment_Billing {
        margin-bottom: 1.5rem;

    }

    /*  payment_right */
    .payment_right {
        width: 50%;
        /* height: 800px; */
        /* border: 1px solid black; */
        text-align: center;
        position: relative;
    }

    .payment_right_nav {
        position: absolute;
        top: 14.6875rem;
        right: -1.25rem;
    }

    .PayPal_img img {
        width: 50%;
        /* height: 90%; */
    }

    .PayPal_title {
        font-size: 30px;
        font-family: SF Pro Text;
        font-weight: 400;
        color: rgba(51, 51, 51, 1);
        text-align: center;
    }

    .security {
        width: 70%;
        text-align: center;
        margin: 30px 75px;
    }

    .financial {
        font-size: 14px;
        font-family: SF Pro Text;
        font-weight: 400;
        color: rgba(51, 51, 51, 1);
    }

    /*  current_nab*/
    .current_nab {
        /* width: 61rem; */
        /* margin-top: 1.5rem; */
        /* margin-left: 1.375rem; */
        /* border: 1px solid black; */
        /* margin-bottom: 2.5rem; */
        margin: 0 auto;
        height: 100%;
    }

    .nab_box {
        display: flex;
        /* align-items: center; */
        justify-content: space-between;
        margin-top: 0.5rem;
    }

    .nab_title {
        font-size: 16px;
        font-family: SF Pro Text;
        font-weight: 400;
        color: rgba(0, 112, 186, 1);
    }

    .nab_clause {
        display: flex;
    }

    .n1 {
        font-size: 16px;
        font-family: SF Pro Text;
        font-weight: 400;
        color: rgba(51, 51, 51, 1);
        margin-right: 20px;
    }

    .nab_time {
        display: flex;
        /* align-items: center; */
        margin-right: 10px;
    }

    .time {
        margin-right: 10px;
    }

    .nab_bot {
        display: flex;
    }

    .Consumer {
        font-size: 16px;
        font-family: SF Pro Text;
        font-weight: 400;
        color: rgba(51, 51, 51, 1);
        text-align: center;
        margin-top: 1.5rem;
        margin-bottom: 1.25rem;
    }
</style>