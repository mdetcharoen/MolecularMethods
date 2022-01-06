# MolecularMethods

# Metagenomics tutorial
เราจะใช้ข้อมูลจำลองจากงานวิจัยของผมเองนะครับ นักศึกษาจะได้ข้อมูลที่เป็นไฟล์ fastq ที่ ตัวย่อของไฟล์ fastq มีได้เป็น fq และ fastq ไฟล์ข้อมูลได้มาจากตัวอย่างดิน ดินถูกนำไปสกัดดีเอ็นเอแล้วนำดีเอ็นเอที่ได้ไปหาลำดับเบสด้วยเทคโนโลยี next-generation sequencing ของบริษัท Illumina 
1. นักศึกษาดาวน์โหลดไฟล์ทั้งสองไฟล์ 
sub1.fq และ sub2.fq
ลองเปิดไฟล์ทั้งสองด้วย text editor software เช่น Notepad หรือ Notepad ++ หรือลองเปิดใน terminal ด้วยคำสั่ง cat เช่น cat sub1.fq.gz หรือ head sub1.fq.gz
สังเกตความแตกต่างระหว่างไฟล์ fasta และ fastq

![image](https://user-images.githubusercontent.com/70691598/148316965-ac438347-1634-4918-970d-28cb4fd01d83.png)

2. ศึกษาสถิติพื้นฐานของข้อมูลทั้งสองก่อนนำไปวิเคราะห์ด้วย fastqc 
ดาวน์โหลดซอฟต์แวร์ fastqc จาก https://www.bioinformatics.babraham.ac.uk/projects/fastqc/
คลิกที่ run_fastqc แล้วเลือกไฟล์ sub1.fq
![image](https://user-images.githubusercontent.com/70691598/148317160-09bf4377-eaa2-4529-ae86-44dd67fe847c.png)

 2.1 ไฟล์แต่ละไฟล์มีกี่ sequences?
 ![image](https://user-images.githubusercontent.com/70691598/148317181-56a099ff-b40a-4652-bb5c-a9109c3a1d19.png)
 

 2.2 แต่ละเบสใน sequences มีคุณภาพแตกต่างกันหรือไม่
 ![image](https://user-images.githubusercontent.com/70691598/148317190-ad5d8fa7-d83a-4f5a-b532-049015e5ae00.png)

 2.3 sequences มีความยาวกี่เบส

3. อัพโหลดไฟล์เข้าสู่ usegalaxy.eu
![image](https://user-images.githubusercontent.com/70691598/148321189-ec2a6b58-e78b-4d63-998b-7a748258977e.png)

