---
title: एज-कंप्यूटिंग (Edge Computing)
status: Completed
category: प्रौद्योगिकी
---

एज-कंप्यूटिंग एक [डिस्ट्रिब्यूटेड सिस्टम](/distributed-systems/) का दृष्टिकोण है, जो कुछ स्टोरेज और कंप्यूटिंग क्षमता को प्राथमिक डेटा केंद्र से डेटा स्रोत में स्थानांतरित करता है।
एकत्रित डेटा की गणना प्रसंस्करण और विश्लेषण के लिए केंद्रीकृत डेटा सेंटर में भेजने के बजाय स्थानीय स्तर पर की जाती है (उदाहरण के लिए, किसी कारखाने के फर्श पर, किसी स्टोर में, या पूरे शहर में)।
ये स्थानीय प्रसंस्करण डिवाइस सिस्टम के एज का प्रतिनिधित्व करते हैं, जबकि डेटा सेंटर इसका केंद्र है।
एज पर गणना किए गए आउटपुट को आगे की प्रक्रिया के लिए प्राथमिक डेटा सेंटर में वापस भेजा जाता है।
एज-कंप्यूटिंग के उदाहरणों में कलाई गैजेट या कंप्यूटर शामिल हैं जो ट्रैफ़िक प्रवाह का विश्लेषण करते हैं।

## समस्या

पिछले दशक में, हमने अत्याधुनिक एज-डिवाइस (जैसे, मोबाइल फोन, स्मार्ट घड़ियाँ, या सेंसर) की बढ़ती संख्या देखी है।
कुछ मामलों में, वास्तविक डेटा प्रोसेसिंग न केवल अच्छा है बल्कि महत्वपूर्ण भी है।
आप उदाहरण के तौर पर स्वचलित गाड़ियों के बारे में सोच सकते हैं।
अब कल्पना करें कि कार के सेंसर से डेटा को वाहन में वापस भेजने से पहले प्रसंस्करण के लिए डेटा सेंटर में स्थानांतरित करना होगा ताकि यह उचित रूप से प्रतिक्रिया कर सके।
इसके वजे से अंतर्निहित नेटवर्क में विलंबता घातक हो सकती है।
हालाँकि यह एक अति अधिक उदाहरण है, अधिकांश उपयोगकर्ता तत्काल प्रतिक्रिया प्रदान करने में असमर्थ स्मार्ट डिवाइस का उपयोग नहीं करना चाहेंगे।

## समाधान

जैसा कि ऊपर वर्णित है, एज-डिवाइसों के उपयोगी होने के लिए, उन्हें उपयोगकर्ताओं को वास्तविक समय पर प्रतिक्रिया प्रदान करने के लिए प्रसंस्करण और विश्लेषण का कम से कम हिस्सा स्थानीय स्तर पर करना होगा।
यह कुछ स्टोरेज और प्रसंस्करण संसाधनों को डेटा सेंटर से उस स्थान पर स्थानांतरित करके प्राप्त किया जाता है जहां डेटा उत्पन्न होता है: जैसे की एज-डिवाइस।
संसाधित और असंसाधित डेटा को बाद में आगे की प्रक्रिया और स्टोरेज के लिए डेटा सेंटर में भेजा जाता है।
संक्षेप में, कुशलता और गति एज-कंप्यूटिंग के प्राथमिक चालक हैं।