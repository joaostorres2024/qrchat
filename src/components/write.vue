<template>
    <div class="input-container">
        <div class="write-container">
            <input class="number" type="text" placeholder="Your number here">
            <textarea class="message" placeholder="Write a message"></textarea>
            <button class="btn-go" type="submit">GO</button>
        </div>
        <div class="qr-code-section">
            <div class="qr-code-container">
                <!-- QR Code será inserido aqui -->
            </div>
            <div class="btn-download">
                <button class="btn-download-btn" type="submit">DOWNLOAD</button>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .write-container {
    max-width: 100%;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    display: flex;
    height: 100%;
    width: auto;
}

.qr-code-section {
    margin-right: 40px;
    margin-left: 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 20px;
}

.btn-download-btn{
    margin: 10px 0;
    cursor: pointer;
    color: #121212;
    background-color: #23E7C0;
    font-weight: bolder;
    font-size: 25px;
    border: none;
    border-radius: 10px;
    height: 60px;
    width: 250px;
}

.qr-code-container {
    border-radius: 10px;
    background: #DAF3EA;
    height: 250px;
    width: 250px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.input-container {
    justify-content: center;
    align-items: start;
    display: flex;
    flex-direction: row;
}

.btn-download {
    margin-top: 10px;
}

::placeholder {
    color: #8f8f8f;
}

.number {
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

.number:focus {
    transition: all 0.1s ease-in;
    outline: 2px solid #23E7C0;
}

.number:not(:focus) {
    transition: all 0.1s ease-out;
}

.message {
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

.message:focus {
    transition: all 0.1s ease-in;
    outline: 2px solid #23E7C0;
}

.message:not(:focus) {
    transition: all 0.1s ease-out;
}

.btn-go {
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