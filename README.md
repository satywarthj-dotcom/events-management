<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grand Music Event Booking</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; text-align: center; color: #333; }
        header { background: #5f259f; color: white; padding: 25px 15px; }
        header h1 { margin: 0; font-size: 24px; }
        header p { margin-top: 5px; opacity: 0.9; }
        .container { padding: 20px 15px; }
        .event-card { background: white; margin: 0 auto; padding: 20px; max-width: 380px; border-radius: 12px; box-shadow: 0 4px 15px rgba(0,0,0,0.1); }
        .event-card h2 { color: #5f259f; margin-top: 0; }
        .details { text-align: left; background: #f8f9fa; padding: 12px 15px; border-radius: 8px; margin: 15px 0; font-size: 15px; line-height: 1.6; }
        .qr-box { border: 2px dashed #5f259f; padding: 15px; border-radius: 10px; background-color: #faf7ff; margin-top: 15px; }
        .qr-box h3 { margin: 0 0 10px 0; font-size: 16px; color: #5f259f; }
        .qr-img { width: 220px; height: auto; border-radius: 8px; border: 3px solid #5f259f; }
        .note { color: #d32f2f; font-size: 13px; margin: 12px 0; font-weight: bold; }
        .btn-wa { background: #25D366; color: white; padding: 12px 18px; text-decoration: none; border-radius: 25px; display: inline-block; font-weight: bold; font-size: 14px; box-shadow: 0 3px 6px rgba(0,0,0,0.2); }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to Events Management</h1>
        <p>हमारे आगामी इवेंट्स के टिकट यहाँ से बुक करें</p>
    </header>

    <div class="container">
        <div class="event-card">
            <h2>Grand Music & Cultural Night</h2>
            
            <div class="details">
                <p>25 <b>sep:</b> 25sep 2026</p>
                <p>📍 <b>स्थान:</b> मुख्य ऑडिटोरियम, जयपुर (राजस्थान)</p>
                <p>🎟️ <b>टिकट मूल्य:</b> ₹500 प्रति व्यक्ति</p>
            </div>

            <div class="qr-box">
                <h3>PhonePe / Google Pay से स्कैन करके भुगतान करें:</h3>
                
                <!-- यहाँ आपकी अपलोड की गई QR कोड फोटो का नाम आएगा -->
                <img src="Screenshot_20260919_16.jpg" alt="PhonePe QR Code" class="qr-img">

                <p class="note">⚠️ पेमेंट करने के बाद स्क्रीनशॉट और अपना नाम नीचे दिए गए WhatsApp बटन पर भेजें:</p>
                
                <!-- 9358591677 की जगह अपना असली WhatsApp नंबर डालें -->
                <a href="https://wa.me/919876543210?text=नमस्ते,%20मैंने%20इवेंट%20की%20टिकट%20का%20भुगतान%20कर%20दिया%20है।" class="btn-wa">
                   💬 WhatsApp पर पेमेंट स्क्रीनशॉट भेजें
                </a>
            </div>
        </div>
    </div>

</body>
</html>
