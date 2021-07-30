FULL STACK + MVC + 
routes = controllers (MVC)


"body-parser" Library ==> it needs to use req.body.
We need to write it in server.js:
const bodyParser = require('body-parser');
app.use(bodyParser.urlencoded({ limit: '10mb', extended: false })) 


<form method="GET"> ---- method GET as "app.get('/', (req, res) ...)