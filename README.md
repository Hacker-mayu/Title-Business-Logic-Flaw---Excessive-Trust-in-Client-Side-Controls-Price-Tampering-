Steps to Exploit
Log in and add the target item (e.g., the "Lightweight l33t leather jacket") to the basket.
Intercept the POST /cart add-to-basket request in Burp Suite.
Observe that the request includes a price parameter sourced from the client.
Modify the price value to a low amount (e.g., 1).
Forward the request and proceed to checkout.
Complete the purchase at the tampered price.
