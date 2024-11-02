## How to run Super Dev Mode? (v1)

Be aware that the Super Dev Mode is only available in GWT 2.5+. Additionally be aware that Super Dev Mode requires specific browsers to work!

This chapter does not describe the usage of “Super Dev Mode” in detail. Please refer to the official documentation to learn how to use it. Be aware that you need to adjust your *gwt.xml” file or provide a special one for development.

In contrast to the “normal” Development Mode, the Super Dev Mode does not start the complete web application for you. Instead you have to run the web application by yourselves. Please refer to [the draft war](the draft war.html) for details on how to startup the draft war using a servlet container.

To start the Super Dev Mode, execute the task “gwtSuperDev”. When it is ready you will see the message “Next, visit: http://localhost:9876/”. Do exactly that and open “http://localhost:9876/” in your browser. You will now see two Buttons “Dev Mode On” and “Dev Mode Off”. Drag&drop these to your browser’s bookmark bar.

Now navigate your browser to the webapp hosting your application. Press the “Dev Mode On” bookmark. Now you should see a dialog listing all your gwt modules. Select the one you want to debug. The page will reload after the Super Dev Mode recompiled your GWT module. You can now debug the application using the developer tools of your browser.
