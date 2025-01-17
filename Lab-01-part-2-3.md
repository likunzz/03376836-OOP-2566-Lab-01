# Lab-01 Part 2~3 คำสั่ง Console.Write() และ Console.WriteLine()

## 2. การใช้เมดธอด Console.Write()

### 2.1 การใช้เมดธอด Console.Write()
👉 แก้ไขโปรแกรม ให้เป็นดังด้านล่างนี้
```csharp
Console.Write("Hello");
Console.Write("Hello");
```

➢ รันโปรแกรมและบันทึกผล
![image](https://github.com/likunzz/03376836-OOP-2566-Lab-01/assets/144196696/9221e36b-3774-4287-b64f-1869be49da9e)

❔ ผลที่ได้จากการทดลอง เป็นอย่างที่นักศึกษาคิดหรือไม่ อย่างไร จงอธิบาย
### -เป็นไปตามที่คิดไว้ เพราะใช้คำสั่ง Console.Write("..."); 2 รอบ แสดงผลออกมาทางคอนโทรล(ได้ข้อความติดกัน เนื่องจากไม่ได้กำหนดคำสั่งให้เว้นบรรทัด) 


### 2.2 การใช้เมดธอด Console.Write() ร่วมกับ  `Environment.NewLine`

`Environment.NewLine` เป็นค่าคงที่ที่ถูกนิยามในภาษา C# เพื่อใช้สำหรับการส่งอักขระขึ้นบรรทัดใหม่ไปยัง console

👉 แก้ไขโปรแกรม ให้เป็นดังด้านล่างนี้

```csharp
Console.Write("Hello" + Environment.NewLine);
Console.Write("Hello" + Environment.NewLine);
```

➢ รันโปรแกรมและบันทึกผล
![image](https://github.com/likunzz/03376836-OOP-2566-Lab-01/assets/144196696/43e20cf4-11ca-4255-a590-49617ad441b9)

❔ ผลที่ได้จากการทดลอง เป็นอย่างที่นักศึกษาคิดหรือไม่ อย่างไร จงอธิบาย

### -เป็นไปตามที่คิดไว้ เพราะใช้คำสั่งร่วมกับ Environment.NewLine กำหนดให้โปรแกรมขึ้นบรรทัดใหม่จึงได้ผลออกมาเป็น Hello ซึ่งอยู่คนละบรรทัดกัน

## 3. เมดธอด Console.WriteLine()

`Console.WriteLine()` เป็นคำสั่งที่เทียบเท่ากับการใช้  `Console.Write` ร่วมกับ  `Environment.NewLine` ทำให้ประหยัดเวลาในการเขียนโปรแกรม
👉 แก้โปรแกรมในเมดธอด Main() ให้เป็นดังต่อไปนี้

```csharp
Console.WriteLine("Hello");
```

➢ รันโปรแกรมและบันทึกผล

![image](https://github.com/likunzz/03376836-OOP-2566-Lab-01/assets/144196696/cff8467f-212c-4486-bee0-a15326522643)



👉 แก้ไขโปรแกรม ให้เป็นดังรูปด้านล่างนี้

```csharp
Console.Write("Hello, ");
Console.WriteLine("World!");
```

➢ รันโปรแกรมและบันทึกผล

![image](https://github.com/likunzz/03376836-OOP-2566-Lab-01/assets/144196696/d6d4f5f7-0648-438b-b036-eb2118ff4081)


❔ ผลที่ได้จากการทดลอง เป็นอย่างที่นักศึกษาคิดหรือไม่ อย่างไร จงอธิบาย

### เป็นไปตามที่คิดไว้ได้ Hello, world! ติดกัน เนื่องจากคำสั่งแรกที่ใช้คือ Console.Write ทำให้ข้อมูลที่ถูกแสดงจะต่อท้ายกับข้อมูลที่ถูกแสดงล่าสุดในบรรทัดเดียวกัน

❔ จงอธิบายความแตกต่างระหว่างคำสั่ง Console.Write() และ Console.WriteLine()

### Console.Write() ใช้เพื่อแสดงข้อมูลทางหน้าจอโดยไม่ขึ้นบรรทัดใหม่ แต่ Console.WriteLine() ใช้เพื่อแสดงข้อมูลทางหน้าจอและขึ้นบรรทัดใหม่

## [4. จำนวนของอาร์กิวเมนต์ในคำสั่ง Console.WriteLine()](./Lab-01-part-4.md)
