function sendToTelegram() {
    const token = "YOUR_BOT_TOKEN"; // ከBotFather ያገኙት
    const chatId = "YOUR_CHAT_ID"; // የእርስዎ የግል ID
    const message = "አዲስ የጥገና ትዕዛዝ ከTechfix ዌብሳይት ደርሶዎታል!";

    const url = `https://api.telegram.org/bot${token}/sendMessage?chat_id=${chatId}&text=${encodeURIComponent(message)}`;

    fetch(url)
        .then(response => {
            if(response.ok) {
                alert("መልእክትዎ ተልኳል! እናመሰግናለን።");
            }
        })
        .catch(error => console.error('Error:', error));
}
