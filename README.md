# othoba_Webapp_Load-Stress_Testing-JMeter

HTTP Methode: POST Method: Create new booking GET Method: Get booking with id POST Methode: Authentication for token PUT Methode: Update booking info DELETE Methode: Delete booking info

Dear viewers,

I’ve completed performance test on frequently used API for test App. Test executed for the below mentioned scenario in server 000.000.000.00.

10 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 9s; error rate~0.18% And Total Concurrent API requested: 1640.

20 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 17.2s;error rate~0.06% And Total Concurrent API requested:3280.

30 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 18s; error rate~1.09% And Total Concurrent API requested: 1470.

While executed 1470 concurrent request, found 16 request got connection timeout and error rate is 1.09%.

Summary: Server can handle almost concurrent 9100 API call with almost zero (0) error rate.

Please find the details report from the attachment and let me know if you have any further queries.
