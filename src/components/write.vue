<template>
    <div class="write-container">
        <input class="number" type="text" placeholder="Your number here">
        <textarea class="message" placeholder="Write a message"></textarea>
        <button class="btn-go" type="submit">GO</button>
    </div>
    <div class="qr-code-container">

    </div>
</template>

<style scoped>
    .write-container{
        flex-direction: column;
        align-items: center;
        justify-content: center;
        height: auto;
        width: 100vw;
        display: flex;
    }

    ::placeholder{
        color: #8f8f8f;
    }

    .number{
        margin: 20px 0;
        font-family: 'Poppins';
        outline: #FCFCFC;
        border: none;
        border-radius: 10px;
        background-color: #DAF3EA;
        padding: 15px;
        font-size: 20px;
        height: 60px;
        width: 400px;
    }

    .number:focus{
        transition: all 0.1s ease-in;
        outline: 2px solid #23E7C0;
    }

    .number:not(:focus){
        transition: all 0.1s ease-out;
    }

    .message{
        resize: none;
        font-family: 'Poppins';
        outline: #FCFCFC;
        border: none;
        border-radius: 10px;
        background-color: #DAF3EA;
        padding: 15px;
        font-size: 20px;
        height: 200px;
        width: 400px;
    }

    .message:focus{
        transition: all 0.1s ease-in;
        outline: 2px solid #23E7C0;
    }

    .message:not(:focus){
        transition: all 0.1s ease-out;
    }

    .btn-go{
        margin: 20px 0;
        cursor: pointer;
        color: #121212;
        background-color: #23E7C0;
        font-weight: bolder;
        font-size: 25px;
        border: none;
        border-radius: 10px;
        height: 60px;
        width: 400px;
    }

</style>

<script>

</script>