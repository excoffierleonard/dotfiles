# lsusb

> यूएसबी बसों और उनसे जुड़े उपकरणों के बारे में जानकारी प्रदर्शित करें।
> अधिक जानकारी: <https://manned.org/lsusb>।

- उपलब्ध सभी USB उपकरणों की सूची बनाएं:

`lsusb`

- USB पदानुक्रम को एक ट्री के रूप में सूचीबद्ध करें:

`lsusb -t`

- USB उपकरणों के बारे में विस्तारित जानकारी की सूची बनाएं:

`lsusb --verbose`

- केवल निर्दिष्ट विक्रेता और उत्पाद आईडी वाले उपकरणों की सूची बनाएं:

`lsusb -d {{वेंडर}}:{{उत्पाद}}`