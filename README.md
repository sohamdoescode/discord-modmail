# Z Support Modmail Bot
Simple modmail bot for Discord servers, which is easy to set up and run yourself
 <h1> IMPORTANT NOTICE </h1> 
 <br>
 I highly recommend that you DO NOT use this as of now as its filled with bugs. I will probably make a rewrite sometime :)
 <br>
<h3>Requirements</h3>
💠 node.js
<br>
💠 mongoDB pass
<br>
<I><B>Dont know how to get a mongoDB pass?</B></I>-> Click <a href="https://www.youtube.com/watch?v=4X2qsZudLNY">HERE</a> (Thanks to DashCruft)
<br>
<br>
<h3> Running the Bot Yourself</h3>
<b>Step 1 :</b> Clone this repository
<br>
<b>Step 2 :</b> Head over to <code>config</code> directory and open up the <code>settings.json</code> file
<br>
<b>Step 3 :</b> Fill in all the necessary details (stated there) and save the file
<br>
<b>Step 4 :</b> Run <code>npm i</code> in the console and all the other dependencies should be installed
<br>
<b>Step 5 :</b> Run <code>node .</code> OR <code>node index.js</code> and your bot should be up and working!
<br>
<b><i>Note :</b></i> In order to keep the bot running 24x7, you may host it on Repl.it, Glitch or Heroku, but a VPS is recommended
<br>
<br>
<h3> Commands </h3>
<b>Default prefix:</b> <code>!</code>
<br>
<code>!reply <reply></code> OR <code>!r <reply></code> : Replies to a thread with the specified (SUPPORT TEAM ONLY)
<br>
<code>!close</code> : Closes a thread with a 10 seconds timeout
<br>
<h4>Pre-defined Snippets</h4>
These snippets come in handy while handling ModMails. When executed (with <code>!<snippet name</code></code>), the corresponding response is triggered and sent to the thread author.
<br>
<b> Snippets and their replies : </b>
<br>
<code>hi</code>: "Hi there! Thank you for contacting our staff team. How may we help you today?"
<br>
<code>transferred</code>: "We have notified the respective department regarding this thread. They will be getting back to you as soon as they can"
<br>
<code>reported</code>: "Thank you for bringing this to our attention. We have started an investigation and needed action will be taken soon"
<br>
<code>morehelp</code>: "Is there anything else we can help you with today?"
<br>
<code>noreply</code>: "This is a gentle reminder that this thread will be closed if you do not reply to it within the next 24 hours"
<br>
<br>
<b> Example Usage </b>
<code> !hi </code> will make the bot reply "Hi there! Thank you for contacting our staff team. How may we help you today?" to the thread author.
<br>
<br>
<h3>More Help</h3>
<br>
Made with ♥️ by Soham#7975 (Discord username)
<br>
Please don't add me on Discord for issues regarding this
