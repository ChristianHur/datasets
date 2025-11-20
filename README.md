# Datasets (JSON)

This repository contains a JSON dataset.  
You can access this file remotely from any front-end app (React, Vue, Angular, plain JS).

---

## 🌐 Raw GitHub URL (for Fetch/Axios)
After uploading to GitHub, click the **RAW** button on `flight-data.json` and copy the link.

It will look like:


Use this URL inside your React or JavaScript app.

---

## 📥 Fetch Example (JavaScript)

```js
fetch("https://raw.githubusercontent.com/christianhur/datasets/main/flight-data.json")
  .then(res => res.json())
  .then(data => console.log(data))
  .catch(err => console.log(err));
