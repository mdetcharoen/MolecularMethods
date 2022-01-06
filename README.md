# Metagenomics tutorial
เราจะใช้ข้อมูลจำลองจากงานวิจัยของผมเองนะครับ นักศึกษาจะได้ข้อมูลที่เป็นไฟล์ fastq ที่ ตัวย่อของไฟล์ fastq มีได้เป็น fq และ fastq ไฟล์ข้อมูลได้มาจากตัวอย่างดิน ดินถูกนำไปสกัดดีเอ็นเอแล้วนำดีเอ็นเอที่ได้ไปหาลำดับเบสด้วยเทคโนโลยี next-generation sequencing ของบริษัท Illumina 
1. นักศึกษาดาวน์โหลดไฟล์
sub4.fq
https://github.com/mdetcharoen/MolecularMethods/blob/main/sub4.fq

ลองเปิดไฟล์ด้วย text editor software เช่น Notepad หรือ Notepad ++ หรือลองเปิดใน terminal ด้วยคำสั่ง cat เช่น cat sub4.fq หรือ head sub4.fq
สังเกตความแตกต่างระหว่างไฟล์ fasta และ fastq

![image](https://user-images.githubusercontent.com/70691598/148346653-2e76016d-32c8-420d-8e97-2698959915e4.png)


2. ศึกษาสถิติพื้นฐานของข้อมูลทั้งสองก่อนนำไปวิเคราะห์ด้วย fastqc 
ดาวน์โหลดซอฟต์แวร์ fastqc จาก https://www.bioinformatics.babraham.ac.uk/projects/fastqc/
คลิกที่ run_fastqc แล้วเลือกไฟล์ sub1.fq

![image](https://user-images.githubusercontent.com/70691598/148317160-09bf4377-eaa2-4529-ae86-44dd67fe847c.png)

 2.1 ไฟล์แต่ละไฟล์มีกี่ sequences?
 
 ![image](https://user-images.githubusercontent.com/70691598/148346810-c25cb494-81ed-4655-a4fa-8b0aa7fa0bd6.png)


 2.2 แต่ละเบสใน sequences มีคุณภาพแตกต่างกันหรือไม่
 
 ![image](https://user-images.githubusercontent.com/70691598/148346854-1c354243-d180-46e4-9534-68f4d0259cae.png)

 2.3 sequences มีความยาวกี่เบส

3. อัพโหลดไฟล์เข้าสู่ usegalaxy.eu

![image](https://user-images.githubusercontent.com/70691598/148321189-ec2a6b58-e78b-4d63-998b-7a748258977e.png)

4. เมื่ออัพโหลดไฟล์เสร็จแล้วให้เข้าสู่ workflow ที่ผมทำขึ้นครับ คลิกที่ลิงค์นี้ https://usegalaxy.eu/u/detcharoen/w/metagenomics-data
5. กดที่ปุ่ม run workflow ที่มุมบนขวา

![image](https://user-images.githubusercontent.com/70691598/148347731-ca0ae72b-d7bd-446e-b2ff-4c0931b51a2f.png)

6. เลือกไฟล์ sub4.fq แล้วกด Run Workflow

![image](https://user-images.githubusercontent.com/70691598/148348197-df130a27-bf35-40bb-9137-ba9e6ac0d737.png)

7. รอ ระหว่างนี้จะเห็นไฟล์ output ที่ได้จากขั้นตอนต่าง ๆ ในช่อง history ทางขวามือ

![image](https://user-images.githubusercontent.com/70691598/148348457-d7f44c30-2d3f-46e2-8b08-9beaeae8a1f5.png)
8. กดดูผล fastQC 

![image](https://user-images.githubusercontent.com/70691598/148349994-36dd7490-19b1-4d85-b852-9354b2561cf6.png)

![image](https://user-images.githubusercontent.com/70691598/148350073-0516ab81-70d1-412d-8ba6-2ba25ab177fd.png)

9. กดดูผลลัพท์ Krona pie chart
คลิกที่รูปดวงตา

![image](https://user-images.githubusercontent.com/70691598/148361196-f0e840be-b60b-44f9-b3df-f5547249dd50.png)

ลองกดที่ปุ่มต่าง ๆ สังเกตการเปลี่ยนแปลงที่เกิดขึ้นบนกราฟ

![image](https://user-images.githubusercontent.com/70691598/148361362-3ced911c-66db-4e0a-9297-85eb6d5fb016.png)


