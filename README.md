<b>This Integration allows you to update your agents timesheets with attendance events captured by the terminal solution "TimeMoto"</b>
<br><br>
![TimeMoto-to-Halo](https://github.com/user-attachments/assets/a4f9f3a1-6b4e-4bb5-af8b-18eee3c92791)
<br>
For this to work, you need to set the trigger of the runbook to webhook and pass the url to the webhook configuration in TimeMoto.<br>
This is how you configure the webhook within TimeMoto:<br><br>
<img width="1451" alt="Bildschirmfoto 2024-07-18 um 19 31 10" src="https://github.com/user-attachments/assets/041fa176-7f46-4df3-bcb8-37c888158231">
<br><br>
Finally you need to import the methods for your HaloPSA internal custom integration from the "halo-customintegration-TimeMoto.json" file.
The runbook itself can be imported from the "halo-TimeMoto-Integration.json"
<br><br>
<img width="1565" alt="Bildschirmfoto 2024-07-18 um 19 32 42" src="https://github.com/user-attachments/assets/921d9c5b-8b04-4c30-8f27-8bbe815d802f">
