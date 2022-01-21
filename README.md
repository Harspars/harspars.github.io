## Welcome to My Demo Site


### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

 <!DOCTYPE html>
 <html>
 <head>
	    <!-- Metas -->
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<meta name="description" content=" A Sample website designed to test Genesys Cloud CX features"
		
		<!-- Stylesheets -->
		<link rel="stylesheet" type="text/css" href="css/style.css">
		
		<title>HOME | BBTADemo.com</title>
</head>
<body>
<script type="text/javascript" charset="utf-8">
  (function (g, e, n, es, ys) {
    g['_genesysJs'] = e;
    g[e] = g[e] || function () {
      (g[e].q = g[e].q || []).push(arguments)
    };
    g[e].t = 1 * new Date();
    g[e].c = es;
    ys = document.createElement('script'); ys.async = 1; ys.src = n; ys.charset = 'utf-8'; document.head.appendChild(ys);
  })(window, 'Genesys', 'https://apps.mypurecloud.com.au/genesys-bootstrap/genesys.min.js', {
    environment: 'apse2',
    deploymentId: '014fd7be-96a4-482b-8172-a642689661a8'
  });
</script>
	<header>
		<div class="topnav" id="myTopnav">
			<p align="center">
				<a href="#home" class="active">Home</a>
				<a href="#news">News</a>
				<a href="#contact">Contact</a>
				<a href="#about">About</a>
				<a href="javascript:void(0);" class="icon" onclick="myFunction()">
					<i class="fa fa-bars"></i>
				</a>
			</p>
		</div>
	</header>
	<div class="aside-left">
		<p align="center">
			<h3>BLACKBOX AUSTRALIA DEMO</h3>
		</p>
	</div>
	<main>
		<h1>What would you like to buy</h1>
		<p>We provide several service like Portfolio Management, Insurance and Finance Options</p>
	</main>
	<aside>
		<h2>Our Offerings</h2>
		<h4>We provide hosted and Cloud Solutions for UCaaS and CCaaS</h4>
	</aside>
	<footer>
		<div class="left-footer">
			<p>Something will go here.</p>
		</div>
		<div class="center-footer">
			<p>Something will go in the center here.</p>
		</div>
		<div class="right-footer">
			<p>Something on the right.</p>
		</div>
		<div class="copyright">
			<p align="center">Copyright &copy; 2021 - 2022 BBTADemo.com</p>
		</div>
	</footer>

<script src="https://apps.mypurecloud.com.au/widgets/9.0/cxbus.min.js" onload="javascript:CXBus.configure({debug:false,pluginsPath:'https://apps.mypurecloud.com.au/widgets/9.0/plugins/'}); CXBus.loadPlugin('widgets-core');"></script>

<script>
  window._genesys = {
    "widgets": {
      "webchat": {
        "transport": {
          "type": "purecloud-v2-sockets",
          "dataURL": "https://api.mypurecloud.com.au",
          "deploymentKey": "99897707-60b8-4527-883d-afa00c14bd49",
          "orgGuid": "99d21775-62de-44cb-a90d-6d7010d44524",
          "interactionData": {
            "routing": {
              "targetType": "QUEUE",
              "targetAddress": "Demo Queue",
              "priority": 2
            }
          }
        },
        "userData": {
          "addressStreet": "",
          "addressCity": "",
          "addressPostalCode": "",
          "addressState": "",
          "phoneNumber": "",
          "customField1Label": "",
          "customField1": "",
          "customField2Label": "",
          "customField2": "",
          "customField3Label": "",
          "customField3": ""
        }
      }
    }
  };

  function getAdvancedConfig() {
    return {
      "form": {
        "autoSubmit": false,
        "firstname": "",
        "lastname": "",
        "email": "",
        "subject": ""
      },
      "formJSON": {
        "wrapper": "<table></table>",
        "inputs": [
          {
            "id": "cx_webchat_form_firstname",
            "name": "firstname",
            "maxlength": "100",
            "placeholder": "Required",
            "label": "First Name"
          },
          {
            "id": "cx_webchat_form_lastname",
            "name": "lastname",
            "maxlength": "100",
            "placeholder": "Required",
            "label": "Last Name"
          },
          {
            "id": "cx_webchat_form_email",
            "name": "email",
            "maxlength": "100",
            "placeholder": "Optional",
            "label": "Email"
          },
          {
            "id": "cx_webchat_form_subject",
            "name": "subject",
            "maxlength": "100",
            "placeholder": "Optional",
            "label": "Subject"
          }
        ]
      }
    };
  }

  const customPlugin = CXBus.registerPlugin('Custom');
</script>

<button type="button" id="chat-button" onclick="customPlugin.command('WebChat.open', getAdvancedConfig());">Lets Chat</button>


</body>
</html>
