<!DOCTYPE html>
<html>
<head>
    <title>موقع مثالي</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css">
</head>
<body>
    <div class="container">
        <h1>مرحبا بك في موقعنا</h1>
        <p>يمكنك تحميل ملفاتك من هنا:</p>
        <form action="upload.php" method="post" enctype="multipart/form-data">
            <div class="form-group">
                <label for="fileToUpload">اختر ملفًا لتحميله:</label>
                <input type="file" name="fileToUpload" id="fileToUpload">
            </div>
            <button type="submit" name="submit" class="btn btn-primary">تحميل الملف</button>
