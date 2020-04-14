<template>
<div>
    <table class="tableone">
        <tr>
            <td id="name">سیگنال رایگان</td>
            <td style="background-color: rgb(81, 160, 81);">
                <p style="border-bottom:1px solid black; height:20px; margin:5px ">2020.04.07 Tehran 12:36</p>
                <p style="margin:0px; color:white">EUR/USD <span style="color:rgb(218, 81, 81); font-weight:800;">(50 pip) </span></p>
                Buy Price : <span style="color:white"> 1.04325 </span>
                <br>
                Stop Loss :  <span style="color:white"> 1.04325 </span>
                <br>
                Take Profit :  <span style="color:white"> 1.04325 </span>
            </td>
        </tr>
        <tr>
            <td id="name">نقره ای</td>
            <td><span class="lock"> <img src="./lock-solid.svg" alt=""></span>
            <br>
            <button>خرید</button>
            </td>
            <td><span class="lock"> <img src="./lock-solid.svg" alt=""></span>
            <br>
            <button>خرید</button>
            </td>
        </tr>
        <tr>
            <td id="name">طلایی</td>
            <td><span class="lock"> <img src="./lock-solid.svg" alt=""></span>
            <br>
            <button>خرید</button>
            </td>
            <td><span class="lock"> <img src="./lock-solid.svg" alt=""></span>
            <br>
            <button>خرید</button>
            </td>
            <td><span class="lock"> <img src="./lock-solid.svg" alt=""></span>
            <br>
            <button>خرید</button>
            </td>
            <td><span class="lock"> <img src="./lock-solid.svg" alt=""></span>
            <br>
            <button>خرید</button>
            </td>
        </tr>
        <tr>
            <td class="diamond-top" id="name"> <span style="visibility:hidden">الماس </span></td>
            <td><span class="lock"> <img src="./lock-solid.svg" alt=""></span>
            <br>
            <button>خرید</button>
            </td>
            <td><span class="lock"> <img src="./lock-solid.svg" alt=""></span>
            <br>
            <button>خرید</button>
            </td>
            <td><span class="lock"> <img src="./lock-solid.svg" alt=""></span>
            <br>
            <button>خرید</button>
            </td>
            <td><span class="lock"> <img src="./lock-solid.svg" alt=""></span>
            <br>
            <button>خرید</button>
            </td>
        </tr>
         <tr>
            <td class="diamond-bottom" id="name"><span class="diamond-text">الماس</span></td>
            <td><span class="lock"> <img src="./lock-solid.svg" alt=""></span>
            <br>
            <button>خرید</button>
            </td>
            <td><span class="lock"> <img src="./lock-solid.svg" alt=""></span>
            <br>
            <button>خرید</button>
            </td>
            <td><span class="lock"> <img src="./lock-solid.svg" alt=""></span>
            <br>
            <button>خرید</button>
            </td>
            <td><span class="lock"> <img src="./lock-solid.svg" alt=""></span>
            <br>
            <button>خرید</button>
            </td>
        </tr>
    </table>
</div>
</template>
<script>
export default{

}
</script>
<style>
.lock img{
    width: 20px;
    height: 20px;
}
#name{
    font-size: 20px;
    font-weight: 600;
}
.diamond-text{
    position: absolute;
    transform: translateX(-15px) translateY(-56px);
}
.diamond-top{
    border-bottom: 0;
    border-bottom-right-radius:0px ;
    border-bottom-left-radius:0px ;
}
.diamond-bottom{
    border-top: 0;
    border-top-right-radius:0px ;
    border-top-left-radius:0px ;
}
.tableone{
    width: 1000px;
    margin-top: 20px;
    text-align:center;
    font-size:15px;
    font-weight: 500;
    margin-left: 150px;
    border-spacing: 0px;
}
td button{
    border:none;
    outline: none;
    width: 50px;
    height: 20px;
    border-radius: 5PX;
    background-color: gray;
    cursor: pointer;
}
td{
    width: 200px;
    height: 100px;
    border: 1px solid white;
    border-radius: 5px;
    background-color: gainsboro;
    margin: 1px 1px 1px 1px;

}

</style>