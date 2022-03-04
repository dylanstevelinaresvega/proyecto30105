const http = requiere('http');

Const port = 80;

const server = http.createServer((req,res) => {
	res.statusCode = 200;
	res.setHeader('content-Type','text/plain');
	res.end('Hello World')
});

server.listen(port, () => {
	console.log('Server running on port ${port}');
});
