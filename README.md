# & Ampersand Maker

## Start App

```sh
run.exe
```

Open Browser: http://localhost:8069/

## คำอธิบายเพิ่มเติม

```sh
รูปภาพทั้งหมดจะถูกเก็บไว้ที่ images โฟลเดอร์

images/
-- Background
-- Skin
-- Body
-- Head
-- Eyes
-- Mouth

NOTE 1: สามารถเพิ่มหรือลดจำนวน เครื่องประดับได้ เช่น ผู้ใช้อยากเพิ่มแขนตัวละครก็ให้สร้างโฟลเดอร์ Arm เพิ่ม
```

```sh
รูปภาพทั้งหมดที่ถูกสร้างจะออกมาใน output/images โฟลเดอร์

images/
-- 1.png
-- 2.png
-- 3.png
```

```sh
สุดท้ายโปรแกรมจะสร้าง metadata ให้ด้วยตามชื่อไฟล์ output/metadata โฟลเดอร์

metadata/
-- 1
-- 2
-- 3

ตัวอย่าง

{
  "name": "name #1",
  "description": "description",
  "image": "https://domain.com/image/1.png",
  "attributes": [
    {
      "trait_type": "Background",
      "value": "Pink",
      "score": 50,
    },
    {
      "trait_type": "Skin",
      "value": "Pinky",
      "score": 50,
    },
    {
      "trait_type": "Body",
      "value": "Sun Flower T-Shirt",
      "score": 50,
    },
    {
      "trait_type": "Eyes",
      "value": "Chill Eyes",
      "score": 50,
    },
    {
      "trait_type": "Head",
      "value": "Banana",
      "score": 50,
    },
    {
      "trait_type": "Mouth",
      "value": "Pink Bubblegum",
      "score": 50,
    }
  ]
}
```
