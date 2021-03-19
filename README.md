# UTS
Nama	: Alvin Yogie
NIM	: 03082180045
Kelas	: 18TI3

Aplikasi ini merupakan aplikasi berbasis web yang simple dimana hanya menampilkan sebarapa 
banyak orang yang terconnect, menampilkan message list atau chat, dan dapat melakukan send
message atau chating secara realtime. Aplikasi ini hanya bisa melakukan chat public tidak 
memiliki private chat kepada user lain. Pada dasarnya aplikasi ini seperti aplikasi chat 
discord. Di dalam folder terdapat 2 file utama yaitu app.js yang bertindak sebagai server 
dan index.html yang bertindak sebagai tampilan untuk user atau client.

Aplikasi ini saya program di vscode menggunakan node.js dan package yang saya pakai adalah
socket.io dan express. 

Dalam kasus ini saya akan menjelaskan bagaimana cara run di vscode. Pertama perlu memiliki
node.js yang sudah terinstall di komputer (biasanya sudah tersedia npm). Kedua pada terminal 
install socket.io dan express menggunakan commend "npm install socket.io express". Ketiga 
buka website seperti mozilla atau chrome dan pada tab (yang biasa tertulis www.google.com) 
tuliskan "localhost:3300". Keempat pada terminal tulis "node app" dan refresh di websitenya
maka tampilan di website akan berubah dan terconnect ke tampilan index.html nya. 

Untuk melakukan chat dengan user lain, dapat dilakukan dengan menambah tab dan menulis
localhost:3300 setelah terconnect maka jumlah user online akan bertambah dan bisa melakukan
chatting.
