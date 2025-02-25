<template>
    <div class="container3">
        <a href="#" class="b">Home</a>
        <a href="#" class="b">Payment</a>
        <a href="#" class="b">Paymddent</a>
        <a href="#" class="b">Customer</a>
        <a href="#" class="b">Products</a>
        <a href="#" class="b">Reports</a>
        <a href="#" class="b3">Connect</a>
        <select name="More" id="More" class="more b5">
            <option value="">More</option>
            <option value="1">1</option>
            <option value="2">2</option>
            <option value="3">3</option>
        </select>
        <a href="#" class="b3">Developers</a>
        <label class="b3">
            <input type="checkbox" name="" id="" class="checkbox">
            <span class="btn-box">
                <span class="btn">
                </span>      
            </span>
            <span class="text">Test Mode</span>
        </label>
    </div>
</template>
<script>
    export default {
        name: 'ContainerComponent3',
    };
</script>
<style coped>
    .container3 {
    display: flex;
    border: 1px solid black;
    border-radius: 8px;
    height: 50px;
    justify-content:left;
    align-items: center;
    background-color: white;
    justify-content:space-around;
    margin-left: 10px;
    margin-right: 10px;
    }
    .more{
    border: transparent;
    }
    .btn-box {
    display:inline-block;
    vertical-align:middle;
    width: 40px;
    height: 20px;
    border-radius:100px;
    background-color: #ccc;
    box-shadow: 0px 3px 0px rgba(0,0,0,.13) inset;
}
    .btn-box .btn {
        display:inline-block;
        width: 20px;
        height: 20px;
        border-radius:50%;
        background-color: #fff;
        margin-left: 0;/*動畫從ml為0開始*/
        transition: .5s;
        box-shadow:1px 2px 5px rgba(0,0,0,.3);
    }
    .checkbox {
        position:absolute;
        opacity:0;
    }           
    .checkbox:checked + .btn-box {
    background-color: #8f8;
    }
    .checkbox:checked + .btn-box .btn {
        margin-left: 20px;
    }
</style>