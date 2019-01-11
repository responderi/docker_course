First container is built from Dockerfile with:
sudo docker build -t curler .

Then we use command:
sudo docker run -it curler

And give
helsinki.fi

We get:
<!DOCTYPE HTML PUBLIC "-//IETF//DTD HTML 2.0//EN">
<html><head>
<title>301 Moved Permanently</title>
</head><body>
<h1>Moved Permanently</h1>
<p>The document has moved <a href="http://www.helsinki.fi/">here</a>.</p>
</body></html>

