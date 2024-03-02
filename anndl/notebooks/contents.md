<div style="page-break-after: always;"></div>


# สารบัญ

***

<table style="width:120%">
    <tr>
        <td style="width:80%"><div style="font-size: 18pt; text-align: left;">สารบัญ</div></td>
        <td><div style="text-align: right;">หน้า</div></td>
    </tr>
    <tr>
        <td><hr></td>
        <td><hr></td>
    </tr>
    <tr>
        <td style="width:90%"><div style="padding-top: 10px;">1. &nbsp; บทนำ</div></td><td><div style="text-align: right;padding-top: 10px;">1</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 1.1 &nbsp; ประวัติโดยย่อของโครงข่ายประสาทเทียม </td><td><div class="alignright">3</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 1.2 &nbsp; โครงข่ายประสาทเทียมเชิงลึก </td><td><div class="alignright">5</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 1.3 &nbsp; รูปแบบการเรียนรู้ </td><td><div class="alignright">6</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 1.3.1 &nbsp; แผนภาพการเรียนรู้เชิงลึก</td><td><div class="alignright">7</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 1.4 &nbsp; ซอฟต์แวร์สำหรับพัฒนา </td><td><div class="alignright">8</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 1.5 &nbsp; การใช้งาน TF เบื้องต้น </td><td><div class="alignright">18</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 1.5.1 &nbsp; ค่าคงที่ ตัวแปร และเทนเซอร์</td><td><div class="alignright">18</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 1.5.2 &nbsp; การเข้าถึงชั้นของโมเดล</td><td><div class="alignright">21</div></td>
    </tr>        
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 1.5.3 &nbsp; การเข้าถึงเทนเซอร์ในโมเดล</td><td><div class="alignright">23</div></td>
    </tr> 
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 1.5.4 &nbsp; พื้นฐานการถ่ายโอนการเรียนรู้</td><td><div class="alignright">24</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 1.5.5 &nbsp; การบันทึกและโหลดโมเดล</td><td><div class="alignright">27</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 1.6 &nbsp; โครงสร้างของหนังสือ </td><td><div class="alignright">28</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 1.7 &nbsp; สรุปท้ายบท </td><td><div class="alignright">29</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; โจทย์ปัญหา </td><td><div class="alignright">29</div></td>
    </tr>
    <tr>
        <td style="width:90%"><div style="padding-top: 10px;">2. &nbsp; โมเดลโครงข่ายประสาทเทียมเชิงลึก</div></td><td><div style="text-align: right;padding-top: 10px;">31</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 2.1 &nbsp; การถดถอยเชิงเส้น </td><td><div class="alignright">31</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 2.2 &nbsp; การถดถอยลอจิสติก </td><td><div class="alignright">34</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 2.2.1 &nbsp; ฟังก์ชันมูลค่า</td><td><div class="alignright">37</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 2.2.2 &nbsp; ขั้นตอนวิธีลดค่าเกรเดียนต์</td><td><div class="alignright">39</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 2.2.3 &nbsp; การลดค่าเกรเดียนต์สำหรับการถดถอยลอจิสติก</td><td><div class="alignright">42</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 2.2.4 &nbsp; การคำนวณในรูปเวกเตอร์</td><td><div class="alignright">45</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 2.3 &nbsp; โครงข่ายประสาทเทียมเชิงลึก </td><td><div class="alignright">51</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 2.3.1 &nbsp; แผนภาพการคำนวณสำหรับ DNN ชั้นแฝงเดี่ยว</td><td><div class="alignright">51</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 2.3.2 &nbsp; การคำนวณเชิงเวกเตอร์สำหรับทั้งชุดตัวอย่าง</td><td><div class="alignright">54</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 2.3.3 &nbsp; ฟังก์ชันกระตุ้นแบบไม่เป็นเชิงเส้น</td><td><div class="alignright">55</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 2.3.4 &nbsp; อนุพันธ์ของฟังก์ชันกระตุ้น</td><td><div class="alignright">58</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 2.3.5 &nbsp; การลดค่าเกรเดียนต์สำหรับ DNN ชั้นแฝงเดี่ยว</td><td><div class="alignright">59</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 2.3.6 &nbsp; โมเดล DNN หลายชั้นแฝง</td><td><div class="alignright">70</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 2.3.7 &nbsp; สร้างโมเดลโดยไลบรารี TF</td><td><div class="alignright">84</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 2.4 &nbsp; การจำแนกหลายประเภท </td><td><div class="alignright">91</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 2.4.1 &nbsp; ฟังก์ชันกระตุ้นแบบซอฟต์แมกซ์</td><td><div class="alignright">91</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 2.5 &nbsp; สรุปท้ายบท </td><td><div class="alignright">98</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; โจทย์ปัญหา </td><td><div class="alignright">99</div></td>
    </tr>
    <tr>
        <td style="width:90%"><div style="padding-top: 10px;">3. &nbsp; การปรับปรุงโครงข่ายประสาทเทียม</div></td><td><div style="text-align: right;padding-top: 10px;">101</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 3.1 &nbsp; การจัดการข้อมูล </td><td><div class="alignright">101</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 3.1.1 &nbsp; ค่าเอนเอียงและความแปรปรวน</td><td><div class="alignright">102</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 3.1.2 &nbsp; วิธีพื้นฐานในการลดค่าเอนเอียงและความแปรปรวน</td><td><div class="alignright">104</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 3.2 &nbsp; การปรับปรุงโมเดลความแปรปรวนสูง </td><td><div class="alignright">105</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 3.2.1 &nbsp; การเรกูลาไรเซชันโครงข่ายประสาทเทียม</td><td><div class="alignright">105</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 3.2.2 &nbsp; วิธีการดรอปเอาต์</td><td><div class="alignright">113</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 3.2.3 &nbsp; การแก้ปัญหาฟิตเกินโดยหยุดฝึกก่อนกำหนด</td><td><div class="alignright">117</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 3.3 &nbsp; การเตรียมข้อมูลและตั้งค่าพารามิเตอร์ </td><td><div class="alignright">120</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 3.3.1 &nbsp; การทำอินพุตให้เป็นบรรทัดฐาน</td><td><div class="alignright">120</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 3.3.2 &nbsp; การกำหนดค่าเริ่มต้นของพารามิเตอร์</td><td><div class="alignright">120</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 3.4 &nbsp; ขั้นตอนวิธีหาค่าเหมาะที่สุด </td><td><div class="alignright">128</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 3.4.1 &nbsp; การแบ่งข้อมูลเป็นกลุ่มย่อย</td><td><div class="alignright">128</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 3.4.2 &nbsp; วิธีโมเมนตัม</td><td><div class="alignright">130</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 3.4.3 &nbsp; วิธีการแพร่กระจายแบบรากกำลังสองเฉลี่ย</td><td><div class="alignright">132</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 3.4.4 &nbsp; วิธีการ Adam</td><td><div class="alignright">134</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 3.4.5 &nbsp; การลดระดับการเรียนรู้</td><td><div class="alignright">138</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 3.5 &nbsp; การทำกลุ่มให้เป็นบรรทัดฐาน </td><td><div class="alignright">139</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 3.6 &nbsp; สรุปท้ายบท </td><td><div class="alignright">146</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; โจทย์ปัญหา </td><td><div class="alignright">147</div></td>
    </tr>
    <tr>
        <td style="width:90%"><div style="padding-top: 10px;">4. &nbsp; โครงข่ายประสาทเทียมเชิงสังวัตนาการ</div></td><td><div style="text-align: right;padding-top: 10px;">149</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 4.1 &nbsp; การประมวลผลภาพโดยวิธีสังวัตนาการ </td><td><div class="alignright">150</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 4.1.1 &nbsp; การเสริมเต็มเมทริกซ์อินพุต</td><td><div class="alignright">154</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 4.1.2 &nbsp; การกำหนดช่วงก้าว</td><td><div class="alignright">155</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 4.1.3 &nbsp; การสังวัตนาการ 3 มิติ</td><td><div class="alignright">155</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 4.2 &nbsp; ชั้นสังวัตนาการในโครงข่ายประสาทเทียม </td><td><div class="alignright">156</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 4.2.1 &nbsp; ชั้นพูลลิง</td><td><div class="alignright">158</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 4.2.2 &nbsp; ตัวอย่างโมเดล CNN</td><td><div class="alignright">160</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 4.3 &nbsp; การแต่งเติมข้อมูลภาพ </td><td><div class="alignright">180</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 4.4 &nbsp; โมเดลกรณีศึกษา </td><td><div class="alignright">189</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 4.4.1 &nbsp; LeNet-5</td><td><div class="alignright">190</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 4.4.2 &nbsp; AlexNet</td><td><div class="alignright">190</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 4.4.3 &nbsp; VGG-16 และ VGG-19</td><td><div class="alignright">191</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 4.4.4 &nbsp; ResNets</td><td><div class="alignright">198</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 4.4.5 &nbsp; โครงข่ายอินเซปชัน</td><td><div class="alignright">208</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 4.5 &nbsp; การถ่ายโอนการเรียนรู้ </td><td><div class="alignright">211</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 4.6 &nbsp; การประยุกต์ใช้งานด้านการตรวจหาวัตถุ </td><td><div class="alignright">218</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 4.6.1 &nbsp; การจำแนกและระบุตำแหน่งวัตถุ</td><td><div class="alignright">218</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 4.6.2 &nbsp; วิธีการหน้าต่างเลื่อน</td><td><div class="alignright">221</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 4.6.3 &nbsp; การแปลงชั้นเชื่อมต่อเต็มเป็นชั้นสังวัตนาการ</td><td><div class="alignright">222</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 4.6.4 &nbsp; อิมพลิเมนต์หน้าต่างเลื่อนโดยการสังวัตนาการ</td><td><div class="alignright">223</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 4.7 &nbsp; ขั้นตอนวิธี YOLO </td><td><div class="alignright">224</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 4.7.1 &nbsp; อัตราส่วนอินเตอร์เซกชันต่อยูเนียน</td><td><div class="alignright">226</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 4.7.2 &nbsp; การขจัดการตรวจพบที่ไม่ใช่ค่ามากสุด</td><td><div class="alignright">227</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 4.7.3 &nbsp; กล่องจุดตรึง</td><td><div class="alignright">228</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 4.8 &nbsp; การประยุกต์ใช้งานด้านการรู้จำใบหน้า </td><td><div class="alignright">231</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 4.8.1 &nbsp; การเรียนรู้จากภาพเดียว</td><td><div class="alignright">232</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 4.8.2 &nbsp; โครงข่ายสยาม</td><td><div class="alignright">233</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 4.9 &nbsp; สรุปท้ายบท </td><td><div class="alignright">237</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; โจทย์ปัญหา </td><td><div class="alignright">238</div></td>
    </tr>
    <tr>
        <td style="width:90%"><div style="padding-top: 10px;">5. &nbsp; โครงข่ายประสาทเทียมวกกลับ</div></td><td><div style="text-align: right;padding-top: 10px;">241</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 5.1 &nbsp; สัญกรณ์สำหรับข้อมูลลำดับ </td><td><div class="alignright">241</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 5.2 &nbsp; โครงข่ายประสาทเทียมวกกลับ </td><td><div class="alignright">243</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 5.2.1 &nbsp; การแพร่กระจายข้างหน้าของ RNN</td><td><div class="alignright">244</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 5.2.2 &nbsp; การแพร่กระจายย้อนหลังของ RNN</td><td><div class="alignright">245</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 5.2.3 &nbsp; จำนวนอินพุตและเอาต์พุตของโมเดล RNN</td><td><div class="alignright">245</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 5.3 &nbsp; โมเดลอันดับสูงที่พัฒนาจาก RNN </td><td><div class="alignright">247</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 5.3.1 &nbsp; โมเดล GRU</td><td><div class="alignright">248</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 5.3.2 &nbsp; โมเดล LSTM</td><td><div class="alignright">250</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 5.3.3 &nbsp; โมเดล RNN สองทิศทาง</td><td><div class="alignright">252</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 5.3.4 &nbsp; โมเดล RNN เชิงลึก</td><td><div class="alignright">253</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 5.4 &nbsp; สร้างโมเดลอันดับโดยไลบรารี TF </td><td><div class="alignright">254</div></td>
    </tr>    
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 5.5 &nbsp; การพัฒนางาน NLP โดย TF ขั้นพื้นฐาน </td><td><div class="alignright">261</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 5.5.1 &nbsp; การเข้ารหัสคำ</td><td><div class="alignright">262</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 5.5.2 &nbsp; การเสริมเต็ม</td><td><div class="alignright">264</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; 5.5.3 &nbsp; การฝังตรึงคำศัพท์</td><td><div class="alignright">265</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; 5.6 &nbsp; สรุปท้ายบท </td><td><div class="alignright">274</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; โจทย์ปัญหา </td><td><div class="alignright">275</div></td>
    </tr>
    <tr>
        <td style="width:90%"><div style="padding-top: 10px;">A. &nbsp; รวมหลักการและวิธีการ</div></td><td><div style="text-align: right;padding-top: 10px;">277</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; A.1 &nbsp; ค่าเฉลี่ยที่ให้น้ำหนักแบบเลขชี้กำลัง </td><td><div class="alignright">277</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; A.1.1 &nbsp; การแก้ไขค่าเอนเอียง</td><td><div class="alignright">279</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; A.2 &nbsp; ข้อมูลอนุกรมเวลา </td><td><div class="alignright">281</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; A.2.1 &nbsp; แนวโน้ม</td><td><div class="alignright">282</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; A.2.2 &nbsp; องค์ประกอบตามฤดูกาล</td><td><div class="alignright">283</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; A.2.3 &nbsp; การรบกวน</td><td><div class="alignright">285</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; A.2.4 &nbsp; สหสัมพันธ์อัตโนมัติ</td><td><div class="alignright">286</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; A.2.5 &nbsp; อนุกรมเวลาไม่คงที่</td><td><div class="alignright">289</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; A.3 &nbsp; การพยากรณ์ข้อมูลอนุกรมเวลา </td><td><div class="alignright">290</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; A.3.1 &nbsp; ตัววัดสมรรถนะ</td><td><div class="alignright">291</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; A.3.2 &nbsp; เส้นฐานการพยากรณ์</td><td><div class="alignright">292</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; &emsp; A.3.3 &nbsp; การจัดรูปข้อมูลอนุกรมเวลา</td><td><div class="alignright">295</div></td>
    </tr>
    <tr>
        <td style="width:90%"><div style="padding-top: 10px;">B. &nbsp; ซอฟต์แวร์</div></td><td><div style="text-align: right;padding-top: 10px;">303</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; B.1 &nbsp; โปรแกรม GNU wget </td><td><div class="alignright">303</div></td>
    </tr>
    <tr>
        <td>&nbsp; &nbsp; &nbsp; B.2 &nbsp; การติดตั้ง TF และไลบรารีสนับสนุน </td><td><div class="alignright">304</div></td>
    </tr>
    <tr>
        <td style="width:90%"><div style="padding-top: 10px;">บรรณานุกรม</div></td><td><div style="text-align: right;padding-top: 10px;">305</div></td>
    </tr>
    <tr>
        <td style="width:90%"><div style="padding-top: 10px;">ประวัติผู้เขียน</div></td><td><div style="text-align: right;padding-top: 10px;">309</div></td>
    </tr>
    <tr>
        <td style="width:90%"><div style="padding-top: 10px;">ดัชนี</div></td><td><div style="text-align: right;padding-top: 10px;">311</div></td>
    </tr>    
</table>
