# 以人工智慧輔助計算喉部影像參數
「臺灣50」優良SMART on FHIR應用程式徵案活動。

- **說明：**  
此App為主啟動程式，由入口程式呼叫： `sof-ent` 。

- **App啟動流程：**  
THAS Sandbox啟動SMART App  
→ 經OAuth2/OIDC授權  
→ 從THAS FHIR取得Raw BMP  
→ 呼叫Render上的/predict  
→ 取得本次推論結果對應的Binary ID  
→ 從THAS FHIR取回PNG/PDF顯示

<br>

---
Developed by 185852 and 185661. Copyright © Changhua Christian Hospital. All rights reserved.
