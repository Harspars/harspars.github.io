## **Welcome to Chisholm Demo Site**

[Link](https://www.chisholm.edu.au/) and ![Image](Chisholm.jpg)

 <html>

<body>

	<header>
		
	</header>
	<div class="aside-left">
		<p align="center">
			<h3>Chisholm Information</h3>
		</p>
	</div>
	<main>
		<h1>On campus or in the workplace course enquiries</h1>
		<p>Our enquiry hubs will operate remotely from 10 January 2022. 

		   Phone:  1300 244 746
		   Phone lines open Monday to Friday 8.30am - 5.30pm.

		   Email: enquiries@chisholm.edu.au</p>
	</main>
	<aside>
		<h2>Apprenticeship Hub</h2>
		<h4>The Apprenticeship Hub is located in Building A, Dandenong. Entry is via the Student Hub.</h4>
	</aside>
	<footer>
			<div class="copyright">
			<p align="center">Copyright &copy; Chisholm Institute 2022</p>
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
	          {
            "id": "cx_webchat_form_prospective_student",
            "name": "ProspectiveStudent",
            "maxlength": "100",
            "placeholder": "Custom data placeholder",
            "label": "Prospective Student",
            "value": "Yes"
          },
          {
            "id": "cx_webchat_form_student_support",
            "name": "StudentSupport",
            "maxlength": "100",
            "placeholder": "Custom data placeholder",
            "label": "Student Support",
            "value": "No"
          }
	{	
	<label for="Student">Type of Student:</label>

		<select name="Student" id="Student">
  		<option value="Prospective Student">Prospective Student</option>
  		<option value="Student Support">Student Support</option>
		</select>
	}
        ]
      }
    };
  }

  const customPlugin = CXBus.registerPlugin('Custom');
</script>

<button type="button" id="chat-button" onclick="customPlugin.command('WebChat.open', getAdvancedConfig());">CHAT WITH ONE OF OUR TEAM NOW</button>


</body>
</html>
