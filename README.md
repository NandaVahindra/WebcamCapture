# WebcamCapture

Projek Aplikasi Sederhana Webcam Capture menggunakan bahasa C# dengan Visual Studio.  
Aplikasi ini dapat mendeteksi input video kamera yang terhubung pada PC kemudian dapat menampilkan video previewnya.
Tampilan Aplikasi: 
![Screenshot 2023-09-11 092634](https://github.com/NandaVahindra/WebcamCapture/assets/114988957/72dde15a-d034-4909-b1f1-172bf9e26705)

Pada box warna Orange, video preview akan ditampilkan, dan pada box warna biru hasil capture akan ditampilkan

ComboBox diprogram untuk menampilkan List dari source video pada PC dengan kode berikut :
https://github.com/NandaVahindra/WebcamCapture/blob/868d47e8fd87de53e2947b226ade7650c59e953e/MediaCapture/Form1.cs#L27-L37  
Hasil kode :
![Screenshot 2023-09-11 094532](https://github.com/NandaVahindra/WebcamCapture/assets/114988957/61d01d84-6610-47ca-8566-d6cdebd4d488)

Tombol start digunakan untuk menapilkan preview video sesuai dengan video device yang kita select
https://github.com/NandaVahindra/WebcamCapture/blob/868d47e8fd87de53e2947b226ade7650c59e953e/MediaCapture/Form1.cs#L39-L57  
Sebelum ditampilkan akan dicek terlebih dahulu apakah ada video source lain pada imagebox yang sedang berjalan jika ada maka akan distop terlebih dahulu.  
Tombol Capture diprogram untuk melakukan clone pada picturebox1 ke picturebox2 sehingga menghasilkan capture  
https://github.com/NandaVahindra/WebcamCapture/blob/868d47e8fd87de53e2947b226ade7650c59e953e/MediaCapture/Form1.cs#L59-L62  
Setelah itu tombol save diprogram untuk melakukan save pada picturebox2 dengan memberikan pilihan png dan jpeg.  
https://github.com/NandaVahindra/WebcamCapture/blob/868d47e8fd87de53e2947b226ade7650c59e953e/MediaCapture/Form1.cs#L64-L83  
Tombol Exit untuk keluar dari aplikasi. Sebelum keluar dari aplikasi, pastikan video source dan picturebox distop dan direset terlebih dahulu agar tidak menimbulkan error.  
https://github.com/NandaVahindra/WebcamCapture/blob/868d47e8fd87de53e2947b226ade7650c59e953e/MediaCapture/Form1.cs#L85-L97  

reference : https://www.youtube.com/watch?v=HUiV10g1VLU
